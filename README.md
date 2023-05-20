# Social Topography

Social Topography is a geographic tool that converts values to smooth hills and vallyes,
the tool made it to [news media in Israel](https://www.calcalist.co.il/local/articles/0,7340,L-3680112,00.html):

![Social Topography of socioeconomic index in Haifa](https://shai2u.github.io/social-topography/site/images/image_4.png)
And an article was [published](https://www.sciencedirect.com/science/article/abs/pii/S0743016717310331) based on this tool.

The tool was originally developed by [Meirav Aharon Gutman](https://www.linkedin.com/in/meirav-aharon-gutman-67931679), [Mordechai Schaap](https://www.linkedin.com/in/mordechaischaap/) and Idan Lederman

The code in this repository enables recreating Social Topography model in a 3D geographic raster, that can later on be used as an elevation model in a 3D GIS environment (e.g. QGIS, ArcGIS Pro, or on the web using Cesium or Mapbox)

# How does it work?

The tool has two main components

1. A conversion from values from one source to geographical heights using linear algebra
2. Generating the elevaton file open source geographic libraries

# Other Features

During preperation, the tool will preview
the 3D model using pydeck in a notebook environment

![Social Topography of socioeconomic index in Haifa](https://shai2u.github.io/social-topography/site/images/preview.png)
# Requirements

Geopandas
Pydeck
GDAL Installed on your operating system and that can run in command line
