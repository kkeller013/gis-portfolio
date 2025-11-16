# 🌲 Forest Change Monitoring Using Landsat Time Series

## 🗺️ Forest Change Overview
This project applies multi-temporal Landsat imagery to detect forest loss, disturbance, and recovery. By integrating NDVI change, land-cover classification, and raster differencing, the workflow identifies where canopy health has declined or improved over time.

Impact: Produces a clear, spatially explicit picture of long-term forest change to support environmental monitoring and decision making.
---

## 📌 Objective  
Identify distinct vineyard management zones in the Calistoga American Viticultural Area (Napa Valley).
Integrate NDVI, soil clay percentage, slope, and aspect into a unified spatial model.
Provide actionable insights to improve irrigation efficiency, canopy management, and drainage planning.

## 🧰 Tools  
GIS / Remote Sensing: ArcGIS Pro · Landsat 5/7/8
Analysis: NDVI · Raster Calculator · Band differencing · Change detection · Supervised classification
Skills: Geoprocessing · Image interpretation · Spatial analysis

## 🧭 Workflow Summary  
Prepared and clipped Landsat imagery for multiple time periods.
Calculated NDVI for each year to measure vegetation condition.
Created false-color composites to visualize forest structure.
Ran supervised classification to map land-cover classes.
Performed NDVI differencing (Year B – Year A) to detect vegetation loss.
Mapped forest loss, gain, and disturbance zones.

## 📊 Key Results  

NDVI Change
- Identifies areas with major vegetation decline
- Reveals stable vs. disturbed canopy patterns

Land-Cover Classification
- Distinguishes forest vs. non-forest
- Supports interpretation of NDVI-based change

Forest Loss / Gain
- Quantifies forest disturbance between time periods
- Highlights spatial clusters of canopy loss     |

## 💡 Insights & Recommendations  
- NDVI differencing reliably highlights vegetation stress and canopy thinning.
- Classification adds context, helping interpret what land-use type is changing.
- Combining NDVI + classification provides a robust assessment of forest dynamics.
- Results inform future monitoring, conservation, and land-management decisions.
---
