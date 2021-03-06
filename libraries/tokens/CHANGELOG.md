# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.4.0] - 2020-09-02

### Added

#### Color

- Added missing overlay color `pressed_overlay_light`

### Removed

- Removed unused colors in EDS
  - `field__fill_resting`
  - `field__fill_hover`
  - `field__fill_activated`

### Changed

#### Color

- Changed `link_in_snackbars` for better contrast.

## [0.3.0] - 2020-07-15

### Changed

- Font-weight is increased from 400 (regular) to 500 (medium) in all cases where the font-size is below 16px
- Font-size is increased and line-height decreased for label and helper
- Values such as underline, uppercase etc. are now lowercase

### Removed

- tabs.inactive-text is not in use in EDS Core React and has been removed

## [0.2.1] - 2020-07-08

### Changed

- Updated tokens to include text-align even if the value is “left”

## [0.2.0] - 2020-04-30

### Changed

- Updated tokens with latest values from Figma, see the [EDS Figma changelog](https://eds.equinor.com/updates/release-information/changelog/) for more details

## [0.1.0] - 2020-02-24

### Changed

- Updated README to me abit more clearer
- Adjustments to to `package.json` to be more in line with our other packages
- New versioning of packages

## [0.0.1-alpha.7] - 2020-01-22

### Changed

- Better support for using as commonjs or esm modules in different node versions

## [0.0.1-alpha.6] - 2020-01-20

### Added

- Compiled bundle for esm, cjs and umd modules

## [0.0.1-alpha.5] - 2019-12-13

### Changed

- Base tokens are now exported as esm instead of json

## [0.0.1-alpha.4] - 2019-08-04

### Changed

- Update readme with available tokens
- New model on `base` tokens

### Added

- `table` tokens

## [0.0.1-alpha.3] - 2019-07-23

### Changed

- Update missing fields in package.json

## [0.0.1-alpha.2] - 2019-07-23

### Changed

- Update license
- Add CHANGELOG
