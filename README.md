# Patchwork Data
This repo contains various data about or is used by Patchwork Archive. Below you'll find a description about each file

## radio.m3u
The playlist of all URLs that [Patchwork Radio](https://patchwork.moekyun.me/radio) plays.

**THIS IS NOT** a full list of what videos are archived. 
- Shorts and other videos that are not suited for playback on the radio are removed.
- Links are added by chunks and aren't updated on a regular schedule

# songs.sql
A dump of the fallback database for videos that appear in the archive. Data from here is used if the .info.json metadata is unavailable. The file here serves as an emergency backup.

# channels.txt
A list of VTuber channels that should be crawled (may not be fully complete or 100% accurate)
