# Changelog

All notable changes to this project are documented here, following
[Keep a Changelog](https://keepachangelog.com) and
[Semantic Versioning](https://semver.org).

## [Unreleased]

### Fixed

- Restored the on-page game-nav (More Games / Source / Feedback / Star). The
  bundler `document.documentElement.replaceWith()`s the DOM on unpack, wiping
  the static `#game-nav`; the self-healing overlay only re-created the version
  badge. It now rebuilds the whole nav (links + badge) after each unpack.

## [0.1.0] - 2026-07-19

### Added

- Initial versioned release of game-n-s-clone.
- In-game version badge sourced from `version.js`.
