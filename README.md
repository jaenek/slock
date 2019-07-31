# slock
simple screen locker utility for X.


## Requirements
In order to build slock you need the Xlib header files.


## Installation
Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):
```
make clean install
```

## Running slock
Simply invoke the 'slock' command. To get out of it, enter your password.

## Patches
This source was modified and contains support for pywal colors.
Which should be located in `/home/jaenek/.cache/wal/colors-wal-slock.h`
