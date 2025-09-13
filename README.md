# Catchment & Consumer Segmentation Explorer

An interactive map showing **station catchment areas** for Northern Rail Stations (Harrogate, St Helens, Worksop) combined with **Mosaic consumer segmentation**.

🔗 **Web Map**: [View](https://aseemtrans.github.io/station-segmentation-map)

---

## 📌 About the Project
This project explores how **station catchment areas** (zones from which passengers travel to a station) can be combined with **consumer segmentation** to inform **retail planning and marketing**.

- **Catchment Categories**
  - **Primary** – highest concentration of station users  
  - **Secondary** – moderate passenger flows  
  - **Tertiary** – wider zones with occasional users  

- **Consumer Segmentation (Mosaic)**
  Each LSOA within a catchment is classified into a **dominant consumer segment** such as *Family Basics*, *City Prosperity*, or *Aspiring Homemakers*. These categories provide insights into **shopping behavior, spending power, and lifestyle**.

By linking catchments with Mosaic, we can answer:
- Where do customers come from?  
- Who are they (demographics, lifestyle)?  
- What are their retail preferences?  

---

## 🛠️ Tech Stack
- **Python (GeoPandas, Shapely)** – data cleaning and GeoJSON export  
- **Tippecanoe** – converting GeoJSON → MBTiles vector tiles  
- **PMTiles** – packaging tiles into a single web-friendly archive  
- **MapLibre GL JS** – interactive web map visualization  
- **HTML + CSS + JavaScript** – frontend filters, UI, styling  

---
