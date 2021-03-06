# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [4.0.0] - 2020-03-24
### Added
 - Multilanguage support

### Changed
 - Separated content from configuration
 - New functions to modify config and content. Configurations and Contents cannot be modified directly now.
 - IconURL in Nuget package is replaced with Icon as IconURL is now deprecated.

## [3.0.0] - 2019-07-23
### Changed
 - Caution notice is now in a separate function
 - Moved texts, styles, etc... to configuration
 - Eslint rules to include amd as environment
 - Fixed some eslint errors

## [2.0.0] - 2019-06-06
### Added
 - Published to npm.
 - Published to Nuget
 - Added logo to status icons
 - Added credits

## Changed
 - Module export is now UMD
 - Changed status icon styles
 - Updates to reflect new repo name in GitHub

## [1.2.0] - 2019-05-20
### Added
 - Eslint specification
 - CI/CD via Azure Pipelines

### Changed
 - Minor changes to suit eslint specs
 - Converted comments into jsdoc

## [1.1.1] - 2019-05-14
### Changed
 - Line breaks in warning message

## [1.1.0] - 2019-05-14
### Added
 - Added new website url
 - Added some documentation in the sxw.js file

### Changed
 - Now using strinct mode
 - The lib is now encapsulated within a function
 

## [1.0.0] - 2019-05-10
### Added
 - Added XSS warning to window
 - New configurations and options

### Changed
 - Added format to console texts
 - Added more information to console texts

### Removed
 - Auto calling of warning function

## [0.0.1] - 2019-05-10
### Added
 - New Changelog
 - Basic console warning
