# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.2] - 2025-08-17

## Quality Improvements

- **Massive coverage boost**: From 43% to 87% total coverage
- **PresetManager**: 89% coverage with comprehensive CRUD tests
- **StatsManager**: 79% coverage including chart generation and export
- **CLI Commands**: Full test coverage for all new commands
- **Error handling**: Test edge cases and validation scenarios

## Files Added

- `tests/test_presets.py` - Complete PresetManager test suite
- `tests/test_stats_advanced.py` - Advanced StatsManager functionality  
- `tests/test_breath_commands.py` - New CLI command tests

## [1.1.0] - 2025-08-06

### Added

- Enhanced statistics with beautiful ASCII charts
- Export functionality for JSON and CSV formats
- Longest streak tracking in stats display
- Detailed stats view with `--detailed` flag

## [1.0.0] - 2025-08-05

### Added

- Custom breathing pattern management
- Statistics tracking with streak monitoring
- Pattern creation, modification, and deletion
- Complete CRUD operations for custom patterns

## [0.1.0] - 2025-08-01

### Added

- Initial release with basic breathing exercises
- Built-in patterns (4-7-8, Box breathing)
- Visual progress bars with colors
