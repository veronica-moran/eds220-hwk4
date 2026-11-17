# Task 2: Visualizing fire scars through false color

# About
This notebook uses Landsat 8 satellite imagery and fire perimeter data to visualize the Palisades and Eaton fire scars. These fires occured in Los Angeles County in January 2025. False Color imagery is used to highlight burned areas against surrounding vegetation.

# Repository Structure

eds220-hwk4
│--  README.md
│--  hwk4-task2-false-color-Moran.ipynb
│--  .gitignore

# Data

Simplified collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmospherically corrected surface reflectance data, collected by the Landsat 8 satellite.

The data was retrieved from the [Microsoft Planetary Computer data catalog](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2) and clipped to an area surrounding the fire perimeters. This data should be used for visualization and educational purposes only and can be accessed as landsat8-2025-02-23-palisades-eaton.nc in the course shared data [Google Drive](https://drive.google.com/drive/u/1/folders/1USqhiMLyN8GE05B8WJmHabviJGnmAsLP).

The second dataset contains fire perimeters for the Eaton and Palisades fires. The data was retrieved from the [AVIRIS Data Portal](https://popo.jpl.nasa.gov/mmgis-aviris/?mission=LA_Fires). Most recent fire perimeter was from January 12, 2025. The data was accessed November 15, 2026.

# References

U.S. Geological Survey. Landsat Collection 2 Level-2 [Data set]. Microsoft Planetary Computer. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

NASA Jet Propulsion Laboratory. AVIRIS Data Portal: LA Fires [Data portal]. https://popo.jpl.nasa.gov/mmgis-aviris/?mission=LA_Fires