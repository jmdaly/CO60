# CO60 PCB

The CO60 was developed out of the desire to make available a 60% PCB
that appeals to many people and is readily available. CO60 is a
portmanteau of Community and 60% keyboard.

## Overview

The CO60 aims to meet the following design goals:

* Switches oriented such that the LEDs are South-facing, for
  compatibility with Cherry profile keycaps.

* USB Type-C support in both A to C and C to C configurations.

* QMK support.

* A variety of split spacebar configurations, including split 6.25U
  space and split 7U space.

* ESD protection circuitry, including data line protection and a
  polyfuse on the VCC line.

* Support for per-switch LED backlighting.

* Fits in standard 60% keyboard cases.

## Supported Layouts

The CO60 supports the [the following layouts](http://www.keyboard-layout-editor.com/#/gists/b488496b3a71c8192113c07e298be340).

## Motivation

There are a number of 60% keyboard PCBs available today, so it is important to
be clear about the reasons for developing a new one. This PCB is the only 60%
keyboard PCB that, to the best of the designer's knowledge, satisfies ALL of
the following criteria:

* Support for MX switches oriented such that the LEDs are South
  facing, for compatibility with Cherry profile keycaps.

* Support for split spacebars, in both 6.25U and 7U configurations.

* USB Type-C connection that supports both A to C and C to C
  configurations.

* Open source hardware. This allows anybody to do a production run of the board
  at any point, and doesn't lock the design in with a particular vendor.

* QMK support.

## Obtaining the Files

This repository contains several submodules, which in turn contain
Kicad libraries used in the PCB design. In order to clone the CO60
repository, and all of the library submodules, the following command
must be issued,

```
git clone --recursive https://gitlab.com/jmdaly/CO60.git
```

## Acknowledgements

This PCB design would not have been possible without the help and
previous work of a number of people. In particular, great inspiration
has been derived from the GH60 project, and [ai03's excellent open
source keyboard designs](https://github.com/ai03-2725). This includes
the use of ai03's KiCad [switch footprint
libraries](https://github.com/ai03-2725/MX_Alps_Hybrid.pretty) and his
[USB Type-C](https://github.com/ai03-2725/Type-C.pretty) KiCad
footprint libraries.

The board outline libraries were created by amtra5, and full credit
goes to him for their design.

There is an active keyboard design community on the /r/mk discord. The
users there have been very helpful, and I've learned a significant
amount about PCB design from them.
