# TMP117 Breakout
## Introduction
The TMP117 from Texas Instruments is a precision temperature sensor that has a stated accurace that rivals Platinum RTDs. It senses temperature though an internal diode-connected PNP BJT, digitizes it using an internal ADC and communicates with an external controller through I2C. An accuracy of +/-0.1C is claimed over a -55C to +145C temperature range. 
## Project Motivation
I wanted to be able to use the TMP117 for various projects without separately laying out a circuit on each PCB. This breakout board makes it easy to use with regular 2.54mm pitch pin headers. It can also be placed directly on a PCB through the castellations.
## Usage
The board is populated and connected to an external controller through the breakout pins/castellations. The TMP117 uses a 16-bit two's complement format. 
## List of Files
- Hardware: Schematic and PCB KiCAD files, GERBER files
- Software: Example code using Raspberry Pi Pico (PIO and hardware I2C)
- Resources: 
## Application Examples
## Notes
## Links
- Datasheet: https://www.ti.com/lit/ds/symlink/tmp117.pdf
