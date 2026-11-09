# SAFA Ltd - Interactive Land Preparation & Farm Dashboard

An interactive Web GIS dashboard built for **SAFA Ltd** to track, audit, and analyze farm land preparation, tractor operations, polygon acreage coverage, and field survey submissions across various counties (Taita Taveta, Kibwezi East, Makueni).

## 🚀 Key Features

- **Interactive Map:** Built with Leaflet.js, displaying farm boundaries (Polygons/MultiPolygons) overlaid on Google Satellite Hybrid and Carto Light basemaps.
- **Dynamic Filtering:** Filter farms dynamically by Farmer Name, County Group, Submission Date, and Field Officer.
- **Automated Summary Breakdown:** Real-time acreage aggregation by tractor driver, cluster total acreage, and unique farmer count.
- **Verification & Audit Modal:** Tooling to export CSV reports for:
  - Polygon Plough Coverage Ratings
  - Ploughed Farmers with NO Tractor Tracks
  - Duplicate Shared Coordinates & Overlapping Polygons (>25%)
  - Unmapped Track Areas

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Mapping & Spatial Data:** Leaflet.js, GeoJSON
- **Basemaps:** Google Maps Tiles, CARTO Basemaps
- **Data Integration:** KoboCollect Survey GeoJSON Outputs

