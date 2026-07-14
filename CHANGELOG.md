# Changelog
All notable user-facing changes to SpinDrive are documented in this file. This mod is compatible with Kerbal Space Program 1.12.5 unless noted otherwise.

## v1.1.0
### Added
- Added `CommunityCategoryKit` support with custom "Spin Drives" category filter.
- Added `VABOrganizer` subcategories for engines and support parts.
- Added custom category icons for CCK integration.
- Added bulkhead profiles to all engine and generator parts (0.3125m, 2.5m, srf).
### Changed
- Reorganized the entire mod into the standard folder structure (Parts, Resources, Patches, and Textures)
- Changed `AstrophageGenerator`'s title and description
- Changed the Astrophage fuel subtype's colors to match what's seen in *Project Hail Mary*.
### Fixed
- Fixed `AstrophageGenerator` VAB rotation alignment.

## v1.0.3
This is SpinDrive's first official GitHub release. Versions 1.0.0-.2 (below) were previously distributed on SpaceDock only; they're recorded here so the mod has one continuous history, going forward.
### Fixed
- Removed a duplicate, packaged `FarFutureTechnologies.dll` that may conflict with any existing FFT installs.
### Added
- Added an astrophage CryoTanks fuel switch patch: `@SUBTYPE[LH2/O]` now can target CryoTanks-native tanks without false-positives on FFT/BlueShift/any other non-`[LF/Ox]` tanks.
- Added `primaryColor` and `secondaryColor` hex fields as well as an `EnrAst` resource bar abbreviation so astrophage now shows up as a red/maroon resource and is abbreviated properly in resource menus.

## v1.0.2
### Fixed
- Fixed a plume naming/compatibility issue so the spin drive cluster uses the intended Waterfall plume again, included a patch to avoid breaking existing craft.

## v1.0.1
### Changed
- Rebalanced the cost of the spin drives and their fuel for career mode.

## v1.0.0
- Initial release.