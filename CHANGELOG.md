# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
- Nothing yet.

## [0.2.0] - 2022-10-28
### Added
- Added documentation to [docs.rs](https://docs.rs/json_keyquotes_convert).
- Added more tests to improve the coverage.
- Use Rust modules to divide the functionality.
- Made the core functions public.
- Applied the Builder Pattern for `JsonKeyQuoteConverter` (usage of this is now recommended over calling the core functions).

### Changed
- Greatly improved the README of the crate.
- Lots of improvements and bugfixes for the core functions.
- Improved the release pipeline to only push a new version to Crates.io when it is newer than the current published version.

## [0.1.1] - 2022-09-26
### Changed
- Increased the version number.

## [0.1.0] - 2022-09-26
### Added
- Added the `json_convert_without_to_with_keyquotes` function to convert a file from JSON without keyquotes to JSON with keyquotes.
- Added the `json_convert_with_to_without_keyquotes` function to convert a file from JSON with keyquotes to JSON without keyquotes.