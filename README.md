# Lucy Wagner - Portfolio
GIS Portfolio for Lucy Wagner - Undergraduate Student at the University of St Andrews studying Spatial Science and Public Health 

## Project Example 1: Mapping Malaria Risk Around Lake Tana

Grade: 20/20 by UK Grading Standards

PDF Version: [230002756_MalariaRisk_FinalPDF.pdf](https://github.com/user-attachments/files/24314802/230002756_MalariaRisk_FinalPDF.pdf)

This section of the repository contains the link to view my spatial Multi-Criteria Evaluation (MCE) of malaria risk around Lake Tana, Ethiopia. The project combines environmental suitability and population exposure to illustrate high-risk zones for malaria prevention measures.

## Research Question

How do environmental suitability patterns and population exposure interact to shape malaria risk around Lake Tana, and which areas emerge as priority hotspots for targeted public-health intervention?

## Methods Overview

- Environmental suitability model built from:
  - Temperature (WorldClim)
  - Elevation and slope (SRTM DEM)
  - Distance to water (Lake Tana and surrounding hydrology)
  - Land-cover constraints (Copernicus)
- Population exposure derived from a normalised WorldPop raster.
- Risk Index computed as: **Risk = Environmental Suitability × Exposure**.
- Spatial processing in **QGIS**; validation and plotting in **Python** using `rasterio`, `numpy`, `matplotlib`, and `seaborn`.

## Project Example 2: Multi-Criteria Evaluation of Conflict Zones for Carpet Washing Industries' Suitability around Kathmandu, Nepal

PDF Version:[MCE_Kathmandu_Lucy_Wagner.pdf](https://github.com/user-attachments/files/24314868/MCE_Kathmandu_Lucy_Wagner.pdf)

This section of the repository contains the link to view my introduction to the Multi-Criteria Evaluation Process where I combined a Carpet Washing Facility Suitability map with an Agricultural Suitability map to identify conflict zones for the facilities arounf Kathmandu. I explored how various factors and constraints impact the suitability for these facilities to properly operate. 

## Methods Overview

- Carpet Suitability
  - Used Roads (HDX) shapefile to create a Powerlines raster (assuming that all main powerlines are near major road systems)
  - Used Roads, Rivers (HDX), and Powerlines shapefiles to create distance raster
  - Land Cover Constraints (Copernicus) to exclude unsuitable land types
  - Slope (SRTM DEM) to mask unsuitable elevation

- Agricultural Suitability
  - Used DEM converted to slope and changed weight of water factor to create suitability index for agriculture
 
- Conflict Zones Final
  - "identify conflicting areas that are 90% or more suitable for carpet industry and at the same time 90% or more suitable for agriculture"
  - Used raster calculator to mask 0.9 or more of each suitability map to produce one conflict zone output

 ## Project Example 3: Python for Spatial Analysis 

 This section of the repository contains the links to view my Python processes where I evaluated various Spatial Analysis problems and queries. 

 Geopandas and Rasterio PDF: https://drive.google.com/drive/folders/1vO0w3crNWhTVKaq7gLLun7qP_fbXOXzG?dmr=1&ec=wgc-drive-hero-goto 

 K-Means and DBSCAN PDF: https://drive.google.com/drive/folders/1vO0w3crNWhTVKaq7gLLun7qP_fbXOXzG?dmr=1&ec=wgc-drive-hero-goto

 ## Project Example 4: Palau Water Crisis after Tropical Cyclone Rai

This section of the repository contains the folder for a Humanitarian Disaster Response project in which I used Excel, ArcGIS Pro, and varying information/file databases to construct a semi-fictional assessment of a water crisis in Palau after Tropical Cyclone Rai.

IMPORTANT: Some of the data utilized in this lab was fictional for classwork purposes and does not necessarily reflect true facts and figures of disaster/damage records from Cyclone Rai's duration or response period. Please note this if assessing against existing literature on Palau during this emergency.
 
 Link to zip file containing all deliverables calculated and produced within the project: https://drive.google.com/file/d/1aSK23kzpr2sIYKg5B69WVx7bF4y4RCv-/view?usp=drive_link


## Project Example 5: Introduction to Geospatial Analysis 

This section of the repository contains a zip file to view my introduction to geospatial analysis using data from Scotland. This part of the repository was submitted as an assignment in my second year of univsersity schooling.

[SD2100_Geospatial_Analysis_ASSIGNMENT.docx.zip](https://github.com/user-attachments/files/24416272/SD2100_Geospatial_Analysis_ASSIGNMENT.docx.zip)

