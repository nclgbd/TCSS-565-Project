# Trajectory classification using Spatial Databases

## Overview

The basic idea of this project is to classify trajectories using spatial databases. The project is divided into two parts: the first one is the classification of trajectories and the second one is to create an application to visualize the results in some way. An example of the backend workflow can be found [in this notebook](./Final_Project.ipynb), **and this notebook acts as the main demo for project submission, and a walkthrough of this demo can be found [at this link](https://drive.google.com/file/d/1NV73Xj69ZMidnnBh2M_MzFhpw8Apr2NP/view?usp=sharing)**.

Model training and test results can be found in [this directory](./results/). There are 3 `csv` files. `2023-12-01_02-21-23_experiment1_test_results.csv` are the 5-fold cross validation results for experiment 1, `2023-12-01_02-21-23_experiment1_test_results.csv` are the test results for experiment 1, and `2023-12-01_02-21-23_experiment2_test_results.csv` are the test results for experiment 2.

- [Taxi Trajectory Data](https://www.kaggle.com/datasets/crailtap/taxi-trajectory/data) - real world data used as trajectory data
- [geopy](https://geopy.readthedocs.io/en/latest/#) - Python library to locate the coordinates of addresses, cities, countries, and landmarks across the globe using third-party geocoders and other data sources
- [geopandas](https://geopandas.org/en/stable/index.html) - Python library to work with geospatial data and functions similar to [`pandas`](https://pandas.pydata.org/). Geometric operations are performed by [shapely](https://shapely.readthedocs.io/en/stable/manual.html)

### Getting started

- Create anaconda environment by running `conda env create -f conda.yml`. Be sure to use the resulting environment when running the code.
