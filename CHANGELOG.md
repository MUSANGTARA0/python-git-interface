# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.4.1] - 2021-10-28
### Fixed
- Fix bug with getting branch names

## [0.4.0] - 2021-10-24
### Added
- Cloning support (without authentication)

## [0.3.1] - 2021-10-21
### Fixed
- Fixed #1 `get_branches()` not showing full branch names

## [0.3.0] - 2021-10-17
### Added
- Project changelog
- Branch creation
- Branch copy
- Branch rename
- Branch deletion
- Ls-tree functionality
- Symbolic-ref functionality

### Changed
- Add `NoBranchesException` to `get_branches()`

### Fixed
- Add missing `__all__` methods

## [0.2.0] - 2021-10-04
### Added
- Document Code
- Get/Set repo description
- Run maintenance
- Create archives

### Changed
- Use GitException for init_repo

## [0.1.0] - 2021-10-03
### Added
- Get branches
- Log viewing
- Init repo

[0.4.1]: https://github.com/enchant97/python-git-interface/compare/v0.4.0...v0.4.1
[0.4.0]: https://github.com/enchant97/python-git-interface/compare/v0.3.1...v0.4.0
[0.3.1]: https://github.com/enchant97/python-git-interface/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/enchant97/python-git-interface/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/enchant97/python-git-interface/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/enchant97/python-git-interface/releases/tag/v0.1.0
