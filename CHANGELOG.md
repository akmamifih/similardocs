# Changelog

All notable changes are documented here.
Format follows keepachangelog.com, versions are semver-ish.

## [0.2.0] - 2026-08-23

### Fixed
- crash on paths containing spaces
- off-by-one in the summary counter

### Changed
- faster directory walking, fewer syscalls

## [0.1.0] - 2026-04-04

### Added
- sentence-transformers when available, tf-idf fallback
