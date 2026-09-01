# AvidTune Assets

<div align="center">

### Official Media & Visual Assets for AvidTune

[![Main Repository](https://img.shields.io/badge/Repository-AvidTune-0D1117?style=flat-square&logo=github&labelColor=161B22)](https://github.com/cgens67/AvidTune)
[![Release](https://img.shields.io/github/v/release/cgens67/AvidTune?style=flat-square&logo=github&color=0D1117&labelColor=161B22)](https://github.com/cgens67/AvidTune/releases)
[![License](https://img.shields.io/github/license/cgens67/AvidTune?style=flat-square&logo=gnu&color=2B3137&labelColor=161B22)](https://github.com/cgens67/AvidTune/blob/main/LICENSE)
[![Telegram Updates](https://img.shields.io/badge/Telegram-Updates-2CA5E0?style=flat-square&logo=telegram&labelColor=161B22)](https://t.me/avidtuneupdates)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Assets Inventory](#assets-inventory)
  - [Release & Changelog Banners](#release--changelog-banners)
  - [Branding & Media](#branding--media)
- [Naming Conventions](#naming-conventions)
- [Usage & Hotlinking](#usage--hotlinking)
- [Contributing Assets](#contributing-assets)
- [License](#license)

---

## Overview

This repository hosts official media assets, promotional artwork, banners, and changelog headers used across the **AvidTune** ecosystem (GitHub releases, Telegram channel, documentation, and website).

> 🔗 **Looking for the app?** Visit the main [AvidTune Repository](https://github.com/cgens67/AvidTune) or the [Official Website](https://avidtune.netlify.app/).

---

## Assets Inventory

### Release & Changelog Banners
Release banners represent major and minor version announcements, changelogs, and update notices:

| File Pattern | Description | Example Target |
| :--- | :--- | :--- |
| `1.0.0.png` | Stable release banner | GitHub Release / Telegram announcement |
| `1.4.0-beta2.png` | Pre-release / Beta banner | Beta release notes & testing channels |
| `X.Y.Z.png` | Version-specific feature graphics | Changelog headers |

---

### Branding & Media

| Asset Type | File Name | Purpose |
| :--- | :--- | :--- |
| **App Icon** | `icon.png` / `logo.png` | High-resolution AvidTune branding |
| **Banner Header** | `banner.png` | Social previews & README headers |
| **Feature Badges** | `promo-*.png` | Feature highlights & documentation assets |

---

## Naming Conventions

To keep assets organized and easily referenceable across scripts and release workflows, please adhere to the standard naming patterns:

- **Stable Releases:** `<semver>.png`  
  *(e.g., `1.0.0.png`, `1.2.0.png`)*
- **Beta / RC Releases:** `<semver>-<tag>.png`  
  *(e.g., `1.4.0-beta1.png`, `1.4.0-beta2.png`, `2.0.0-rc1.png`)*
- **General Graphics:** lowercase with hyphens  
  *(e.g., `hero-banner.png`, `telegram-header.png`)*

### Recommended Format Guidelines
- **Format:** PNG (optimized/lossless) or SVG where applicable
- **Banner Aspect Ratio:** 16:9 or 2:1 recommended for social/Telegram previews
- **Color Profile:** sRGB (aligned with Material Design 3 guidelines)

---

## Usage & Hotlinking

You can hotlink or embed assets directly in Markdown, HTML, or release templates:

### GitHub Direct URL
```markdown
![AvidTune v1.4.0 Beta 2](https://raw.githubusercontent.com/cgens67/assets/main/1.4.0-beta2.png)
```

### Fast CDN (jsDelivr)
```markdown
![AvidTune v1.0.0](https://cdn.jsdelivr.net/gh/cgens67/assets@main/1.0.0.png)
```

---

## Contributing Assets

1. Ensure the image is optimized to maintain small repo sizes (use tools like [TinyPNG](https://tinypng.com/) or `oxipng`).
2. Follow the standard [Naming Conventions](#naming-conventions).
3. Place files directly in the root directory (or designated paths if structured later).
4. Open a pull request or push directly if you have maintainer access.

---

## License

All visual assets and media contained in this repository are distributed under the [GNU General Public License v3.0](https://github.com/cgens67/AvidTune/blob/main/LICENSE) in conjunction with the main **AvidTune** project.

<div align="center">
  <p><strong>© 2026 AvidTune by <a href="https://github.com/cgens67">cgens67</a></strong></p>
  
  [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cgens67)
  [![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/avidtuneupdates)
</div>
