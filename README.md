# Solar PV Infrastructure Corridor Suitability Modeling

A multi-criteria spatial decision workflow developed in **QGIS** to identify unutilized land parcels for decentralized solar installations along active railway corridors.

## Methodology
- **Corridor Generation:** Modeled a 50 m linear infrastructure buffer reprojected to UTM Zone 44N (EPSG:32644) for precise metric operations.
- **Terrain Filtering:** Evaluated 30 m SRTM DEM data to restrict suitability to gentle terrain (Slope $\le 15^\circ$), eliminating site-grading costs and hill-shading risks.
- **Cartography:** Dual-scale map layout featuring regional railway context with inset extent frames.

## Cartographic Deliverable
![Solar PV Corridor Map](solar_pv_corridor_map.png)

## Tools Used
- QGIS 3.x
- SRTM 30m DEM & OpenStreetMap (OSM)
