# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.1] - 2026-11-04

### Changed

- `applog.configure` log path now follows the standard pattern.
- `requirements.txt` now also lists `playwright`.

### Removed

- Stale `tests/test_log_setup.py`, which imported the deleted `log_setup` module and could not run.

## [0.1.0] - 2026-11-04

### Added
- Changelog for version tracking

### Changed
- Custom log_setup replaced with applog-0.2.0
