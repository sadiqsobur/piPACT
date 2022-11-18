# piPACT

Hello reader,
This is my code work done for BWSI's independent project, piPACT. All source code used for this investigation will be right here in this repository. Methodogoly and instructions for the recreation of this investigation will also be included, probably. Everything here is primarily done in python, while using YAML for configuration.

Most of my raw data is actually included in this repository for my own convenience.

Purpose?
---
My intent is to test the reliability of BLE (bluetooth low energy) signals within the close ranges that transmissions and infections will mostly be occuring. For close ranges a certain configuration is required. Currently I am collecting data to approximate the relation between RSSI and distance between the two beacons.

Extra info
---
I picked up a minimal install of Raspberry Pi OS for both my machines, and have configured them minimally to run headless as I wanted to run both purely through the command line. A minimal image of Raspberry Pi OS can be found [here.]("https://www.raspberrypi.org/downloads/raspberry-pi-os/") My ssh setup is default and the only other configuration I've done is purely for development(Vim, Git, etc.) and has no impact on the results themselves.

Credits
---
Much of the code and configuration is modified from [this repository](https://github.com/BWSI-piPACT/reference_code) supplied by BWSI piPACT.
