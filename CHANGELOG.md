# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.10.0] - 2024-11-08

### Added

- Update otel dependencies to latest
- Add example for configuration with Dash0
- Add OpenTelemetry CICD Pipeline Attributes
- Add labels from a PR to the trace span

## [1.9.1] - 2024-05-09

### Fixed

- Split headers only on the first `=` character

### Changed

- Update dependencies
- Update dev dependencies

## [1.9.0] - 2024-05-04

### Added

- Support for `https` endpoints (proto over http).
- Update to node 20.x

[unreleased]: https://github.com/corentinmusard/otel-cicd-action/compare/v1.10.0...HEAD
[1.10.0]: https://github.com/corentinmusard/otel-cicd-action/compare/v1.9.1...v1.10.0
[1.9.1]: https://github.com/corentinmusard/otel-cicd-action/compare/v1.9.0...v1.9.1
[1.9.0]: https://github.com/corentinmusard/otel-cicd-action/releases/tag/v1.9.0

Versions previous to 1.9.0 were developed in another repository. To see previous changelog entries see the [CHANGELOG.md](https://github.com/inception-health/otel-export-trace-action/blob/v1.8.0/CHANGELOG.md).
