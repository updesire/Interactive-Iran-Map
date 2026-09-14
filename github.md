repo: mrunderline/iran-geojson
branch: master
path: iran_topo.json

## Last sync
date: 2026-09-14T19:49:35Z

### Updated in this project
- Copied `iran_topo.json` (TopoJSON of Iran's provinces) to build the interactive province map in `Interactive 3D Banner.dc.html`
- Converted client-side via topojson-client + d3-geo (Mercator projection) into SVG province paths
- Read `DavidHDev/react-bits` SoftAurora shader source and ported its GLSL (vertex + fragment) to a vanilla WebGL background (blue-only palette), replacing the old three.js particle field

## Screen map
| Screen | Source files |
| --- | --- |
| Interactive Iran map (province click/hover cards) | iran_topo.json |
| Aurora background | DavidHDev/react-bits: src/content/Backgrounds/SoftAurora/SoftAurora.jsx (shader ported, not copied as-is) |
