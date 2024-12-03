# OptimizingPSPS

## Accessing and Storing Necessary Data
The data files should be given by our mentor phi through the sempra link and accessed in the data folder. The data for src_wings_meteorology_windspeed_snapshot_2023_08_02, src_wings_meteorology_station_summary_snapshot_2023_08_02, and gis_weatherstation_shape_2024_10_04 are read in through pd.excel in our notebook and the dev_wings_agg_span_2024_01_01 and src_vri_snapshot_2024_03_20 datsets are read in as csv.

## Software Dependencies
Our dependencies are located in the docker image here https://github.com/users/wkam3/packages/container/package/q1-project-image and the system dependencies and python packages are listed below:
  - gcc
  - g++
  - libproj-dev
  - proj-data
  - proj-bin
  - libgeos-dev
  - gdal-bin
  - libgdal-dev
  - htop
- pandas (version 2.2.3)
- networkx (version 3.2.1)
- geopandas (version 1.0.1)
- shapely (version 2.0.6)
- folium (version 0.18.0)
- matplotlib (version 3.9.2)
- seaborn (version 0.13.2)
- numpy (version 1.24.4)
- branca (version 0.8.0)

## Commands needed to run
  - pull our notebook down and store the data in the same folder as our notebook, don't put data files in a data folder
  - pull the docker image for our project using: docker pull ghcr.io/wkam3/q1-project-image:latest
  - run the docker container: docker run -p 8888:8888 -v "$(pwd):/home/jovyan/work" ghcr.io/wkam3/q1-project-image:latest
  - Access where you downloaded our jupyter notebook along with the required data and press run all cells
  
