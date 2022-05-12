# PiKrellCam

PiKrellCam is an audio/video recording motion detect program with an OSD web
interface that detects motion using the Raspberry Pi camera MMAL motion vectors.

Read about it and install instructions at:
[PiKrellCam webpage](http://billw2.github.io/pikrellcam/pikrellcam.html)

Git download with:
    $ git clone https://github.com/billw2/pikrellcam

As mentionned [here](https://github.com/billw2/pikrellcam/issues/78#issuecomment-973221866), we do have a though to the original author of this software: William (Bill) James Wilson, Jr..

My intend is to get this very clever and efficient software run on Raspberry pi OS BULLSEYE 32 bits.
Note that the sole different file is the install file, everything else has been kept as is.

The Raspberry pi OS moves from, the now obsolete, picamera library to the new, yet unstable, libcamera.
This is not going to provide motion vectors to any software. They are absolutely required to get it work so
do not expect me to help further than this.
