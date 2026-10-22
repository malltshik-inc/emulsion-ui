# Emulsion UI

A minimalist browser-based photo editor with a warm editorial aesthetic and a focused set of darkroom-inspired controls.

Live demo: https://malltshik.github.io/emulsion-ui

## Overview

Emulsion UI is a single-page image editor built with plain HTML, CSS, and JavaScript. It presents a curated library of sample scenes and lets you adjust the look of each image using controls similar to a classic editing suite.

The interface is designed to feel tactile and calm, with a left-hand image library, a tool strip, and a central editing stage.

## Features

- Image library with multiple sample scenes
- White balance and tint adjustments
- Exposure, contrast, highlights, shadows, clarity, and saturation controls
- Vignette and crop controls
- Rotate adjustments
- Compare mode to view before/after changes
- Undo / redo history
- Reset controls and single-image reset flow
- Browser-based editing with no dependency install required

## Tech

- HTML
- CSS
- JavaScript
- SVG-based artwork and previews

## Project structure

- `index.html` — complete app structure, styles, and editor logic
- `README.md` — project overview and usage notes

## Run locally

Because this project is a static web app, you can run it in either of these ways:

### Option 1: Open directly in a browser

Open `index.html` directly in your browser.

### Option 2: Serve locally

From the repository root:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/
```

## Notes

This project is intentionally lightweight and self-contained. It is ideal for experimentation, demoing design ideas, or extending with additional editing tools and export features.

## License

This project does not currently declare a license. If you plan to reuse or distribute it, add an appropriate license before publishing.
