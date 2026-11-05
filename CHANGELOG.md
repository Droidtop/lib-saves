# Changelog

All notable changes to lib-saves. Versions follow [Semantic Versioning](https://semver.org/)
(0.x releases may change anything).

## [0.1.1]

### Changed
- Built on lib-sync v0.1.1 and lib-games v0.1.1 (sync-core 0.1.1: a forgotten device is told it is not paired), so a program
  using this library and lib-sync links one copy of sync-core.

## [0.1.0]

### Added
- `saves-locate`: save locations (the person's entries, Ludusavi's data, engine rules, Wine and Proton prefixes) and kept copies. Moved from droidtop-agent `0ec4110` `crates/saves` unchanged but for its package name (Droidtop/tracker#867 step 1).
