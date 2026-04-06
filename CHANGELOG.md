# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.6.0] - 2025-12-18

### Added
- Multi-day query support with date range selector UI

## [0.5.0] - 2025-12-12

### Changed
- Redesigned web UI with dark theme and metric-row pattern
- Updated README with screenshots and mise tasks

## [0.4.0] - 2025-12-11

### Added
- Forks chart in web UI dashboard
- Askama templates for HTML rendering
- Network and disk charts
- Procfs forks probe for process creation monitoring
- Network probe for interface monitoring

## [0.3.0] - 2025-12-10

### Added
- Alpine APKBUILD package configurations
- Improved sysinfo probes with additional metrics

### Changed
- Renamed project from Helioscope to Ferrview

## [0.2.0] - 2025-12-09

### Added
- Web UI with SVG charts and UTC date formatting
- Collector HTTP server with health endpoint and request limits
- Unit tests

### Changed
- Restructured collector with separate UI and HTTP modules

## [0.1.0] - 2025-12-07

### Added
- Initial release
- Workspace with ferrview-collector, ferrview-node, and ferrview-common
- System probes: CPU, memory, temperature, disk
- SQLite storage with daily rotation
- HTTP client with retry logic in node agent

[0.6.0]: https://github.com/vectorian-rs/ferrview/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/vectorian-rs/ferrview/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/vectorian-rs/ferrview/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/vectorian-rs/ferrview/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/vectorian-rs/ferrview/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/vectorian-rs/ferrview/releases/tag/v0.1.0
