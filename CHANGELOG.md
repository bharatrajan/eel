# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).
This `CHANGELOG.md` implements the spirit of http://keepachangelog.com/.

## [1.16](https://github.com/Comcast/eel/compare/v1.15...dev) - [Unreleased]

## [1.15](https://github.com/Comcast/eel/compare/v1.14...v1.15) - 2017-12-01

### Fixed
* Update retry to not retry for 300 and 400

## [1.14](https://github.com/Comcast/eel/compare/v1.13...v1.14) - 2017-11-08

### Fixed
* Fixed bad urls in `CHANGELOG.md`

### Changed
* Commented out array_length_error log to address XRULES-9749

## [1.13](https://github.com/Comcast/eel/compare/v1.12...v1.13) - [2017-09-08]

### Changed
* add tenantId in logs

## [1.12](https://github.com/Comcast/eel/compare/v1.11...v1.12) - [2017-07-28]

### Fixed
* XRULES-8923: erroneous metric on published events

## [1.11](https://github.com/Comcast/eel/compare/v1.10...v1.11) - [2017-06-19]

### Added
* This `CHANGELOG.md` file
* .github/PULL_REQUEST_TEMPLATE.md to improve our PR process

### Fixed
* XRULES-8388: Panic handling code caused the code to panic
