# SALMON Output Viewer

Single-file HTML app for visualizing SALMON output files locally.

## Features

- Plot SALMON time-series and frequency-domain `.data` outputs
- Load cube sequences from a selected directory
- Render cube data with atoms, cell box, and isosurfaces
- Compare two graph datasets side by side
- Toggle displayed graph series from the legend
- Record cube playback as WebM when the browser supports it

## Usage

Open `salmon_output_viewer.html` in a web browser.

Typical workflow:

1. Use `Select Files (.data)` for standard SALMON output tables
2. Use `Select Cube Directory` for cube-frame directories
3. Pick datasets from the left panel
4. Adjust `Iso Value` and `Opacity` for cube rendering

## Notes

- This repository is client-side only. No backend is required.
- `3Dmol.js` is vendored locally under `vendor/3Dmol-min.js`.
- `Select Files (.data)` and `Select Cube Directory` are intentionally separate routes.
