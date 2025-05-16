# Vertical Farm Card

This repository contains the frontend Lovelace card for the Vertical Farm Home Assistant integration.

## Features
- Custom Lovelace card for visualizing your vertical farm
- Works with the [Vertical Farm integration](https://github.com/eddie-rowe/vertical-farm)

## Installation (via HACS)
1. Add this repository to HACS as a custom repository (category: Plugin).
2. Install the "Vertical Farm Card" from HACS.
3. In Home Assistant, go to **Settings → Dashboards → Resources** and add:
   - URL: `/hacsfiles/vertical-farm-card.js`
   - Resource type: JavaScript Module
4. Add the card to your dashboard using the following YAML:

```yaml
type: 'custom:vertical-farm-card'
farm_name: 'Main Farm'
```

## Development
- Clone this repo and run `npm install` in the root directory.
- Build the card with `npm run build`.
- The built file will be in the root as `vertical-farm-card.js`.

## Backend Integration
This card is designed to work with the [Vertical Farm integration](https://github.com/eddie-rowe/vertical-farm).

## License
Apache 2.0
