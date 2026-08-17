# Change Log

All notable changes to the **UMP Theme** extension are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.6] - 2026-08-17

### Added

- Bilingual `README`: complete English and Portuguese sections, so the Marketplace page reads natively for both audiences. Includes screenshots of both themes running in VS Code.

## [0.0.5] - 2026-08-17

### Changed

- **Ultimate Mega Power Dark** palette lifted 15%: every color had its HSL lightness multiplied by 1.15, hue and saturation untouched, alpha preserved. The canvas stays dark while the code gains brightness, and editor contrast rises from 7.60:1 to 9.45:1.

### Fixed

- **Ultimate Mega Power Dark** is now registered as an actual dark theme (`uiTheme: vs-dark`). It shipped declared as a light theme, so VS Code filled every surface the theme did not define with light defaults, and listed it under the wrong group in the theme picker.
- `repository` and `homepage` pointed at a GitHub repository that no longer exists, leaving both links broken on the Marketplace page.

### Added

- MIT `LICENSE` — the Marketplace listing previously showed no license.
- A real `README` describing both themes, with install and activation instructions.
- Marketplace `keywords` and a `bugs` URL.

## [0.0.4] - 2024-02-14

### Added

- Ultimate Mega Power Dark theme (beta).

## [0.0.3] - 2024-02-10

### Fixed

- Terminal and cursor colors.

## [0.0.2] - 2023-05-22

### Fixed

- Color adjustments across the light theme.

## [0.0.1] - 2023-05-22

### Added

- Initial release: Ultimate Mega Power Light theme.
