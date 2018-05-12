# Pink Pulsating Pancreas

## Architecture

Most of the work is done on a Raspberry Pi running Pure Data. An Arduino-like
MCU is used to read from the fader bank and output DMX.

## MCU software

The MCU controls DMX lighting fixtures, and will probably handle all
aspects of that, accepting a mode and some basic parameters from Pure
Data. The MCU also reads from the fader bank.

This software was designed to run on a
[dmxfire16](https://github.com/propane-and-electrons/dmxfire16), but should
work on any Arduino-ish (ATmega328) platform.

The [DMXSerial](http://www.mathertel.de/Arduino/DMXSerial.aspx) library
(v1.4.0) is required, and can be installed using the Arduino Library Manager.

## Raspberry PI

The main controls are written in Pure Data. (Version TBD)
