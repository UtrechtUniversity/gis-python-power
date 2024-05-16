# Power of Python in GIS

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11202763.svg)](https://doi.org/10.5281/zenodo.11202763)

This repository contains material for a short workshop demonstrating the power of Python for GIS and Geosciences. The workshop makes use of Jupyter Notebooks to perform raster and vector operations, as well as visualization of geospatial data, using Python. 

The main Python libraries used are:

- `xarray`
- `rasterio`
- `geopandas`
- `rioxarray`
- `earthpy`
- `pandas`
- `shapely`
- `fiona`

## Installation

The participants of this workshop are typically provided with a notebook environment so they don't need to install anything.

- Install Python 3.10 and Jupyter ([installation instructions](https://utrechtuniversity.github.io/workshop-introduction-to-python/installation-and-setup.html)). 
- [Clone the GitHub repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
- Install the required Python packages automatically using `conda env create -f environment.yml`. This assumes you have conda installed (e.g. by following the installation instructions above). Run this command by opening a terminal (e.g. Anaconda prompt on Windows) and first navigating to the cloned repository on your PC (previous step).

## Repository materials

- The workshop materials can be found in the  <a href="https://github.com/UtrechtUniversity/gis-python-power/tree/main/workshop-materials">**wokshop-materials folder**</a>. It contains the jupyter notebooks as well as the data used for the workshop.
- The folder <a href="https://github.com/UtrechtUniversity/gis-python-power/tree/main/playbooks">**playbooks**</a> is exclusively dedicated for automated transfer of the course materials to the digital workspaces on SURF Research Cloud.
- The `environment.yml` file describes the packages that are required to run the notebooks. The file is used to create a python kernel on SURF Research Cloud that has all the packages installed.
- The `.github` folder contains a GitHub Actions workflow that will automatically update the zipped `workshop-materials.zip` whenever there are changes to the `workshop-materials` folder.

## Contact

[Geo Data Team](https://geo-data-support.sites.uu.nl/)
