# Brands

Source brand assets (logos, wordmarks, lockups) for the Open Home Foundation and its projects. For usage guidelines, see the [brand guidelines site](https://brands.openhomefoundation.io).

## Copyright notice
This logo is trademarked and the property of the Open Home Foundation. This means it is not available for commercial use without express written permission from the foundation. We regard commercial use as anything designed to market or promote a product, software or service that is for sale. Please contact partner@openhomefoundation.org for further information.

## Brands

| Brand | Directory |
|---|---|
| Open Home Foundation | `open-home-foundation/` |
| Home Assistant | `home-assistant/` |
| Music Assistant | `music-assistant/` |
| ESPHome | `esphome/` |

## Structure

Each brand directory contains three asset variants, each with SVG and PNG formats:

```
{brand}/
├── logomark/
│   ├── svg/
│   └── png/
├── wordmark/
│   ├── svg/
│   └── png/
└── lockup/
    ├── svg/
    └── png/
```

## Naming Convention

All files follow: `{variant}-{theme}.{ext}`

- **Variants**: `logomark`, `wordmark`, `lockup`
- **Themes**: `color` (full color), `white` (reversed for dark backgrounds), `black` (monochrome)

Examples:
- `open-home-foundation/logomark/svg/logomark-color.svg`
- `home-assistant/lockup/png/lockup-white.png`
- `music-assistant/wordmark/svg/wordmark-black.svg`

## Adding a New Brand

1. Create a directory using the brand's kebab-case name (e.g., `my-project/`).
2. Add the `logomark/`, `wordmark/`, and `lockup/` subdirectories, each with `svg/` and `png/` folders.
3. Name files as `{variant}-{theme}.{ext}`.
4. Update the brands table in this README.
