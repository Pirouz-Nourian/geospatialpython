# Geospatial Python: Vector and Raster Computing

# [Geospatial Computing course from Carpentries](https://carpentries-incubator.github.io/geospatial-python/)
# [Python GIS Course](https://automating-gis-processes.github.io/2016/Lesson1-Intro-Python-GIS.html)

Installations for VS Code (conda):

Create a conda environment from the yml file:

```conda
conda env create -f geopy.yml
```
This will take quite a while and then after the installation is done, you need to actiate the environment and choose its python as the kernel of the Jupyter notebooks:

```conda
conda activate geospatial
```
These are my notes from a [geospatial computing workshop](https://www.itc.nl/research/research-facilities/labs-resources/itc-big-geodata/training/introduction-to-geospatial-raster-and-vector-data-with-python/) held at ITC by the NLeSC (Netherlands eScience Centre).
Collaborative Notes are on [tinyurl.com/2023-03-30-geospatial-python](https://codimd.carpentries.org/ICtpqPq1S_ud5X_ocOVoHQ)

working with vector data: geopandas
working with raster data: rioxarray, xarray-spatial

If you have a UT account you can also run the codes on [CRIB](https://crib.utwente.nl/)

Getting raster data from [Copernicus Sentinel2](https://scihub.copernicus.eu/dhus/#/home)
API Access will be used in the workshop.
For API Access the [STAC protocol](https://stacspec.org/en) is used.
Using the [STAC Browser](https://radiantearth.github.io/stac-browser/#/external/earth-search.aws.element84.com/v0/collections/sentinel-s2-l2a-cogs/items/S2B_52VDL_20230330_0_L2A?.language=en) is recommended.\

This tutorial is adopted from the [Carpentries Geospatial Python](https://carpentries-incubator.github.io/geospatial-python/)

For a longer course take a look at [PythonGIS](https://pythongis.org/index.html)

For spatial analysis in Python check out [LibPySAL](https://pysal.org/libpysal/)


