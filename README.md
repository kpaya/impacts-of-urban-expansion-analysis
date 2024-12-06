# Urban Expansion and Its Impact on Biodiversity: A Study of BII Changes in Phoenix, Arizona
 
## About
This repository is dedicated to analyze BII data through functions such as biodiversity_function and percent_function, which automate key aspects of the analysis. These functions streamline the process by handling data wrangling and calculating BII and percentage change.

Additionally, visualizations such as color-coded maps have been created to highlight significant BII changes in the region. These maps help identify areas most affected by urbanization.

## Repository Structure
The repository is organized as follows:
 
/data: Contains the raw datasets used in the analysis, including the biodiversity data and boundary shapefiles.
 
README.md: This file provides an overview of the repository and how to use it.

impacts-development-on-BII-analysis.ipynb: Jupyter notebook containing the analysis, including BII calculations, percentage changes, and visualizations.

## Data
The data used in this project comes from: 

1. Microsoft Planetary Computer - Biodiversity Intactness Index (BII): The BII data was sourced from the Microsoft Planetary Computer platform. It provides terrestrial biodiversity intactness estimates based on 100-meter gridded maps for the years 2017-2020.
2. U.S. Census Bureau - TIGER/Line Shapefiles: The legal boundaries of all U.S. cities were obtained from the U.S. Census Bureau’s TIGER/Line shapefiles. This data was used to define the geographic scope of the Phoenix subdivision.
3. OpenStreetMap: OpenStreetMap was used as a base map to provide geographic context for the visualizations.

Data access: The boundary shapefiles can be found in the /data folder of the repository. The BII data can be retrieved programmatically from the Microsoft Planetary Computer Data Catalog using the code included in the impacts-development-on-BII-analysis.ipynb. The OpenStreetMap basemap is added programmatically to the visualizations using the contextily package, the code is included in the same notebook.

## References
Microsoft Planetary Computer. Biodiversity Intactness. 2024. Microsoft. Retrieved December 5, 2024, from https://planetarycomputer.microsoft.com/dataset/io-biodiversity

Census Bureau, TIGER/Line Shapefiles. 2024. Census.Gov. Retrieved December 5, 2024, from https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html

OpenStreetMap contributors. BaseMap. 2024. OpenStreetMap. Retrieved December 5, 2024, from https://www.openstreetmap.org/copyright
 
**This project was created as part of the EDS 220: Environmental Data Science course at UCSB.**
 
