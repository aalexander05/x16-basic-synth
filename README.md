# X16 Basic Synth
![image](https://github.com/aalexander05/x16-basic-synth/assets/29714952/ea8b3065-8d16-42ac-90ed-5da1e0a97f5d)


# Overview
This is a terribly simple BASIC application that lets you play notes with your keyboard. It's designed to be used with the Commander X16 computer.
This is the first applicaiton I wrote in BASIC and the first program I ever wrote to run on an 8-bit computer. 

It doesn't work very well as a musical instrument since it can only play one note at a time, but creating it helped me learn a lot about BASIC, and helped me hear all the sounds that `FMPLAY` command can make on the Commander X16 system.
It's not very responsive, since it lags between each note, so you'll have to be forgiving with it.

The SYNTH.PRG can load the tokenized version of the program onto the Commander X16 computer with the `LOAD` command. 

### Development Setup Instructions

The source is intended to be utilized with the [BASLOAD](https://github.com/stefan-b-jakobsson/basload) utility. Follow the readme guide and from that repo and load the SYNTH.BAS file into it to properly tokenize and run the file.
