# Calculadora de Reticula Editorial v4 - educational web app 2026

> **Build and preview editorial grids in a single web page, with format, typography, and InDesign equivalency controls introduced in version 4.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v4-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/victortaylor70/calculadora-reticula-web-v4?style=flat-square)](https://github.com/victortaylor70/calculadora-reticula-web-v4)

---

<p align="center">
  <a href="https://victortaylor70.github.io/calculadora-reticula-web-v4/">
    <img src="https://img.shields.io/badge/Download-Calculadora%20de%20Reticula%20Editorial%20Latest-brightgreen?style=for-the-badge" alt="Download Calculadora de Reticula Editorial">
  </a>
</p>

> **[Download - Calculadora de Reticula Editorial v4](https://victortaylor70.github.io/calculadora-reticula-web-v4/)**

---

[Download Latest Build](https://victortaylor70.github.io/calculadora-reticula-web-v4/)

---

## What Calculadora de Reticula Editorial Does

Calculadora de Reticula Editorial is a browser tool that lets you construct and examine editorial grids as you work. Everything runs on one page, so you can watch page structure, spacing, and type relationships respond instantly to your input instead of switching between separate tools.

Its focus is practical and pedagogical: it supports learning and early planning around paper formats, margins, column counts, gutter widths, and baseline rhythm. Alongside the grid itself, the app provides typographic conversion references between PostScript/DTP and Didot, which makes it a useful study aid for editorial design coursework and for comparing grids against InDesign-style conventions.

---

## Highlights

- Grid calculations and visual feedback update live as values change
- Paper size presets, with manual entry for custom page dimensions
- Dedicated controls for margins, columns, and gutters
- Canvas layers you can switch on or off to inspect individual layout elements
- Typographic conversion between PostScript/DTP and Didot units
- Teaching-oriented notes on editorial composition
- Single-page web interface, ready to open in a browser
- InDesign equivalency references for layout-focused study

---

## Getting Started

Because this is a web application, no build step is required to run it.

1. Clone or download the repository:
   - `git clone https://github.com/victortaylor70/calculadora-reticula-web-v4.git
2. Enter the project directory.
3. Open the HTML entry file in your browser, or host the folder with a static server if you prefer a cleaner local setup.

Sample command for a local static server:

- `python -m http.server 8000`

Visit `http://localhost:8000` to load the app.

---

## How to Use It

1. Pick a paper preset, or type in your own page dimensions.
2. Set margins, column count, and gutters according to the layout you want to explore.
3. Watch the grid redraw immediately whenever a value changes.
4. Show or hide canvas layers to isolate particular structural parts of the grid.
5. Use the typographic conversion tools to compare measurement systems while planning text grids.
6. Carry the resulting values into editorial exercises, mockups, or layout planning work.

---

## Configuration Notes

Nearly all settings live in the on-screen controls. This is a browser-based single-page app, so you normally adjust configuration through the interface itself rather than in external files.

If you modify the project locally, keep the main HTML, CSS, and script assets in their existing structure so the app continues to load properly.

---

## Requirements

- A current web browser
- JavaScript turned on
- A screen large enough to view the grid comfortably
- Optionally, a local static server for development or offline testing

---

## FAQ

### How do I update the app?
Swap your local files for the newest repository version and reload the page in your browser.

### Is any extra software needed?
No, not for regular use. A browser suffices, though a local web server can make local testing easier.

### Where do I change layout values?
Every primary value is adjusted from the app interface, including page format, margins, columns, and related grid settings.

### What should I check if the page fails to load?
Make sure the files were copied together, look for errors in the browser console, and try serving the project from a local static server.

### Does the app handle typographic conversion?
Yes. Conversion references between PostScript/DTP and Didot are built into the layout workflow.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
