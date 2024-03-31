# Repository ptsbasic-tk

# PTS BASIC 1A

This is the initial version of PTS BASIC available on bitsavers
which is compatable with the emulated PDP-11/70 configuration
used for the PiDP-11/70 kit.

## prerequsites

- Linux host system
- SimH 4.0 installed
- This git repository cloned to a working folder
- The working folder contains a symbolic link "simh" linked to
the SimH application

## make precedure

- Type: ./simh build-ptsbasic-1a.ini
- Type: ./simh link-ptsbasic-1a.ini

## running ptsbasic

- Type: ./simh run-ptsbasic-1a.ini
- Answer "A", for "All", to the question that appears regarding the modules to load
- Answer "0", zero, to the question about number of pad characters

This will start the Paper Tape System BASIC version 1A in the SimH emulation of a minimum configuration
emulated PDP-11/70

# PTS BASIC TK

This section is a work in progress
