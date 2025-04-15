# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog], and this project adheres to [Semantic Versioning].

## [1.1.0] (2025-04-14)

### Added

- Imports JetBrains Mono directly from Google Fonts rather than relying on a locally installed version. This improves ligatures and makes letter spacing more consistent.
- Adds text rendering optimizations for better font display and ligature rendering.
- Adds explicit support for programming ligatures with expanded font-feature settings.

### Changed

- Standardizes the use of ligatures across code formatting.
- Changes the font weight for spans to be more consistent.
- Decreases font weight and letter spacing for module names.
- Expands the previous Arguments/Returns formatting to all H6 headers.
- Changes definitions, names, and parameters to use monospace font at slightly smaller size with reduced letter spacing.
- Changes decorators to use slightly smaller font, match the name color, and reduce their bottom margin slightly.
- Changes all annotation formatting to match return annotation formatting.
- Refines default value styling with lighter font weight.

### Removed

- Removes custom `line-height` from root `pdoc` element, instead using browser defaults.
- Removes redundant `font-feature-settings` from multiple elements (consolidated in `code`/`pre` elements).
- Removes specific styling for `function::after` pseudo-elements.
- Removes custom formatting for unordered lists.

## [1.0.0] (2025-04-13)

Initial release.

<!-- Links -->
[Keep a Changelog]: https://keepachangelog.com/en/1.1.0/
[Semantic Versioning]: https://semver.org/spec/v2.0.0.html

<!-- Versions -->
[1.1.0]: https://github.com/dannystewart/pdoc-tokyo-night/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/dannystewart/pdoc-tokyo-night/releases/tag/v1.0.0
