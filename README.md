# Lucy Wagner - Portfolio
GIS Portfolio for Lucy Wagner - Undergraduate Student at the University of St Andrews studying Spatial Science and Public Health 

# IRP-Repository
The repository for my final IRP on Malaria in the Lake Tana region of Ethiopia. You can view and run the analysis in Google Colab:

https://colab.research.google.com/drive/1H-II9G0JsvZPSl-2-qUX_emLtHjPNE9J#scrollTo=YQnLO-EH8Wms

# Mapping Malaria Risk Around Lake Tana

This repository contains the link to code my spatial Multi-Criteria Evaluation (MCE) of malaria risk around Lake Tana, Ethiopia. The project combines environmental suitability and population exposure to illustrate high-risk zones for malaria prevention measures.

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
