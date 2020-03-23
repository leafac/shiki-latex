# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2020-03-22

### Added

- <https://github.com/leafac/shiki-latex/issues/3#issuecomment-601790389>: Load custom themes.
- Debugging with the `SHIKI_LATEX_DEBUG` environment variable. The debug log is written to `shiki-minted-debug.json`.

### Fixed

- <https://github.com/leafac/shiki-latex/issues/3>: Normalize colors, for example, `#D8DEE9FF` turns into `#D8DEE9`, and `#FFF` turns into `#FFFFFF`. This is necessary because the `xcolor` LaTeX package expects colors in this format.

## [1.0.2] - 2020-03-13

### Fixed

- <https://github.com/leafac/shiki-latex/issues/2>: Escaping `}`.

## [1.0.1] - 2020-03-13

### Fixed

- <https://github.com/leafac/shiki-latex/issues/1>: Parsing of parameters to make executable compatible with older versions of minted.

## [1.0.0] - 2020-03-10

### Added

- LaTeX renderer for Shiki.
- Executable compatible with the way minted calls Pygments.

[unreleased]: https://github.com/leafac/shiki-latex/compare/1.1.0...HEAD
[1.1.0]: https://github.com/leafac/shiki-latex/compare/1.0.2...1.1.0
[1.0.2]: https://github.com/leafac/shiki-latex/compare/1.0.0...1.0.2
[1.0.1]: https://github.com/leafac/shiki-latex/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/leafac/shiki-latex/releases/tag/1.0.0