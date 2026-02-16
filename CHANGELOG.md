# Changelog

## [Unreleased]

_This release focuses on easier workflow configuration and better execution visibility._

### Changed

- Improve documentation so setup and troubleshooting are easier on first use
  ([`690ca33`](https://github.com/octivi/update-securitytxt-expires/commit/690ca33),
  [`b96e6c0`](https://github.com/octivi/update-securitytxt-expires/commit/b96e6c0),
  [`75f0e43`](https://github.com/octivi/update-securitytxt-expires/commit/75f0e43),
  [`de0fdbc`](https://github.com/octivi/update-securitytxt-expires/commit/de0fdbc))
- Improve internal argument validation for more predictable CLI behavior
  ([`a3499f5`](https://github.com/octivi/update-securitytxt-expires/commit/a3499f5))

### Added

- Add support for space-, comma-, and newline-separated `targets` and
  `exclude_paths`, making YAML inputs easier to format
  ([`d35b319`](https://github.com/octivi/update-securitytxt-expires/commit/d35b319))
- Add `dry_run` mode so you can preview changes before touching files
  ([`9bfce33`](https://github.com/octivi/update-securitytxt-expires/commit/9bfce33))
- Add `verbose` mode and GitHub Actions-native logs/annotations/step summary
  to simplify debugging in CI runs
  ([`9bfce33`](https://github.com/octivi/update-securitytxt-expires/commit/9bfce33))
- Add a dedicated "Why choose this action" section to help evaluate fit quickly
  ([`56be12b`](https://github.com/octivi/update-securitytxt-expires/commit/56be12b))

### Removed

- No user-facing removals.

### Fixed

- Fix issue-reporting link and CLI wording in the docs
  ([`1582d56`](https://github.com/octivi/update-securitytxt-expires/commit/1582d56),
  [`2f63b9f`](https://github.com/octivi/update-securitytxt-expires/commit/2f63b9f))
- Fix minor documentation inconsistencies
  ([`7626b65`](https://github.com/octivi/update-securitytxt-expires/commit/7626b65))

## [1.0.0] - 2026-02-06

_Initial public release of the action._

### Changed

- Align action metadata with GitHub Marketplace requirements
  ([`9bcea9b`](https://github.com/octivi/update-securitytxt-expires/commit/9bcea9b))
- Simplify examples and quick-start docs for faster onboarding
  ([`136339a`](https://github.com/octivi/update-securitytxt-expires/commit/136339a),
  [`11d2351`](https://github.com/octivi/update-securitytxt-expires/commit/11d2351))

### Added

- Add first stable release of the action with updater script, composite-action
  wrapper, test suite, and repository policies
  ([`7b310ee`](https://github.com/octivi/update-securitytxt-expires/commit/7b310ee))

### Removed

- No user-facing removals.

### Fixed

- No user-facing fixes.

<!-- Reference links (recommended) -->

[Unreleased]: https://github.com/octivi/update-securitytxt-expires/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/octivi/update-securitytxt-expires/releases/tag/v1.0.0
