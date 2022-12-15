# dlm3u8
This guide show you how to download directly m3u8 as mp4 to your linux using ffmpeg

Install ffmpeg first.

Ubuntu - 
sudo apt-get update -y
sudo apt-get install ffmpeg -y



ffmpeg -y -loglevel verbose -i "http://yourlink/yourchannel.m3u8" -c copy -f mpegts "yourvideo.mp4"

