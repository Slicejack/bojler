# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [5.0.3] - 2022-08-24
### Added
- Added `.nvmrc` file.

### Changed
- Bumped del from 6.0.0 to 6.1.1.
- Bumped inquirer from 8.2.0 to 8.2.4.
- Bumped juice from 8.0.0 to 8.1.0.
- Bumped sass from 1.45.2 to 1.54.5.
- Updated `package-lock.json` file.

## [5.0.2] - 2022-02-28
### Changed
- Bumped node-fetch from 2.6.6 to 2.6.7.
- Bumped sass from 1.45.2 to 1.49.9.

## [5.0.1] - 2022-01-05
### Changed
- Updated NPM dependencies.

### Fixed
- Fixed SASS slash-div warnings.

## [5.0.0] - 2021-05-28
### Changed
- Updated gulp tasks.
- Updated `juice` to `v8.0.0`.
- Updated `node-sass` to `v5.0.0`.
- Updated buttons to make them fully clickable (#139).

### Fixed
- Fixed all npm security issues.

### Removed
- Dropped support for node 8.x, please install node 10.x or higher.
- Removed utility classes with ":" and "@" prefixes (#132).

## [4.1.6] - 2021-05-27
### Fixed
- Fixed all npm security issues.

## [4.1.5] - 2020-04-10
### Fixed
- Fixed all npm security issues.

## [4.1.4] - 2019-09-25
### Fixed
- Fixed issues with media queries and gmail (#130).

## [4.1.3] - 2019-09-09
### Fixed
- Fixed all npm security issues.

## [4.1.2] - 2019-09-03
### Fixed
- Fixed issues related to Node 12.

## [4.1.1] - 2019-06-21
### Fixed
- Fixed MacOS Node v10.16.0 compatibility issue.
- Fixed issue with content in conditional comments.

## [4.1.0] - 2018-10-12
### Changed
- Updated `README.md` with few content changes.
- Updated `CHANGELOG.md` with minor content change.

### Added
- Gulp task async completion signal added (#114, #116).
- Added `:` responsive flag to utility classes (#115, #117).

## [4.0.0] - 2018-09-04
### Changed
- Updated folder structure.
- Updated boilerplate template.
- Updated buttons component.
- Updated settings.
- Updated `.package-lock.json`.
- Updated gulp tasks.
- Updated `config.js`.
- Updated gutter on first and last columns.
- Renamed `/scss` folder to `/sass`.
- Increased grid container size.

### Fixed
- Fixed some stylint issues.

### Added
- Added boilerplate with hero template.
- Added horizontal spacing variable for mobile devices.

### Removed
- Removed distribution, documentation and test files.
- Removed border utilites.
- Removed VScode snippets.

## [3.2.1] - 2018-01-23
### Changed
- Added `.stylelintrc` and `.eslintrc` to npm package (#101).

## [3.2.0] - 2018-01-22
### Changed
- Grid gutter settings updated (#97).
- Spacing utilites updated (#91, #98, #99).
- `o-main-wrapper` updated (#95).
- Updated gulp files to version 4 (#90).

### Added
- Links styles added (#94).
- `test:watch` task added (#89).
- Added "Basic", "Notification Success", "Notification Danger", "Notification Warning", "Account Reset Password", "Notification Unsubscribed" and "Account Activate" templates (#75, #76, #77, #78, #79, #80, #82).

### Fixed
- Release zip issue fixed (#88).

## [3.1.0] - 2018-01-16
### Changed
- Documentation updated (#71, #85).
- Updated buttons `line-height` for better consistency (#57).
- ITCSS rules applied (#83).
- Updated `docs/` directory structure (#68).

### Added
- Added tests and examples automation (#86).
- Added more utility classes (#74).
- Added VSCode comment snippets (#84).

## [3.0.0] - 2018-01-12
### Changed
- Transformed bojler to CSS only framework (#61, #70).
- Moved documentation from `gh-pages` branch to `docs/` directory on `master` branch (#64).
- Documentation content updated (#63).
- Licence filename updated.

### Added
- Added files needed for NPM package creation (#60).
- Added new automation scripts (#66, #67, #69).
- Added CI via Travis CI service (#62).

## [2.2.0] - 2018-01-09
### Changed
- Allow use of subdirectories (#54).

## [2.1.2] - 2017-08-07
### Fixed
- Inline source issue fixed (#53).

## [2.1.1] - 2017-08-07
### Fixed
- Images path issue (#51).

## [2.1.0] - 2017-08-02
### Added
- Embedded CSS (#41).
- Assets directory (#21).

### Changed
- Updated `package.json` w/ licence and reporsitory fields (#49).
- Responsive images (#45).
- Images vertical alignment updated (#38).
- Updated meta tags (#47).
- Comments updated (#48).

### Fixed
- Disabled shorthands (#44).

### Removed
- Removed `.image-fix` from `_reset.scss` (#40).

## [2.0.5] - 2017-07-26
### Fixed
- Hero component vertical alignment issue (Outlook 2007.) fixed.
- `no-gutter` class issue fixed.

## [2.0.4] - 2017-07-24
### Fixed
- Specified `.first` and `.last` classes styles only to columns.

### Changed
- Updated `$breakpoint-mobile` to `$grid-container-width`.
- Converted space indentations to tabs.

### Added
- Added `font-smoothing` for better typography in web browsers.
- Added images `line-height` fix utility.

### Removed
- Removed tables utility classes.
- Removed spacing utility classes.

## [2.0.3] - 2017-07-18
### Changed
- System fonts selector updated.

### Added
- Outlook system fonts stack fallback implemented.

## [2.0.2] - 2017-07-17
### Fixed
- Gulp stylesheet tags issue.

### Changed
- Buttons text alignment.
- `body-table-spacing` on small screens.

### Added
- Headings utility classes.

## [2.0.1] - 2017-07-11
### Fixed
- No gutter columns issue w/ inlined CSS.

## [2.0.0] - 2017-06-28
ℹ️ We've started versioning project from this version.

### Changed
- Added information about v2.0.0 to README.md.

### Added
- SASS support.
- Automatic CSS inlining.
- Webserver with Live Reload.
- ESlinter config file.
- Change Log.
- Guidelines for contributing.

## ⚠️ Old version [1.0.0]
Old version of Bojler can be found [here](https://github.com/Slicejack/bojler/tree/v1).
