# Changelog

All notable changes to this repository will be documented in this file.

## 2026-05-09

### Added

- Added an enhanced contrast toggle for the admin UI with preference detection and persisted user settings. (#16541)
- Promoted `@payloadcms/plugin-import-export` out of beta and added collection-level plus field-level import and export hooks. (#16252)
- Added new v4 documentation videos. (#16555)

### Changed

- Raised the minimum supported Node.js version to `24.15.0` for the `4.0.0-beta.0` line. (#16540)
- Enabled the list view Select API by default. (#16471)
- Refreshed the v4 components view with a loading overlay and clearer category titles. (#16550)

### Fixed

- Corrected the `ui4` skill icon source path. (#16553)

### Removed

- Removed the deprecated `title` and `setDocumentTitle` exports from `DocumentInfoContext` in favor of `DocumentTitleContext`. (#16551)
