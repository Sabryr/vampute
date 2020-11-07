# vampute
Amputer is wrapper for ffmpeg. 

[ffmpeg](https://ffmpeg.org/)

This script can be used to remove parts of  a video. This was 
initially designed to support the processing of videos
for [CodeRefinery project](https://coderefinery.org/).
Specifically to remove parts of the video where the faces of
participants are exposed

# Dependancies
ffmpeg need to be installed first

**Ubuntu**
 
 - sudo apt update
 - sudo apt install ffmpeg

# Usage
The script requires two inputs:
 
1. The video to be cleaned
2. A file with portions to be removed

./vampute <VIDEO_FILE> <TIMING_FILE>


## Timing file format

START_TIME,END_TIME
00:10,00:50
01:10,01:50
02:10,02:50

A sample file timing.txt is provided with this

