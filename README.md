# Aquaculture Suitability

HOLC Redlining and Bird Diversity Observations in LA County

## Highlights
- Map algebra
- Resampling raster data
- Function creation and testing

## Purpose

The purpose of this project is to create a function which will automate the analysis of a bathymetry raster. The application of this function is to create a workflow process that creates an efficient method of visualizing areas where a variety of marine animals might be cultivated. The output of this project is a  function which creates a map of the area in the west coast EEZ in which aquaculture for organisms are suitable as well as a table.

## Repository Structure

The folder structure for this repository is a data folder, the `aquaculture.qmd` quarto document, a README.md, and a .gitignore. The data folder is placed within the .gitignore, and contains the west coast region shapefiles, US state shapefiles (to create an appropriate basemap), and sea surface temperature raster data. The repository also contains the rendered files of the quarto doc.

## Data Access

The data used in this project was the sea surface temperature data from NPAA, the bathymetry data is from the Gerneral Bathymetric Chart of the Oceans, the Exclusive Exconomic Zones of the US West Coast is from Marineregions.org. Data about the optimal growing conditions for oysters and two-spot octopus was gleaned from SeaLifeBase .

## References

This repository contains materials for the second assignment for the course EDS 223 - Geospatial Analysis & Remote Sensing.

- National Oceanic and Atmospheric Administration. "NOAA Coral Reef Watch 5-km Satellite Sea Surface Temperature Anomaly Product." Accessed Nov. 11, 2024.

- General Bathymetric Chart of the Oceans (GEBCO). "Gridded Bathymetry Data." Accessed Nov. 11, 2024.

- Marine Regions. "Exclusive Economic Zones (EEZ)." Accessed Nov. 11, 2024.

- SeaLifeBase. "Search Species." Accessed Nov. 26, 2024.
