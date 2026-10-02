# Change Log

All notable changes to the "snowcrash" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [0.3.0] - 2026-10-02

### Fixed
- Selection, selection occurrences, find matches, find range, range highlight, bracket match and current line no longer share the same `#101010` color.
- Find matches now use the yellow accent (current match solid border, other matches soft); selection stays neutral gray.
- Find/replace input no longer blends into the find widget (widget `#1a1a1a`, input `#333333`).
- List hover is now distinguishable from list selection.
- Keyboard focus border is now visible (was `#000000`).
- Whitespace and indent guides are visible on the highlighted line.
- Error squiggles at full opacity; `markup.inserted` is now green instead of the function yellow.

### Added
- Word highlight (read/write), overview ruler and minimap colors for find/selection.
- Suggest/hover widget, input option toggles and diff editor colors.

## [Unreleased]

- Initial release
