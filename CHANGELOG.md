# Changelog

This file documents all the notable changes for each version of Patternbot includes.
Patternbot includes adheres to [Semantic Versioning](http://semver.org/).

---

## [Unreleased]

### Changed

- Made the logged error messages use `console.error()` for better clarity.

---

## [1.2.0] — 2018-03-21

### Added

- Bind all the JavaScript files from the `common` folder & patterns into `<script>` tags on the page after all the patterns have been added.

---

## [1.1.1] — 2018-03-19

### Fixed

- Fix a typo in one of the error messages.

---

## [1.1.0] — 2018-03-10

### Added

- Add `href`/`src`/`url` path correction to change from `../../` to just `../`

### Changed

- Small code fixes, adding missing semi-colons, removing extra `break`, etc.

### Fixed

- Fixed a bug in Blink browsers related to them not rendering SVGs loaded with DOMParser properly.

---

## [1.0.0] — 2018-02-18

### Added

- The initial version of the Patternbot includes system for including patterns into page templates.
