# IBMF JavaScript Modules

A collection of interactive JavaScript-based modules for the [IBMF Philippines](https://ibmfphils.org/) WordPress website.

## Modules

### Church Finder

An interactive church directory with an OpenStreetMap-powered map for finding IBMF-affiliated churches across the Philippines.

**Features:**
- **Search** – Find churches by name or pastor name with real-time results
- **Filter** – Narrow down by geographic region via dropdown
- **Interactive Map** – Built with [Leaflet.js](https://leafletjs.com/) (free, no API key required)
- **Marker Clustering** – Nearby pins are grouped for a clean map experience
- **Mobile Responsive** – Adaptive layout with List/Map tab switching on smaller screens
- **75+ Churches** – Covers 27 regions across Luzon, Visayas, and Mindanao

**Tech:** Leaflet.js, OpenStreetMap tiles, Leaflet.markercluster, vanilla JavaScript, CSS

## Usage

Each module is a self-contained HTML/CSS/JS file designed to be embedded into WordPress pages via Elementor (using the Custom Code / HTML widget).

## Project Structure

```
ibmf-javascript-modules/
├── church-finder.html      # Church Finder module
├── backup/
│   └── church-finder-bk.html
└── Find a Church.pdf
```
