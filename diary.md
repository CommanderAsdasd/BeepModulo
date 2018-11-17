# Compile string
## BCplayer
g++ BCPlayer.cpp stringPlayer.cpp -I ./include lib/libsndfile-1.lib lib/portaudio_x86.lib -o myApp

# Variables
textField collects text data

# TODO
Load textField value to BCPlayer