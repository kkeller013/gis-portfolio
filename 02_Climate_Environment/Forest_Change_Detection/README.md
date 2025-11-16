🌲 Forest Change Monitoring Using Landsat Time Series
🗺️ Forest Change Overview

Forest disturbance and vegetation change detected from multi-year Landsat NDVI and land-cover classification.

📌 Executive Summary

This project analyzes forest disturbance, loss, and recovery using multi-temporal Landsat imagery. By comparing NDVI and classified land cover across different years, the analysis identifies where vegetation has degraded, remained stable, or recovered.
The workflow produces clear, map-driven insight into long-term ecosystem change.

Impact: Enables rapid, spatially explicit assessment of deforestation, disturbance hotspots, and canopy recovery.

🧰 Tools & Skills

GIS/Remote Sensing: ArcGIS Pro · Landsat 5/7/8
Analysis: NDVI · False-color composites · Supervised classification · Change detection
GIS Skills: Geoprocessing · Raster Calculator · Symbology · Spatial statistics

🧭 Workflow Summary

Prepared and clipped multi-year Landsat imagery.

Computed NDVI for each time period to assess vegetation health.

Created false-color composites to highlight forest structure.

Ran supervised classification to map land-cover types.

Performed NDVI differencing to detect forest disturbance.

Mapped forest loss, gain, and recovery zones.

📊 Key Results

(Maps added as they are completed)

NDVI Change

Areas of major vegetation decline detected

Clear separation between disturbed and stable canopy

Land-Cover Classification

Forest vs. non-forest mapped with supervised classification

Classification supports NDVI-based disturbance detection

Forest Loss / Gain

Quantified forest loss between Year A and Year B

Disturbance hotspots clearly visible

💡 Insights & Recommendations

NDVI differencing reliably identifies vegetation disturbance zones.

Supervised classification provides land-use context behind detected changes.

Combining NDVI + classification yields a robust picture of forest dynamics.

Results highlight where future monitoring or conservation actions may be needed.

📁 Supporting Files

Maps: NDVI, land cover, forest loss/gain (/maps/)

Data: Landsat imagery (raw + processed, optional)

Scripts: Any Python/Arcade expressions or analysis notes you export

[⬅️ Back to Portfolio Home](../../README.md)
