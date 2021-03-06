# Change Log

All notable changes to *configue* will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

Up to version [0.7.1] project was know has `hapi-configue`.

## [Unreleased][unreleased]

## [0.10.0] - 2016-02-09
### Added
- can now specify default value to `get`

## [0.9.2] - 2016-02-02
### Changed
- updated dependencies

## [0.9.1] - 2016-02-02
### Changed
- whole api was refactored: `configue` is now usable without hapi
- `configue` is now registerable to hapi by extracting a plugin from the
  instance with `configue.plugin()`

## [0.8.2] - 2016-01-08
### Changed
- Updated Examples

## [0.8.1] - 2016-01-08
### Added
- Setup code quality harness with eslint and Code Climate

### Changed
- Improved README

## [0.8.0] - 2016-01-08
### Changed
- Upgrade package name to *Configue*
- Deprecated previous name with

        npm deprecate hapi-configue "<=v0.7.1" "WARNING: This project has been renamed to configue. Install using configue instead."

## [0.7.1] - 2016-01-08
### Added
- Warning for migration to *Configue*

## [0.7.0] - 2015-12-07
### Added
- defaults options

## [0.6.0] - 2015-12-05
### Changed
- hook can now be asynchronous and must be provided with a callback
### Fixed
- default and overrides hooks in option were not accepted by Joi

## [0.5.0] - 2015-12-03
### Added
- enable full customization with `customWorkflow`
## [0.4.0] - 2015-12-03
### Added
- `.npmignore` for lighter package
## [0.3.3] - 2015-12-03
### Added
- support to configure files with a single path, or array of path (as string)

## [0.3.2] - 2015-12-03
### Added
- new tests
### Fixed
- file were overloading each other
- nconf was persisting between creations

## [0.3.1] - 2015-12-02
### Added
- cucumber integration test
### Fixed
- env variable where ignored

## [0.3.0] - 2015-12-02
### Added
- Joi validation of options
- Hook support

## [0.2.0] - 2015-12-02
### Added
- Minimal "Step" definition
- Usage Example
- More detailed documentation (README+jsdoc)

## [0.1.0] - 2015-12-01
- Initial Release

[unreleased]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.10.0...HEAD
[0.10.0]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.9.2...v0.10.0
[0.9.2]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.9.1...v0.9.2
[0.9.1]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.8.2...v0.9.1
[0.8.2]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.8.1...v0.8.2
[0.8.1]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.8.0...v0.8.1
[0.8.0]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.7.1...v0.8.0
[0.7.1]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.7.0...v0.7.1
[0.7.0]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.6.0...v0.7.0
[0.6.0]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.3.3...v0.4.0
[0.3.3]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.3.2...v0.3.3
[0.3.2]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.3.1...v0.3.2
[0.3.1]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/AdrieanKhisbe/hapi-configue/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/AdrieanKhisbe/hapi-configue/compare/e482070....v0.1.0
