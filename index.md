![alt text](https://whs-dot-hk.github.io/ubuntu-htpc/smplayer_mpv_log.png "SMPlayer mpv log")
## mpv log
```
/usr/local/bin/mpv --no-config --no-quiet --terminal --no-msg-color --input-file=/dev/stdin --no-fs --hwdec=no --sub-auto=fuzzy --stop-screensaver --no-input-default-bindings --input-vo-keyboard=no --no-input-cursor --cursor-autohide=no --no-keepaspect --wid=60817474 --monitorpixelaspect=1 --osd-level=1 --osd-scale=1 --osd-bar-align-y=0.6 --sub-ass --embeddedfonts --sub-ass-line-spacing=0 --sub-scale=1 --sub-font=Arial --sub-color=#ffffffff --sub-shadow-color=#ff000000 --sub-border-color=#ff000000 --sub-border-size=0.75 --sub-shadow-offset=2.5 --sub-font-size=50 --sub-bold=no --sub-italic=no --sub-codepage=ISO-8859-1 --vid=1 --aid=1 --sub-pos=100 --volume=55 --cache=auto --start=15 --screenshot-template=cap_%F_%p_%02n --screenshot-format=jpg --screenshot-directory=/home/whs/Pictures/smplayer_screenshots --audio-pitch-correction=yes --volume-max=110 --hwdec=nvdec --vo=gpu --term-playing-msg=MPV_VERSION=${=mpv-version:}
INFO_VIDEO_WIDTH=${=width}
INFO_VIDEO_HEIGHT=${=height}
INFO_VIDEO_ASPECT=${=video-aspect}
INFO_VIDEO_FPS=${=container-fps:${=fps}}
INFO_VIDEO_FORMAT=${=video-format}
INFO_VIDEO_CODEC=${=video-codec}
INFO_AUDIO_FORMAT=${=audio-codec-name}
INFO_AUDIO_CODEC=${=audio-codec}
INFO_AUDIO_RATE=${=audio-params/samplerate}
INFO_AUDIO_NCH=${=audio-params/channel-count}
INFO_LENGTH=${=duration:${=length}}
INFO_DEMUXER=${=current-demuxer:${=demuxer}}
INFO_SEEKABLE=${=seekable}
INFO_TITLES=${=disc-titles}
INFO_CHAPTERS=${=chapters}
INFO_TRACKS_COUNT=${=track-list/count}
METADATA_TITLE=${metadata/by-key/title:}
METADATA_ARTIST=${metadata/by-key/artist:}
METADATA_ALBUM=${metadata/by-key/album:}
METADATA_GENRE=${metadata/by-key/genre:}
METADATA_DATE=${metadata/by-key/date:}
METADATA_TRACK=${metadata/by-key/track:}
METADATA_COPYRIGHT=${metadata/by-key/copyright:}
INFO_MEDIA_TITLE=${=media-title:}
INFO_STREAM_PATH=${stream-path}
 --audio-client-name=SMPlayer --term-status-msg=STATUS: ${=time-pos} / ${=duration:${=length:0}} P: ${=pause} B: ${=paused-for-cache} I: ${=core-idle} VB: ${=video-bitrate:0} AB: ${=audio-bitrate:0} /home/whs/Videos/The_Greatest_Showman/The_Greatest_Showman_t01.mkv

Playing: /home/whs/Videos/The_Greatest_Showman/The_Greatest_Showman_t01.mkv
 (+) Video --vid=1 (h264 1920x1080 23.976fps)
 (+) Audio --aid=1 --alang=eng (*) 'Surround 5.1' (dts 6ch 48000Hz)
     Audio --aid=2 --alang=eng 'Surround 5.1' (ac3 6ch 48000Hz)
     Audio --aid=3 --alang=spa 'Surround 5.1' (ac3 6ch 48000Hz)
     Audio --aid=4 --alang=fra 'Surround 5.1' (ac3 6ch 48000Hz)
     Subs  --sid=1 --slang=eng (hdmv_pgs_subtitle)
     Subs  --sid=2 --slang=spa (hdmv_pgs_subtitle)
     Subs  --sid=3 --slang=spa (hdmv_pgs_subtitle)
     Subs  --sid=4 --slang=fra (hdmv_pgs_subtitle)
     Subs  --sid=5 --slang=fra (hdmv_pgs_subtitle)
     Subs  --sid=6 --slang=eng (hdmv_pgs_subtitle)
     Subs  --sid=7 --slang=spa (hdmv_pgs_subtitle)
     Subs  --sid=8 --slang=fra (hdmv_pgs_subtitle)
     Subs  --sid=9 --slang=eng (hdmv_pgs_subtitle)
File tags:
 Title: The Greatest Showman
[vo/gpu/drmprime-drm] Failed to retrieve DRM fd from native display.
Using hardware decoding (nvdec).
AO: [alsa] 48000Hz stereo 2ch float
VO: [gpu] 1920x1080 cuda[nv12]
INFO_VIDEO_DSIZE=1920x1080
MPV_VERSION=mpv 0.28.0-UNKNOWN
INFO_VIDEO_WIDTH=1920
INFO_VIDEO_HEIGHT=1080
INFO_VIDEO_ASPECT=1.777778
INFO_VIDEO_FPS=23.976025
INFO_VIDEO_FORMAT=h264
INFO_VIDEO_CODEC=h264 (H.264 / AVC / MPEG-4 AVC / MPEG-4 part 10)
INFO_AUDIO_FORMAT=dts
INFO_AUDIO_CODEC=dca (DCA (DTS Coherent Acoustics))
INFO_AUDIO_RATE=48000
INFO_AUDIO_NCH=6
INFO_LENGTH=6289.312000
INFO_DEMUXER=mkv
INFO_SEEKABLE=yes
INFO_TITLES=
INFO_CHAPTERS=20
INFO_TRACKS_COUNT=14
METADATA_TITLE=The Greatest Showman
METADATA_ARTIST=
METADATA_ALBUM=
METADATA_GENRE=
METADATA_DATE=
METADATA_TRACK=
METADATA_COPYRIGHT=
INFO_MEDIA_TITLE=The Greatest Showman
INFO_STREAM_PATH=/home/whs/Videos/The_Greatest_Showman/The_Greatest_Showman_t01.mkv
INFO_CHAPTER_0_NAME=Chapter 01
INFO_CHAPTER_1_NAME=Chapter 02
INFO_CHAPTER_2_NAME=Chapter 03
INFO_CHAPTER_3_NAME=Chapter 04
INFO_CHAPTER_4_NAME=Chapter 05
INFO_CHAPTER_5_NAME=Chapter 06
INFO_CHAPTER_6_NAME=Chapter 07
INFO_CHAPTER_7_NAME=Chapter 08
INFO_CHAPTER_8_NAME=Chapter 09
INFO_CHAPTER_9_NAME=Chapter 10
INFO_CHAPTER_10_NAME=Chapter 11
INFO_CHAPTER_11_NAME=Chapter 12
INFO_CHAPTER_12_NAME=Chapter 13
INFO_CHAPTER_13_NAME=Chapter 14
INFO_CHAPTER_14_NAME=Chapter 15
INFO_CHAPTER_15_NAME=Chapter 16
INFO_CHAPTER_16_NAME=Chapter 17
INFO_CHAPTER_17_NAME=Chapter 18
INFO_CHAPTER_18_NAME=Chapter 19
INFO_CHAPTER_19_NAME=Chapter 20
INFO_TRACK_0: video 1 'eng' '' yes
INFO_TRACK_1: audio 1 'eng' 'Surround 5.1' yes
INFO_TRACK_2: audio 2 'eng' 'Surround 5.1' no
INFO_TRACK_3: audio 3 'spa' 'Surround 5.1' no
INFO_TRACK_4: audio 4 'fra' 'Surround 5.1' no
INFO_TRACK_5: sub 1 'eng' '' no
INFO_TRACK_6: sub 2 'spa' '' no
INFO_TRACK_7: sub 3 'spa' '' no
INFO_TRACK_8: sub 4 'fra' '' no
INFO_TRACK_9: sub 5 'fra' '' no
INFO_TRACK_10: sub 6 'eng' '' no
INFO_TRACK_11: sub 7 'spa' '' no
INFO_TRACK_12: sub 8 'fra' '' no
INFO_TRACK_13: sub 9 'eng' '' no
```
# Ubuntu 18.04 LTS HTPC Guide
We will install `SMPlayer` with `NVDEC` support
## Update and Upgrade Ubuntu
```
$ sudo apt-get update
$ sudo apt-get upgrade
```
## Install Git
```
$ sudo apt-get install git
```

## Install the Latest Kernel
Download
* <http://kernel.ubuntu.com/~kernel-ppa/mainline/v4.16.7/linux-headers-4.16.7-041607_4.16.7-041607.201805021131_all.deb>
* <http://kernel.ubuntu.com/~kernel-ppa/mainline/v4.16.7/linux-headers-4.16.7-041607-generic_4.16.7-041607.201805021131_amd64.deb>
* <http://kernel.ubuntu.com/~kernel-ppa/mainline/v4.16.7/linux-image-unsigned-4.16.7-041607-generic_4.16.7-041607.201805021131_amd64.deb>
* <http://kernel.ubuntu.com/~kernel-ppa/mainline/v4.16.7/linux-modules-4.16.7-041607-generic_4.16.7-041607.201805021131_amd64.deb>

Run
```
$ cd ~/Downloads
$ sudo dpkg -i *.deb
```
## Install the Latest Nvidia Driver
```
$ sudo add-apt-repository ppa:graphics-drivers/ppa
$ sudo apt-get update
$ sudo apt-get install nvidia-390
```
### Enable OpenGL
```
$ sudo apt-get install xorg-dev
```
## Install CUDA
```
$ sudo apt-get install nvidia-cuda-toolkit
```
## FFmpeg
### Install Nvidia Codec Headers
```
$ cd ~/Downloads
$ git clone https://git.videolan.org/git/ffmpeg/nv-codec-headers.git
$ cd nv-codec-headers
$ sudo make install
```
### Install Yasm
```
$ sudo apt-get install yasm
```
### Install libass
```
$ sudo apt-get install libass-dev
```
### Compile and Install FFmpeg
```
$ cd ~/Downloads
$ wget https://www.ffmpeg.org/releases/ffmpeg-snapshot-git.tar.bz2
$ tar -xjvf ffmpeg-snapshot-git.tar.bz2
$ cd ffmpeg
$ ./configure --enable-libass --extra-cflags="-fPIC" --enable-cuda-sdk --enable-nonfree
$ make -j9
$ sudo make install
```
## mpv
### Install ALSA
```
$ sudo apt-get install libasound2-dev
```
### Install mpv
```
$ cd ~/Downloads
$ wget https://github.com/mpv-player/mpv/archive/master.zip
$ unzip master.zip
$ cd mpv-master
```
Replace
the first line `#!/usr/bin/env python`
of
* `bootstrap.py`
* `waf`

with `#!/usr/bin/env python3`

![alt text](https://whs-dot-hk.github.io/ubuntu-htpc/edit_bootstrap_dot_py.png "Edit bootstrap.py")
```
$ ./bootstrap.py
$ ./waf configure -j9
$ ./waf
$ sudo ./waf install
```
## Install SMPlayer
```
$ sudo add-apt-repository ppa:rvm/smplayer
$ sudo apt-get update
$ sudo apt-get install smplayer
```
### Configure SMPlayer
With `--hwdec=nvdec --vo=gpu`

![alt text](https://whs-dot-hk.github.io/ubuntu-htpc/smplayer_preferences.png "SMPlayer Preferences")
## Install MakeMKV
Download
* <http://www.makemkv.com/download/makemkv-bin-1.12.2.tar.gz>
* <http://www.makemkv.com/download/makemkv-oss-1.12.2.tar.gz>
* <https://whs-dot-hk.github.io/ubuntu-htpc/ffabi.c>

```sh
$ cd ~/Downloads
$ sudo apt-get install build-essential pkg-config libc6-dev libssl-dev libexpat1-dev libavcodec-dev libgl1-mesa-dev libqt4-dev zlib1g-dev
$ tar -xzvf makemkv-bin-1.12.2.tar.gz
$ tar -xzvf makemkv-oss-1.12.2.tar.gz
$ cp ffabi.c makemkv-oss-1.12.2/libffabi/src
$ cd makemkv-oss-1.12.2
$ ./configure
$ make -j9
$ sudo make install
$ cd ../makemkv-bin-1.12.2
$ make
$ sudo make install
```
## Reboot
```
$ sudo reboot
```
