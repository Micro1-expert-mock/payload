# Changelog

All notable changes to this project will be documented in this file.

## 2026-05-09

### Added

- Added an enhanced contrast mode toggle to the admin account settings, including persisted preferences and translation coverage. (#16541)
- Added dynamic Select API support for more flexible option loading in the admin UI. (#16520)
- Moved `@payloadcms/plugin-import-export` out of beta and added collection-level and field-level hooks for CSV and JSON workflows. (#16252)

### Changed

- Enabled Select API support in list views by default. (#16471)
- Updated array and block drag-and-drop interactions to use a drag overlay with clearer visual feedback. (#16513)
- Refreshed Lexical editor icons and the v4 components view to align with the latest UI direction. (#16533, #16550)
- Consolidated `admin.disabled` field configuration behavior. (#16504)
- Raised the minimum supported runtime baselines to Node.js `24.15.0` and Next.js `16.2.6`. (#16540, #16537)
- Updated the `uuid` dependency to `14.0.0`. (#16544)

### Fixed

- Fixed a batch of admin field UI issues affecting relationship, date, tabs, groups, checkboxes, radios, point inputs, and block interactions. (#16493)
- Corrected the UI4 skill icon source path. (#16553)

### Removed

- Removed deprecated `title` and `setDocumentTitle` from `DocumentInfoContext`. (#16551)
- Removed deprecated `min` and `max` options from relationship and upload fields. (#16547)
- Removed the `croner` `sloppyRanges` compatibility setting. (#16546)
