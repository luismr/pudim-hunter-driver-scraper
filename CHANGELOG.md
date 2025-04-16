# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.2] - 2024-03-19

### Added
- Support for both synchronous and asynchronous operations in PlaywrightScraper
- Improved error handling and browser management
- Additional test cases for sync/async operations
- GitHub Actions workflow updates for browser testing

### Changed
- Updated README.md to match parent project structure
- Enhanced documentation with detailed examples
- Improved test structure with GitHub profile scraping tests

### Fixed
- Browser installation and management in CI/CD pipeline
- Synchronous context manager implementation
- Resource cleanup in both sync and async modes

## [0.0.1] - 2024-03-19

### Added
- Initial release of pudim-hunter-driver-scraper
- Base PlaywrightScraper implementation with browser automation
- Base ScraperJobDriver implementation extending pudim-hunter-driver
- Support for headless and headed browser modes
- Automatic browser installation and management
- Comprehensive test suite with sync and async tests
- GitHub Actions workflow for CI/CD
- Project documentation and examples
- MIT License

### Dependencies
- pudim-hunter-driver>=0.0.2
- playwright>=1.41.0
- pydantic>=2.0.0
- pytest>=7.4.0
- pytest-asyncio>=0.21.0
- pytest-cov>=4.1.0

[Unreleased]: https://github.com/luismr/pudim-hunter-driver-scraper/compare/v0.0.2...HEAD
[0.0.2]: https://github.com/luismr/pudim-hunter-driver-scraper/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/luismr/pudim-hunter-driver-scraper/releases/tag/v0.0.1 