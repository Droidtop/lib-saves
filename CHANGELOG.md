# Changelog

All notable changes to lib-saves. Versions follow [Semantic Versioning](https://semver.org/)
(in 0.x, only a new minor version may break the interface; CI's `semver` job enforces it).

## [0.1.3]

### Added
- CI's `semver` job: `cargo-semver-checks` against the last release, so a breaking change fails unless its version and
  this CHANGELOG say so (Droidtop/tracker#867).

### Changed
- `saves-locate`: built on lib-sync v0.1.2 (cross-store links, Droidtop/tracker#798) and lib-games v0.1.3, so
  droidtop-agent can take lib-sync v0.1.2 and link one sync-core.

## [0.1.2]

### Changed
- Built on lib-sync v0.1.1 and lib-games v0.1.2, as 0.1.1 meant to be. 0.1.1 was released with its pins unchanged (still lib-sync
  v0.1.0), so it is the same as 0.1.0; use 0.1.2.

## [0.1.1]

### Changed
- Built on lib-sync v0.1.1 and lib-games v0.1.1 (sync-core 0.1.1: a forgotten device is told it is not paired), so a program
  using this library and lib-sync links one copy of sync-core.

## [0.1.0]

### Added
- `saves-locate`: save locations (the person's entries, Ludusavi's data, engine rules, Wine and Proton prefixes) and kept copies. Moved from droidtop-agent `0ec4110` `crates/saves` unchanged but for its package name (Droidtop/tracker#867 step 1).
