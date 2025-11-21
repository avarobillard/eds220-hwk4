# Observing the Palisades and Eaton Fire scars using false color imagery

### About
This repository contains a notebook `hwk4-task2-false-color-ROBILLARD.ipynb` containing a workflow to create a map showing a shortwave infrared/near-infrared/red false color image using Landsat remote sensing data along with fire perimeter polygons to highlight the locations of the Palisades Fire and Eaton Fire in Los Angeles County, California that occurred in early January 2025.


![Photos from the Palisades Fire that started in the City of Los Angeles, January 2025.](images/fire.jpg)
Photos from the Palisades Fire that started in the City of Los Angeles, January 2025.

### Analysis highlights
- Geospatial data exploration and wrangling with `geopandas`
- NetCDF data exploration and wrangling with `xarray` and `rioxarray`
- Creation of true color and false color images using Landsat bands
- Mapping of vector and raster data and customization with `matplotlib`

### Repository structure

This repository consists of a README, a notebook `hwk4-task2-false-color-ROBILLARD.ipynb` containing the analysis, a .gitignore file which includes the data folder, and an images folder which contains the image used in the README as well as the final map. 

### Data

The data for this analysis is not housed in this repository. It was downloaded into a data folder which was added to the .gitignore from the City of Los Angeles and Microsoft Planetary Computer. 

### References

CAL FIRE Official. (2025, January 8). Palisades Fire [Photograph]. Wikimedia Commons. Accessed November 20, 2025, from https://commons.wikimedia.org/wiki/File:Palisades_Fire_%2854254705864%29.jpg

City of Los Angeles. (2025). Palisades and Eaton Dissolved Fire Perimeters (2025) [GIS shapefiles]. Los Angeles GeoHub. Accessed November 20, 2025, from https://geohub.lacity.org/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about

Microsoft Planetary Computer. (n.d.). Landsat Collection 2 Level‑2 [Dataset]. Microsoft. Accessed November 20, 2025, from https://planetarycomputer.microsoft.com/dataset/landsat‑c2‑l2