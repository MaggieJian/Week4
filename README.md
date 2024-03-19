# Week 4: Collocation and unsupervised classification

Welcome to Week 4. The purpose of this GitHub page is to share the code for Week 4 of the module named GEOL0069: Artificial Intelligence For Earth Observation (AI4EO) 2023/24. The primary focus is on sea ice and lead classification.

## Description

You will learn how to find lists of colocated images from pairs of collocated satellites: Sentinel-3 (300m resolution) and Sentinel-2 imagery (10m resolution) as well as collocated altimetry data from Sentinel-3. Unsupervised classification will be performed.

Therefore, this project is divided into two sections:
1) Colocating Sentinel-3 OLCI and Sentinal-2 Optical Data
2) Unsupervised Learning

To successfully classify the echoes in leads and sea ice in this project, you will produce:
1) An average echo shape
2) A standard deviation for these two classes
3) A confusion matrix (to quantify echo classification against the ESA official classification)

![image](https://github.com/MaggieJian/Week4/assets/160494175/3adc0b36-a221-4626-abfb-47120b3ff2f4)
![image](https://github.com/MaggieJian/Week4/assets/160494175/68fb30bc-2e67-4cd5-8190-0fad8d1e20d6)
![image](https://github.com/MaggieJian/Week4/assets/160494175/f7f7949d-adf4-4ede-9c33-97b25ab85b77)


## Getting Started

### Dependencies

1) A Google account
2) A good internet connection for using Google Colab
3) SENTINEL and OLCI files (downloaded and unzipped)
4) Libraries: numpy (as np), ee, os, datetime (timedelta and date), sklearn.cluster (KMeans and DBSCAN), matplotlib.pyplot (as plt), pyproj, shapely.geometry, subprocess, requests, pandas (as pd), rasterio, requests, time, cartopy.crs (as ccrs), sklearn.preprocessing (StandardScaler, MinMaxScaler), sklearn.mixture (GaussianMixture), scipy.cluster.hierarchy (linkage, fcluster), shutil, json, joblib (Parallel), zipfile, sys, glob, netCDF4 (Dataset), scipy.interpolate (griddata), numpy.ma (as ma), glob, matplotlib.patches (Polygon), and scipy.spatial (as spatial and as KDTree).

RAM requirements:

### Installing

To access the Google Colab file, click https://github.com/MaggieJian/Week4 or go to the GitHub repository (MaggieJian/Week4).

### How to run the program

* Step-by-step bullets
```
code blocks for commands
```

## Help

Please contact maggie.jian.21@ucl.ac.uk

Check: The paths should lead to the corrrect satellite images in your Google Drive. If not, re-upload your unzipped satellite images to your Google Drive or change the path.
```
command to run if program contains helper info
```

## Author

Name: Maggie Jian

Contact: maggie.jian.21@ucl.ac.uk


## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is not licensed

## Acknowledgments

Inspiration, code snippets, etc.
[GEOL0069 Jupyter Notebook] (https://cpomucl.github.io/GEOL0069-AI4EO/intro.html)
[awesome-readme](https://github.com/matiassingers/awesome-readme)
[PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
[dbader](https://github.com/dbader/readme-template)
