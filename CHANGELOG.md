# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.1] - 2025-07-04

### Changed
- Updated minimum Obsidian version to 1.0.0 for compatibility with latest Obsidian versions
- Updated TypeScript to v5.3.3
- Updated ESBuild to v0.19.12  
- Updated @typescript-eslint packages to v6.21.0
- Updated @types/node to v20.11.0
- Updated @codemirror/state to v6.4.0
- Added @codemirror/view dependency (v6.23.0)

### Fixed
- Fixed incorrect log message in onunload() method
- Updated version references in README.md

### Added
- Added GitHub Actions CI/CD workflows for automated building and releases
- Added lint scripts to package.json
- Added CHANGELOG.md for version tracking

## [1.1.0] - 2023-07-09

### Added
- Initial release with badge functionality
- Support for various badge types (note, info, todo, etc.)
- GitHub-style badges support
- Custom badge support with icons and colors
- Plain text badges
- Dataview integration

### Features
- Inline badge rendering in Live Preview mode
- Post-processor for Reading mode
- Extensive badge type library with 80+ predefined types
- Custom CSS styling support 