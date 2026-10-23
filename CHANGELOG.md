# Changelog

All notable changes to ConverterPIX Wrapper are documented in this file.

## [2.4] - 2026-10-23

Verified with Blender 5.2.2 LTS and SCS Blender Tools 2.4.

### Changed
- ConverterPIX update thread is now created with `daemon=True`, replacing the deprecated `Thread.setDaemon()` call.
- `unregister()` now removes the File > Import menu entry first and unregisters classes in reverse registration order, so operators are removed before the property groups they reference.

## [2.3]

### Added
- Support for ConverterPIX x64 builds on Windows (64-bit Blender downloads the `win_x64` executable).

## Earlier versions

See the [commit history](https://github.com/simon50keda/ConverterPIXWrapper/commits/master) of the upstream repository.
