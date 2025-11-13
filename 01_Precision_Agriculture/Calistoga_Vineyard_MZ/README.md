# 🍇 Precision Viticulture: Data-Driven Management Zones in the Calistoga AVA

**Goal:**  
Create vineyard management zones using NDVI, soil, and terrain data to optimize irrigation, canopy management, and drainage interventions.

---

## 🧰 Tools & Skills  
**GIS & RS:** ArcGIS Pro · Landsat 8 · SRTM DEM  
**Data Science:** R (tidyverse, kmeans, factoextra) · ANOVA  
**Precision Ag:** Spatial variability analysis · Zone delineation  

---

## 🧭 Approach (High-Level)
- Aggregated NDVI, clay %, slope, and aspect into a 200m grid.  
- Scaled data and ran **K-means clustering** in R.  
- Used **Elbow Method → optimal k = 4**.  
- Validated clusters using ANOVA (**p < 0.001**).  
- Mapped zones in ArcGIS Pro and generated management recommendations.

---

## 📊 Key Results (What Matters)
- **4 meaningful zones** identified with distinct vigor and soil/topography patterns.  
- **Highest vigor zone (Cluster 2):** strong NDVI → requires canopy control.  
- **Stress zone (Cluster 3):** flat, clay-heavy → needs drainage improvement.  
- **Slope-driven zones:** higher NDVI on steep slopes → erosion + irrigation optimization needed.  

---

## 💡 Why This Matters
The zone map enables **site-specific management**, reducing costs and improving grape quality by focusing interventions where they matter most.

---

## 📁 Included
- `scripts/` — K-means clustering, ANOVA, data prep in R  
- `maps/` — NDVI map, management zone map  
- `data/` — (optional) sample grid inputs  

[⬅ Back to Portfolio Home](../../README.md)

