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

A sample file timing.txt is provided with this

