# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased]

## [Rev. 7] - 2019-01-17

### Changed
- This revision adds 16 RGB LEDs to the bottom of the PCB
  to be used as underglow. Note that, in order to add the RGB
  LEDs, I had to re-route significant portions of the PCB. As
  a result, the matrix layout has changed. Rev. 7 firmware is
  incompatible with Rev. 6 firmware.

## [Rev. 6] - 2018-11-19

### Changed
- This revision of the PCB now uses an STM32F303 microcontroller
  instead of an Atmega 32u4. The layouts remain the same, but
  the firmware for Rev. 6 is incompatible with previous revisions.

## [Rev. 5] - 2018-08-28

### Changed
- USB connector from Amphenol Type C to Korean HRO Type-C.
  I believe this new connector will not conflict with switches
  when they are installed. The legs of the Amphenol connector
  conflicted with the switches.

## [Rev. 4] - 2018-07-22

### Added
- Initial versions of plate files to accompany PCB.

### Changed
- Fix pin assignments on transistor used for LED backlighting.
  Prior to this fix, backlighting did not work at all. This fix
  should resolve that issue.

## [Rev. 3] - 2018-06-20

### Added
- More PCB material under USB connector so that its through hole
  pins are entirely within the board.

- Spreadsheet sent to Elecrow for fabrication and assembly. This
  is the revision of the CO60 that was sent to Elecrow for initial
  fabrication and assembly.

### Changed
- Increase width of one VCC trace that was too thin.

- Move some silk screen component labels around so they are
  more visible.

- Clean up routing for some traces to give more clearance around
  other objects.

- Improve ground plane coverage and ensure the two ground
  planes only connect at a single location.

- Move board origin to lower left corner of board.

- Move D4 and D10 to ensure compatibility with some cases.

- Move R18 in order to clean up some traces nearby.

## [Rev. 2] - 2018-06-04

### Added
- This CHANGELOG file to track changes between revisions.

### Changed
- Move the USB connector farther toward the top of the board. This is
  to prevent any issues with the USB housing overlapping with holes in
  the board.

- Clean up some traces near drill holes.

## Rev. 1 - 2018-05-29

### Added
- Tag to note the first completed revision. This is the version that
  was sent to JLCPCB for initial prototyping.

[Unreleased]: https://github.com/jmdaly/CO60/compare/Rev.7...HEAD
[Rev. 7]: https://github.com/jmdaly/CO60/compare/Rev.6...Rev.7
[Rev. 6]: https://github.com/jmdaly/CO60/compare/Rev.5...Rev.6
[Rev. 5]: https://github.com/jmdaly/CO60/compare/Rev.4...Rev.5
[Rev. 4]: https://github.com/jmdaly/CO60/compare/Rev.3...Rev.4
[Rev. 3]: https://github.com/jmdaly/CO60/compare/Rev.2...Rev.3
[Rev. 2]: https://github.com/jmdaly/CO60/compare/Rev.1...Rev.2
