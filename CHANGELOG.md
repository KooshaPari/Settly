# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2026-03-25

### Added
- Initial project scaffold
- Hexagonal architecture structure
- Domain layer with Config, Layer, Source, Validator
- Application layer with ConfigBuilder
- Adapters: FileSource, EnvSource, CliSource
- Format adapters: TomlFormat, YamlFormat, JsonFormat
- Layer priority system
- Merge strategies (Override, Underride, DeepMerge)
- Validation system (RequiredKeys, TypeValidator, RangeValidator)
- Tests
- CI/CD workflow
- STANDARDS.md with 78 xDD methodologies

### Planned
- Hot reload support
- Secret management integration
- Remote configuration support
- Configuration versioning
