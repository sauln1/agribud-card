# Agribuddy Card

This is the front end card for use with the [Agribuddy integration](https://github.com/sauln1/Agribuddy).

![Version](https://img.shields.io/badge/version-1.1.3-1D9E75)
![Home Assistant](https://img.shields.io/badge/Home%20Assistant-2025.1%2B-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)
[![HACS](https://img.shields.io/badge/HACS-default-orange.svg?style=flat-square)](https://hacs.xyz)

## Installation

### HACS (recommended)

1. Open HACS in your Home Assistant instance.
2. Select the **...** elipsis and enter **Custom Repositories** 'https://github.com/sauln1/agribuddy-card' as type 'dashboard'.
3. Click **Download**.
4. Refresh your browser.

### Manual

1. Download `agribuddy-card.js` from the [latest release][releases].
2. Copy it to `<config>/www/agribuddy-card.js`.
3. Add a resource entry in your dashboard settings:
```yaml
resources:
  - url: /local/agribuddy-card.js
    type: module
```
4. Refresh your browser.
---

## Configuration

### Minimal example

```yaml
type: custom:agribuddy-card
title: My Garden
temp_unit: auto
```
<img width="1316" height="427" alt="agribuddy-img" src="agribuddy-img.png" />


Documentation for the functionality of this card can be found in the main [Agribuddy integration repository ReadMe.](https://github.com/sauln1/Agribuddy/blob/main/README.md)

