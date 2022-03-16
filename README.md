# Turbo SD card adapter for Acorn Electron, BBC Micro and BBC Master

## Hardware

This board builds a Turbo SD card adapter for the Acorn 8 bit machines.
For simplicity it uses an [Adafruit Micro SD Breakout](https://www.adafruit.com/product/254).

To support Turbo mode it needs a single 74HCT125 quad tri state buffer
chip in a SOIC package. However you can leave that off and build it in
non turbo mode by linking pads 2 and 3 together, and pads 8 and 9 together
as this permanently connects CB2 to Data Out on the SD card, and PB0 to
Data In on the SD card. 

## Software

This adapter is compatible with [MMFS](https://github.com/hoglet67/MMFS) by Hoglet.

