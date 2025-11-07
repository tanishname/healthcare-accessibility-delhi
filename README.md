# healthcare accessibility analysis — delhi nct

a geospatial case study analyzing hospital coverage across delhi using gis spatial techniques, population rasters, and administrative boundaries.

## NOTE
this is a beginner-level project built using publicly available datasets. the findings reflect the analysis performed on this data and may differ from real-world ground conditions. this project is meant to demonstrate gis workflow, analytical thinking, and problem-solving skills — not to be treated as an official assessment.

---

## 🔍 problem
how many people in delhi lack access to a hospital within 5km?

---

## 🧠 key insights
- **97.83%** of delhi's population is within 5km of a hospital  
- **422,440 people** remain underserved  
- 4 major low-access zones identified:
  - **mehrauli** (highest priority)
  - **kanjhawala**
  - **najafgarh**
  - **alipur**
- ~**1 hospital per 39k residents**
- recommendations include 2 new hospitals that could serve **356k+ people**

---

## 🗺️ methodology
- **hospital data:** openstreetmap (quickosm)
- **population raster:** worldpop 2020 (1km)
- **boundary:** gadm delhi nct
- **analysis tools:** qgis, utm reprojection, 5km buffering, zonal statistics, spatial overlay
- **output:** underserved zones, priority ranking, population impact

---

## 🧰 tech stack
gis • qgis • spatial analysis • osm • raster processing • geoprocessing • public health mapping

---

## 📌 results preview
> maps and report attached in the repository.

---

## 🏆 impact
this project demonstrates how gis can drive real infrastructure decisions instead of just “making maps that look cool.”

---

## author
**tanish**  
gis / spatial analyst (learning + building)
