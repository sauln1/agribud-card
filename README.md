# Boilerplate Card

A community-driven boilerplate of best practices for Home Assistant Lovelace custom cards.

[![GitHub Release][releases-shield]][releases]
[![License][license-shield]](LICENSE.md)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

---

## Overview

This is the front end card for use with the (Agribud integration)[https://github.com/sauln1/Agribud].
---

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


