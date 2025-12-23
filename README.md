# Lucy Wagner - Portfolio
GIS Portfolio for Lucy Wagner - Undergraduate Student at the University of St Andrews studying Spatial Science and Public Health 

## Project Example 1: Mapping Malaria Risk Around Lake Tana

Colab Notebook: https://colab.research.google.com/drive/1H-II9G0JsvZPSl-2-qUX_emLtHjPNE9J#scrollTo=YQnLO-EH8Wms

PDF Version: [230002756_MalariaRisk_FinalPDF.pdf](https://github.com/user-attachments/files/24314802/230002756_MalariaRisk_FinalPDF.pdf)

This section of the repository contains the link to code my spatial Multi-Criteria Evaluation (MCE) of malaria risk around Lake Tana, Ethiopia. The project combines environmental suitability and population exposure to illustrate high-risk zones for malaria prevention measures.

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
