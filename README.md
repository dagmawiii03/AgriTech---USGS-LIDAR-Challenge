# AgriTech---USGS-LIDAR-Challenge

Table of Contents
- [Overview](##overview)
- [Data](##data)
- [Requirements](##requirements)
- [installation](##Installation-guide)
- [Notebooks](##notebooks)
- [scripts](##scripts)

## Overview

AgriTech, is very interested in how water flows through a maize farm field. This knowledge will help us improve our research on new agricultural products being tested on farms.

How much maize a field produces is very spatially variable. Even if the same farming practices, seeds and fertilizer are applied exactly the same by machinery over a field, there can be a very large harvest at one corner and a low harvest at another corner.  We would like to be able to better understand which parts of the farm are likely to produce more or less maize, so that if we try a new fertilizer on part of this farm, we have more confidence that any differences in the maize harvest 9are due mostly to the new fertilizer changes, and not just random effects due to other environmental factors.  

Water is very important for crop growth and health.  We can better predict maize harvest if we better understand how water flows through a field, and which parts are likely to be flooded or too dry. One important ingredient to understanding water flow in a field is by measuring the elevation of the field at many points.

## Data

- The USGS 3D Elevation Program (3DEP) provides access to lidar point cloud data from the 3DEP repository. The adoption of cloud storage and computing by 3DEP allows users to work with massive datasets of lidar point cloud data without having to download them to local machines.
- The point cloud data is freely accessible from AWS in EPT format. Entwine Point Tile (EPT) is a simple and flexible octree-based storage format for point cloud data. The organization of an EPT dataset contains JSON metadata portions as well as binary point data. The JSON file is core metadata required to interpret the contents of an EPT dataset.

## Requirements

- PDAL
- Laspy
- Geopandas

## Installation guide

```
conda create --name mlenv python==3.8.1
conda activate mlenv
```

```
git clone https://github.com/dagmawiii03/AgriTech---USGS-LIDAR-Challenge
cd PythonLidar
pip install -r requirements.txt

```


## Notebooks

```Notebooks``` : various notebooks found

## scripts

```scripts``` : modularized python scripts are found

