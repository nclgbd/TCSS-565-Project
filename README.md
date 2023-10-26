# Trajectory classification using Spatial Databases

## Overview

The basic idea of this project is to classify trajectories using spatial databases. The project is divided into two parts: the first one is the classification of trajectories and the second one is to create an application to visualize the results in some way. An example of the backend workflow can be found [in this notebook](./Workflow_Demo.ipynb)

- [Taxi Trajectory Data](https://www.kaggle.com/datasets/crailtap/taxi-trajectory/data) - real world data used as trajectory data
- [geopy](https://geopy.readthedocs.io/en/latest/#) - Python library to locate the coordinates of addresses, cities, countries, and landmarks across the globe using third-party geocoders and other data sources
- [geopandas](https://geopandas.org/en/stable/index.html) - Python library to work with geospatial data and functions similar to [`pandas`](https://pandas.pydata.org/). Geometric operations are performed by [shapely](https://shapely.readthedocs.io/en/stable/manual.html)

### Getting started

- Create anaconda environment by running `conda env create -f conda.yml`. Be sure to use the resulting environment when running the code.
