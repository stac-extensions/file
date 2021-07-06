# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- `file:path` to indicate a relative path for the asset file.

### Changed

### Deprecated

### Removed

### Fixed

## [v2.0.0]

### Changed

- Summaries for values must be non-empty

### Removed

- `file:bits_per_sample`: now in `raster:bands.bits_per_sample`
- `file:data_type`: now in `raster:bands.data_type`
- `file:nodata`: now in `raster:bands.nodata`
- `file:unit`: now in `raster:bands.unit`

### Fixed

- JSON Schema checks `stac_extensions` field in Collections

## [v1.0.0]

- Initial release

[Unreleased]: <https://github.com/stac-extensions/template/compare/v2.0.0...HEAD>
[v2.0.0]: <https://github.com/stac-extensions/tree/v2.0.0>
[v1.0.0]: <https://github.com/stac-extensions/tree/v1.0.0>
