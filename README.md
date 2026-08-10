# Spring Lake Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Spring Lake municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01407770, Belmar
- PETSS / NOAA station: 8532337
- NAVD88 thresholds: 3.58 ft minor, 4.58 ft moderate, 5.58 ft major
- MLLW thresholds: 5.9 ft minor, 6.9 ft moderate, 7.9 ft major
- MLLW = NAVD88 + 2.32 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Spring Lake Borough boundary at 5-foot resolution.
