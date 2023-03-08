# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

<!-- next-header -->
## [Unreleased] - ReleaseDate

### Breaking Change

- `anstyle` upgraded
- `Stream` was renamed to `AutoStream`
- Replaced all uses of various underlying traits with the sealed `RawStream` trait
- `Lockable::locked` now transfers ownership

### Features

- Wincon support
- `Buffer` as an alternative to `stdout` and `stderr`

### Fixes

- Correctly report how much `StripStream` wrote
- Strip operations now strip `DEL` (0x7f)
- `*Stream::into_inner` support
- Enable windows ANSI support when writing to a terminal for `AutoStream::always_ansi`
- Ensure stale data isn't used when unlocking a stream by making it one-way
- Correctly resume state on partial write

## [0.0.1] - 2023-03-07

<!-- next-url -->
[Unreleased]: https://github.com/rust-cli/anstyle/compare/anstyle-stream-v0.0.1...HEAD
[0.0.1]: https://github.com/rust-cli/anstyle/compare/f1a7e73e317f1278be72655f5ce34336ae3d325c...anstyle-stream-v0.0.1