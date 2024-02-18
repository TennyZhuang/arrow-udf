# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.3] - 2024-02-18

### Fixed

- Fix the bug that the `#[function]` macro does not support more than 12 arguments.

## [0.1.2] - 2024-01-31

### Added

- Support type alias `numeric` and `jsonb` in `#[function]`.
- Support `varchar[]` and `bytea[]` as arguments.

## [0.1.1] - 2024-01-17

### Fixed

- Fixed returning a list in a struct. e.g. `-> struct<a:int[]>` is now supported.
- However, the trade-off is that the performance of returning a list might decrease.

## [0.1.0] - 2024-01-13

### Added

- Initial release. Support basic scalar functions and table functions.
