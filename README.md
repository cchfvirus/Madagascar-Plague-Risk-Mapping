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

🔧 Technologies

Leaflet.js (v1.9.4): Interactive mapping
georaster-layer-for-leaflet (v3.10.0): Raster layer rendering
Chroma.js (v2.4.2): Color scale generation
Leaflet.draw (v1.0.4): Measurement tools

📝 Citation
[Your citation information here]
📧 Contact
[Your contact information]
