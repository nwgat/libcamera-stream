# libcamera-stream
Create a libcamera service that streams to go2rtc

* uses a libcamera-stream.conf file for easy configuration
* seem to work fine with 6.5 MBps bitrate but the preview might fail on pi zero 2 w if you have it at 10 Mbps
* 

# 
* libcamera-stream.conf = configuration file
* libcamera-stream.service = systemd service for ubuntu
* libcamera-stream = rc-service for alpine
* go2rtc.yaml = configuration for go2rtc
