# Code Glue Add-on

Home Assistant add-ons for [Code Glue](https://github.com/Digital-Alchemy-TS/code-glue) - Write Automations and create entities in TypeScript via a built-in IDE.

## Installation

[![Add repository on my Home Assistant][repository-badge]][repository-url]

Add this repository to your Home Assistant instance:

1. Go to **Settings** → **Add-ons** → **Add-on Store**
2. Click the **⋮** menu (top right) → **Repositories**
3. Add this URL:
   ```
   https://github.com/Digital-Alchemy-TS/code-glue-addon
   ```
4. Click **Add** → **Close**

You'll now see two add-ons available:

## Available Add-ons

### Code Glue
**Stable production releases**
- "Thoroughly tested"
- Recommended for production use
- Pulls from `ghcr.io/digital-alchemy-ts/code-glue:latest`

### Code Glue (Dev)
**Development builds for testing**
- Latest features and bug fixes
- May (will) be unstable and/or ugly.
- Pulls from `ghcr.io/digital-alchemy-ts/code-glue:dev`
- Can run alongside production version with its own DB.

## Documentation

Full documentation and source code: https://github.com/Digital-Alchemy-TS/code-glue

## Support

Found a bug or have a feature request?
- Report issues: https://github.com/Digital-Alchemy-TS/code-glue/issues

## Development

This repository contains only the Home Assistant add-on configurations. The actual application source code lives in the main [code-glue repository](https://github.com/Digital-Alchemy-TS/code-glue).

Container images are built and published automatically via GitHub Actions.

[repository-badge]: https://img.shields.io/badge/Add%20repository%20to%20my-Home%20Assistant-41BDF5?logo=home-assistant&style=for-the-badge
[repository-url]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2FDigital-Alchemy-TS%2Fcode-glue-addon