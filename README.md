# piPACT

Hello reader,
This is my code work done for BWSI's independent project, piPACT. All source code used for this investigation will be right here in this repository. Methodogoly and instructions for the recreation of this investigation will also be included, probably. Everything here is primarily done in python, while using YAML for configuration.
A link to my final written report will be included within this README at some point in the future.

Most of my raw data is actually included in this repository for my own convenience.

Purpose?
---
My intent is to test the reliability of BLE (bluetooth low energy) signals admist the obstructions commonly within a typical household or workplace environment like walls, and wifi signals. Currently I am collecting data to approximate the relation between RSSI and distance between the two beacons. Eventually I will incorporate an algorithm 

What is happening?
---
Essentially, I am using the two supplied Raspberry Pi's to collect data. One will act as a beacon, the other as a scanner. As I do not have access to many testing facilities, I will be using the walls of my own home which are cement. Unfortunate as things can be, I currently have little detail on the composition of these walls but am still able to obtain thickness. For the scope of this project I think this is appropriate enough, as environments will have varied ways to hinder reliability of the signals(or perhaps not). At the very least data should stay consistent as my household conditions are not changing. 

Eventually I plan to 

Extra info
---
I picked up a minimal install of Raspberry Pi OS for both my machines, and have configured them minimally to run headless as I wanted to run both purely through the command line. A minimal image of Raspberry Pi OS can be found [here.]("https://www.raspberrypi.org/downloads/raspberry-pi-os/") My ssh setup is default and the only other configuration I've done is purely for development(Vim, Git, etc.) and has

Credits
---
Much of the code and configuration is modified from [this repository](https://github.com/BWSI-piPACT/reference_code) supplied by BWSI.

More credits will be placed here as I continue the project.
