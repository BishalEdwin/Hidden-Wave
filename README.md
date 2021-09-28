# HiddenWave
Embedding secret messages in wave audio file

What is HiddenWave
Hiddenwave is a python based program for simple audio steganography. You can hide your secret text messages in wave audio file. you can play this audio in any media player and secretly share your private message with any one.

Requirements
This tool require python3

Installation
git clone https://github.com/BishalEdwin/Hidden-Wave.git
cd HiddenWave
Usage
Hiddenwave have two python scripts.

HiddenWave.py : for hide secret information.
ExWave.py : for extract secret information for wave audio file.
Hide Secret Information in Audio file
python3 HiddenWave.py -f Demo.wav -m "Secret Msg" -o output.wav
Extract Secret Information from Audio file
python3 ExWave.py -f output.wav
Video Demo

