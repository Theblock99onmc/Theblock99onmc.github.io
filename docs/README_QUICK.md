# Math & Reken Hub - Quick Start Guide

## What is it?
A web-based learning platform for Dutch students (VMBO, HAVO, VWO) to practice math skills through interactive games and tools.

## Main Features

### 🎮 Games
- **Kubus Fusie**: Strategy game - buy, drop, and merge cubes for coins
- **RekenSnelheid**: Speed challenge - solve math problems against the clock
- **Math Peeler**: Algebra - peel complex formulas layer by layer

### 📚 Tools
- **Formules & Tabellen**: Interactive formula explorer with graphs
- **Breuken & Percentages**: Visual fraction-to-decimal-to-percentage converter
- **Statistiek**: Data analyzer - calculate mean, median, mode, and visualize histograms

## Quick Setup

1. Open `index.html` in a browser
2. Select a module from the hub
3. Choose difficulty level (1-3) or Infinite Mode
4. Play!

## Configuration

Edit `config.json` to show/hide modules:
```json
{
  "modules": {
    "rekensnelheid": { "enabled": false },
    "peeler": { "enabled": false },
    "kubus": { "enabled": true },
    "formules": { "enabled": true },
    "breuken": { "enabled": true },
    "statistiek": { "enabled": true }
  }
}
```

## Accessibility Features
- 🌙 Dark/Light/OLED themes
- 📝 Font options: Inter, Lexend, OpenDyslexic
- ♿ Full keyboard navigation
- 🌍 Dutch/English language support

## File Structure
- `index.html` - Main application
- `config.json` - Module configuration
- `docs/` - Documentation

---

For detailed documentation, see [DOCUMENTATION.md](./DOCUMENTATION.md)
