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

Interactive Tools

🖱️ Click to inspect: Left-click any location to view raster cell values
📍 Coordinate copying: Right-click to copy coordinates to clipboard
📏 Measurement tools: Draw polylines and polygons to measure distance and area
🎚️ Layer controls: Toggle between layers with customizable opacity (ENM/Risk: 50%, Hotspot: 100% default)
🗺️ Basemap options: Switch between street map and satellite imagery

Data Overlays

Plague Cases: Georeferenced case locations with detailed attribute popups
High-Risk Boundaries: Dynamic boundary display (color-coded by layer)
North Arrow: Fixed directional reference

Technical Specifications

Format: Cloud Optimized GeoTIFF (COG) for efficient streaming
Projection: WGS84 (EPSG:4326)
Color Schemes:

Discrete classification for Risk Zones (7 classes with distinct colors)
Continuous gradients for ENM and Hotspot layers


Resolution: 1km (ENM), 100m (Risk Zones, Hotspot Analysis)
Libraries: Leaflet.js, georaster-layer-for-leaflet, Chroma.js

🚀 Live Demo
View the interactive map
📊 Data Layers
Risk Zone Classification

0: No Risk (Black)
1: Very Low Risk (Light Yellow)
2: Low Risk (Yellow)
3: Moderate Risk (Orange)
4: Elevated Risk (Red-Orange)
6: High Risk (Red)
9: Very High Risk (Dark Red)

Hot Spot Analysis
Statistical significance levels at 90%, 95%, and 99% confidence intervals for both hot spots (positive clustering) and cold spots (negative clustering).
💻 Usage

Clone the repository
Ensure all data files are present: enm_cog.tif, risk_zones_cog.tif, hotspot_cog.tif, cases.geojson, high_risk_boundaries.geojson
Serve via web server (required for CORS): python -m http.server or R servr::httd()
Open in browser

📁 Repository Structure
madagascar-plague-map/
├── index.html              # Main application
├── enm_cog.tif             # Ecological Niche Model raster
├── risk_zones_cog.tif      # Risk classification raster
├── hotspot_cog.tif         # Hot spot analysis raster
├── cases.geojson           # Plague case locations
└── high_risk_boundaries.geojson  # High-risk region boundaries
🔧 Technologies

Leaflet.js (v1.9.4): Interactive mapping
georaster-layer-for-leaflet (v3.10.0): Raster layer rendering
Chroma.js (v2.4.2): Color scale generation
Leaflet.draw (v1.0.4): Measurement tools

📝 Citation
[Your citation information here]
📧 Contact
[Your contact information]
