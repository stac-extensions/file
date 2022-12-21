# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

### Changed

### Deprecated

- `file:values` in favor of the [classification extension](https://github.com/stac-extensions/classification/). [#11](https://github.com/stac-extensions/file/pull/11)

### Removed

### Fixed

## [v2.1.0]

### Added

- `file:local_path` to indicate a relative local path for the asset file. [[PR#7]](https://github.com/stac-extensions/file/pull/7#)
- Support for STAC Catalogs and link objects. [#9](https://github.com/stac-extensions/file/pull/9)

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

[Unreleased]: <https://github.com/stac-extensions/file/compare/v2.1.0...HEAD>
[v2.1.0]: <https://github.com/stac-extensions/file/tree/v2.1.0>
[v2.0.0]: <https://github.com/stac-extensions/file/tree/v2.0.0>
[v1.0.0]: <https://github.com/stac-extensions/file/tree/v1.0.0>
