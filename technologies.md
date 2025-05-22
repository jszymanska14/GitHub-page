---
layout: default
title: Technologies
nav_order: 2
---

# Technologies

We use cutting-edge tools and platforms in our analysis:

- 🌐 **Google Earth Engine**
- 🐍 **Python with GEE Python API**
- 📊 **Geospatial analysis libraries (e.g. geopandas, rasterio)**
- 📡 **Satellite data from Sentinel-2 and Landsat 8**
- 📈 Custom indices and spectral signature analysis

These technologies allow us to process large-scale data and derive reliable insights about monoculture crop dynamics.

We also used already existing Bare Soil Marker (BSM) and NDVI.
We also produced our Bare Soil probablility index based on thresholds:

| NDVI  | BSM        | Bare Soil Probability |
| ----- | ---------- | --------------------------------- |
| > 0.2 | –          | 0 (none)                          |
| ≤ 0.2 | > 0.3      | 0.9 (high)                        |
| ≤ 0.2 | 0.1 – 0.3  | 0.7 (medium)                     |
| ≤ 0.2 | -0.1 – 0.1 | 0.4 (low)                        |
| ≤ 0.2 | ≤ -0.1     | 0.1 (very low)                 |
