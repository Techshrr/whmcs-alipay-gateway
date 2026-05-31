# Changelog

All notable changes to this project are documented in this file.

This project follows Semantic Versioning where practical.

## [1.1.5] - 2026-06-01

### Fixed

- Applied successful Alipay callbacks to WHMCS invoices with the confirmed gateway payment amount.
- Reduced reliance on WHMCS balance defaults when recording validated payments.
- Placed the GitHub shortcut in the visible gateway settings help row and replaced icon-font markup with inline SVG.

### Added

- Added Hong Kong Traditional Chinese client-area payment messages when the WHMCS language is detected as `zh-hk` or an equivalent Traditional Chinese locale.
- Added a WHMCS gateway-configuration GitHub shortcut and browser-side update notice for published GitHub releases or tags.

## [1.1.4] - 2026-05-26

### Added

- Added a visible admin language setting for WHMCS payment gateway configuration pages.
- Kept inline Chinese and English switch links as optional configuration-page help text.

## [1.1.3] - 2026-05-26

### Changed

- Flattened the GitHub repository layout so gateway files are visible at the repository root.

## [1.1.2] - 2026-05-26

### Added

- Added a sectioned WHMCS gateway configuration UI.
- Added a saved Chinese and English admin language selector for gateway configuration labels.

## [1.1.0] - 2026-05-26

### Added

- Added signed return handling for browser returns after successful payment.

### Fixed

- Improved UTF-8 handling for Alipay display text.

## [1.0.0] - 2026-05-26

### Added

- Initial release.
- Added Alipay PC website payment, RSA2 signing, notification verification, WHMCS invoice callback handling, CNY amount verification, and bilingual customer-facing messages.
