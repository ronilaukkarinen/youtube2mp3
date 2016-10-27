# youtube2mp3

A simple bash script for *nixers who sometimes need the song quickly in mp3 format, for example for ringtone or morning alarm.

## Requirements

- [ffmpeg](https://www.ffmpeg.org/) - Cross-platform solution to record, convert and stream audio and video.
- [youtube-dl](https://github.com/rg3/youtube-dl) - Command-line program to download videos from YouTube.com and other video sites
- [id3v2](http://id3v2.sourceforge.net/) - A command line editor for id3v2 tags

## Installation

1. Git clone repository to your desired path
2. Symlink: `sudo ln -s /path/to/youtube2mp3/youtube2mp3 /usr/local/bin/youtube2mp3`
3. Add execute permissions: `sudo chmod +x /usr/local/bin/youtube2mp3`

## Usage

````
$ youtube2mp3 

Usage: youtube2mp3 [URL]
````

Update with `cd /path/to/youtube2mp3 && git pull`.