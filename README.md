# video-streamer
This repository houses a docker compose file, which sets up two containers to stream a video. The compose file is based on jrottenberg/ffmpeg and tiangolo/nginx-rtmp.

# Usage
Start the containers with docker-compose up and connect with a video streaming software (e.g.g VLC) to rtmp://videoserver/live/my_url.

# License
To this point, I have not found  a license for jrottenberg/ffmpeg. tiangolo/nginx-rtmp-docker is published under MIT, so is this repository.
The example video in this repository is published by https://peach.blender.org/about/ under Creative Commons Attribution 3.0.
