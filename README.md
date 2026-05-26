# Agribud Card

This is the front end card for use with the (Agribud integration)[https://github.com/sauln1/Agribud].

![Version](https://img.shields.io/badge/version-1.1.2-1D9E75)
![Home Assistant](https://img.shields.io/badge/Home%20Assistant-2025.1%2B-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)
[![HACS](https://img.shields.io/badge/HACS-default-orange.svg?style=flat-square)](https://hacs.xyz)

## Installation

### HACS (recommended)

1. Open HACS in your Home Assistant instance.
2. Select the **...** elipsis and enter **Custom Repositories** 'https://github.com/sauln1/agribud-card' as type 'dashboard'.
3. Click **Download**.
4. Refresh your browser.

### Manual

1. Download `agribud-card.js` from the [latest release][releases].
2. Copy it to `<config>/www/agribud-card.js`.
3. Add a resource entry in your dashboard settings:
```yaml
resources:
  - url: /local/agribud-card.js
    type: module
```
4. Refresh your browser.
---

## Configuration

### Minimal example

```yaml
type: custom:boilerplate-card
entity: light.living_room
```


