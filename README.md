Psynesthesia
============

A Neat little script that converts sound to color, originally thought of to show what music means to deaf counterparts, in a way understandable to them.


Dependencies:
=============

Numpy
Pyaudio
Pygame
Wavtorgb


Current problems:
=================

For some reason, only certain WAV types are readable. currently i have been using audio-recorder to record sounds and save them into a WAV format.

Audio-recorder is easily attained by executing the following commands on a debian flavored distro:

$ sudo apt-add-repository ppa:osmoma/audio-recorder

$ sudo apt-get update

$ sudo apt-get install audio-recorder


TODO:
=====
Add the ability to convert sound to color via other means than just a recorded WAV file (i.e, Live audio from your microphone)

Take off Debugging prints (too lazy to at the moment)
