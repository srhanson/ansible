#!/bin/bash

sourceDir="/media/Data/transmission/completed/"
destDir="/media/Data/Media/Torrents"
logfile="$destDir/rlog"

function log() {
    echo "$(date): $@" >> $logfile
}

scriptName="$(basename "$0")"

log "Starting job"

numJobsRunning=$(pgrep "$scriptName" | wc -l)
if [ $numJobsRunning -gt 2 ]; then
	log "Too many ($numJobsRunning) concurrent jobs running" 
	exit
fi

rsync -r -v --partial --exclude '*.part' "$@" $sourceDir $destDir >> $logfile

log "Job finished"
