# Changelog

## 0.0.2 - 2026-04-01
- Fixed patch application failing when target files have diverged from the branch base by using `--3way` merge strategy
- Added verbose output during patch application
- Added detailed error reporting on failure: shows merge base, lists failing files, and suggests resolution

## 0.0.1 - 2025-05-16
- Initial release
