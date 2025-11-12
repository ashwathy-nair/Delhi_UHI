# Urban Heat Mitigation in Delhi Using Geospatial Analytics

### Overview
This project analyzes the Urban Heat Island effect in Delhi during two different seasons (Summer and Winter) from satellite images, the identification of risk zones and propsal of green-blue infrastructue solutions for heat mitigation.

### Objectives
1) Map and quantify UHI hotspots across Delhi.
2) Examine how vegetation and urban density (population, building and road infrastructure, water bodies, etc) influence surface temperature.
3) Identify suitable sites for green infrastructure such as parks, green roofs, and roadside canopy.

### Data & Methods
**Datasets:** 
Landsat 8 OLI/TIRS (Bands 10, 4, 5) — USGS Earth Explorer  
Population Density — ESRI Living Atlas  
Building Footprints — Delhi Open Data Portal 

**Methods:**  
1. Computed LST from thermal band (B10) for June and February 2024 scenes.  
2. Derived NDVI and NDBI to assess vegetation and built-up intensity.  
3. Combined LST, NDVI, NDBI, and population layers to produce a UHI composite index to identify densily packed urban infrasture where population is the highest and has highest degree of UHI effect.  
4. Located barren and rangelands in dense zones as potential sites for urban greening.

<img width="777" height="709" alt="image" src="https://github.com/user-attachments/assets/b3db381c-8246-4f98-830a-4951db286f3d" />

<img width="1252" height="1027" alt="image" src="https://github.com/user-attachments/assets/2e6db30a-9c84-48cb-b19b-1b21fb0e13fd" />



### Tools
ArcGIS Pro, arcpy

### Key Findings
The Land Surface Temperature is more in the outer agricultural areas of West Delhi rather than the urbanized sectors as they are barren during summers whereas these fields have lower LST during winters.
High NDBI areas (Karol Bagh, CP, Okhla) correspond to stronger UHI effects.
Low NDVI and dense built-up regions exhibit maximum heat retention.
Proposed creation of urban forests and green parks and roadside tree canopies in identified suitable barren lands to mitigate heat stress.

### Author
**Ashwathy Nair**  
GIS Data Scientist | Climate & Environment Analytics  
[ashwathynair41@gmail.com](mailto:ashwathynair41@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/ashwathy-nair-777a16110)
