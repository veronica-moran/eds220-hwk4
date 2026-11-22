# Task 2: Visualizing fire scars through false color

# About
This notebook uses Landsat 8 satellite imagery and fire perimeter data to visualize the Palisades and Eaton fire scars. These fires occured in Los Angeles County in January 2025. False Color imagery is used to highlight burned areas against surrounding vegetation.

# Repository Structure
```
eds220-hwk4/
├── README.md
├── .gitignore
├── hwk4-task2-false-color-Moran.ipynb
└── data/                         # Ignored by Git
    ├── fire_perimeters.geojson
    └── landsat8-2025-02-23-palisades-eaton.nc
```

# Data

Simplified collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmospherically corrected surface reflectance data, collected by the Landsat 8 satellite. Retrieved from the [Microsoft Planetary Computer data catalog](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2) and clipped to an area surrounding the fire perimeters, the data was accessed as landsat8-2025-02-23-palisades-eaton.nc from the course shared data [Google Drive](https://drive.google.com/drive/u/1/folders/1USqhiMLyN8GE05B8WJmHabviJGnmAsLP).

The second dataset contains fire perimeters for the Eaton and Palisades fires. The data was retrieved from the [AVIRIS Data Portal](https://popo.jpl.nasa.gov/mmgis-aviris/?mission=LA_Fires). Most recent fire perimeter was from January 12, 2025. The data was accessed November 15, 2026.

# References

[1] Microsoft Planetary Computer. Landsat Collection 2 Level-2. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

[2] NASA Jet Propulsion Laboratory. AVIRIS data portal: LA fires. Retrieved November 15, 2026. https://popo.jpl.nasa.gov/mmgis-aviris/?mission=LA_Fires

[3] Riebeek, H. (2014, March 14). Why is that forest red and that cloud blue? How to interpret a false-color satellite image. NASA Earth Observatory. https://science.nasa.gov/earth/earth-observatory/how-to-interpret-a-false-color-satellite-image/

[4] Galaz García, C. EDS 220: Working with Environmental Datasets. Master of Environmental Data Science, Bren School of Environmental Science & Management, UC Santa Barbara. Accessed November 15, 2026. https://meds-eds-220.github.io/MEDS-eds-220-course/