# 🇺🇸 United States Historical Development Simulation

**An interactive map dashboard simulating the development of the United States from the 13 colonies to the modern day (1776–2025).**

Built by **H Heuristics** — professional-grade historical cartographic simulation with 10-year increments, state formation tracking, city founding visualization, territorial expansion overlays, and economic indicators.

---

## Features

- **Interactive Map** — Leaflet.js-powered map with dark cartographic tiles, color-coded state polygons by admission era, and city markers that appear as they were founded
- **Timeline Engine** — 10-year increment slider (1770–2025) with draggable scrubber, play/pause animation (4 speeds), step controls, and keyboard shortcuts
- **State Formation** — All 50 states appear on the map in their year of admission, color-coded by historical era (Colonial, Early Expansion, Antebellum, Civil War, Gilded Age, Progressive, Cold War, Modern)
- **City Founding** — 41 major US cities with founding dates, coordinates, and significance — markers appear on the map as the timeline advances
- **Territorial Acquisitions** — Toggle-able overlays showing the Louisiana Purchase, Mexican Cession, Oregon Territory, Alaska Purchase, and more with dashed borders and pulse animation
- **Economic Indicators** — Live population counter, land area, state count, and city count in the header
- **Historical Events** — Contextual sidebar showing notable events (wars, legislation, innovations, social movements) within the current time period
- **Responsive Design** — Works on desktop, tablet, and mobile with adaptive layout

## Data Coverage

| Category | Count |
|----------|-------|
| States | 50 (with admission year, capital, region, acquisition) |
| Cities | 41 (with founding year, coordinates, population, significance) |
| Territorial Acquisitions | 9 (with year, description, geographic bounds) |
| Population Data Points | 28 (1770–2025, decennial census) |
| Historical Events | 48 (categorized by Revolution, Founding, Expansion, War, Industry, Economy, Society, Innovation) |
| Timeline Increments | 26 (1770–2025 in 10-year steps) |

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `→` | Step forward 10 years |
| `←` | Step backward 10 years |
| `Space` | Play / Pause animation |
| `Home` | Jump to 1776 |
| `End` | Jump to 2025 |
| `T` | Toggle territorial overlays |
| `R` | Reset map view |

## Tech Stack

- **Leaflet.js 1.9.4** — Interactive map rendering
- **CARTO Dark Basemap** — Cartographic tile layer
- **TopoJSON Client 3.1** — GeoJSON/TopoJSON conversion
- **Google Fonts** — Playfair Display, IM Fell English, Inter
- **Vanilla JavaScript** — Zero framework dependencies
- **GitHub Pages** — Static hosting deployment

## Era Color Coding

| Color | Era | Years |
|-------|-----|-------|
| `#8b6914` | Original Colonies | 1787–1790 |
| `#a07820` | Early Expansion | 1791–1820 |
| `#b88830` | Antebellum | 1821–1860 |
| `#c04030` | Civil War Era | 1861–1865 |
| `#c89820` | Gilded Age | 1866–1900 |
| `#a08830` | Progressive Era | 1901–1940 |
| `#687890` | WWII & Cold War | 1941–1990 |
| `#40a0c0` | Modern Era | 1991–2025 |

## Deployment

This is a static site designed for **GitHub Pages**. Simply push to the `main` branch and enable GitHub Pages in the repository settings.

```bash
git clone https://github.com/Hunterhghs/USA-historical-development-simulation.git
cd USA-historical-development-simulation
# Open index.html in a browser, or deploy via GitHub Pages
```

## Author

**H Heuristics** — Market research, economic development consulting, and data intelligence.

---

*"The history of America is the history of expansion — from sea to shining sea, from colony to superpower."*
