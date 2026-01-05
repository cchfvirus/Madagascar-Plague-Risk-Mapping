# Madagascar Plague Risk Mapping

# Interactive Plague Risk Mapping for Madagascar 🗺️

Plague continues to cause deadly outbreaks in Madagascar, yet health officials lack detailed maps showing where disease risk is highest. This detailed community-level risk assessment enables health authorities to target disease surveillance, prevention efforts, and resources to specific locations where plague is most likely to occur, potentially saving lives through earlier detection and response to outbreaks.

**Explore the interactive map:** https://cchfvirus.github.io/Madagascar-Plague-Risk-Mapping/

## 📊 Map Layers

**Base Layers:**
* **Ecological Niche Model (1km)** - Environmental suitability for plague transmission (Maxent)
* **Risk Zones (100m)** - Integrated transmission risk assessment (Maxent + LandScan Mosaic)
* **Hot Spot Analysis (100m)** - Spatial clustering of plague activity (Getis-Ord Gi*)

**Overlay Layers:**
* **Plague Cases** - Historical case locations with blue medical cross (✚) markers (click for details)
* **High-Risk Regions** - Administrative boundaries for high-risk areas

**Basemaps:**
* Street Map (Esri World Street Map)
* Satellite Imagery (Esri World Imagery)

## 🎯 Interactive Features

**Layer Controls:**
* Toggle between different risk assessment layers
* Switch between street and satellite basemaps
* Show/hide plague cases and high-risk region boundaries
* Adjust layer opacity with real-time sliders (0-100%)

**Measurement Tools:**
* 📏 Distance measurement - Draw polylines to measure distances in kilometers
* 📐 Area measurement - Draw polygons to calculate areas in km²
* Edit and remove measurements as needed

**Navigation & Reference:**
* 🧭 North arrow indicator for orientation
* Right-click anywhere on map to copy coordinates (useful for field work)
* Interactive zoom and pan controls
* Click plague case markers to view detailed case information

**Map Projection:**
* WGS84 (EPSG:4326)
* Cloud Optimized GeoTIFF (COG) format for fast loading

## 📖 Citation

If you use this tool or data, please cite the accompanying publication:
```
[Full Publication Citation Here]
DOI: [Publication DOI]
```
## 📧 Contact

## 📝 License

MIT License

---
