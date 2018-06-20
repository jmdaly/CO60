# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased]

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

[Unreleased]: https://github.com/jmdaly/CO60/compare/Rev.3...HEAD
[Rev. 3]: https://github.com/jmdaly/CO60/compare/Rev.2...Rev.3
[Rev. 2]: https://github.com/jmdaly/CO60/compare/Rev.1...Rev.2
