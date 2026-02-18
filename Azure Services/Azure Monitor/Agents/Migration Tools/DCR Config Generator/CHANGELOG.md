# Changelog

All notable changes to the script will be documented in this file.

## [1.0.2] - 2026-02-17

### Fixed
- Fixed `InvalidAuthenticationToken` error caused by Az.Accounts >= 5.0.0 (Az >= 14.0.0) breaking change where `Get-AzAccessToken` returns a `SecureString` instead of a plain string. Added `Get-AzAccessTokenPlainText` helper that handles both old and new Az module versions.

### Changed
- Updated the Data Collection Endpoint (DCE) API version from `2022-06-01` to `2023-03-11`.

## [1.0.1] - 2024-08-01

### Changed
- Now using the latest DCR Api version 2023-03-11.
- Update one of the console messages.

## [1.0.0] - 2023-12-06

### Added
- Initial release of the script with support for Perf counters,syslog, windows event logs, iis logs, log files, extensions data source
