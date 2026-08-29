# Awesome-EarthObservation-Code with stars

A curated list of awesome tools, tutorials, code, helpful projects, links, stuff about Earth Observation and Geospatial stuff!

Please note that this is <b>not</b> offically an awesome list.

## Latest news

<b> Update May 2026</b> Any links to my (old) website will cease this month - the old blogs are archive in another repo. If you want the latest news in EO I recommend [Spectral Reflectance](https://www.spectralreflectance.space/). My self employment ended in March 2026 but my love and joy for all things EO has not you can find me on LinkedIn [Andrew Cutts](https://www.linkedin.com/in/andrewcutts/)

<b> A note of caution </b> During the QC of links I note that the vast majority are 2years+ old or considerably older. Some repos are retired and still visible, some code is > 10 years old. Tread carefully. This list is open to PR's and suggestions, it is updated infrequently by myself. If you find a link that is helpful, share it! We have 1.3k stars now so plenty of eyes on it. You will get acknowledged in the contributors file.

Annotations are based on the headers - and where available - on the github accounts

<div align="center">

</div>

# Contents

\| [<b>Earth Observation introduction</b>](#earth-observation-introduction) |<br>

\| [Open EO](#open-eo) | [remotesensing.info](#remote-sensinginfo) | [Python processing](#python-processing-of-optical-imagery-non-deep-learning) | [Resources for R](#resources-for-r) | [Languages other than Python and R](#languages-other-than-python-and-r) | [Training and Learning](#training-and-learning) | [Deep Learning & Machine Learning](#deep-learning-and-machine-learning) | [GDAL of course](#gdal-of-course) | [Earth Observation coding on YouTube](#earth-observation-coding-on-youtube) | [Google Earth Engine](#earth-engine) | [Open Data Cube](#open-data-cube) | [Planetary Computer](#planetary-computer) | [QGIS and Grass](#qgis-and-grass) | [Climate & Weather resources](#climate-and-weather-based-resources) | [DEM projects](#dem-projects) | [SAR](#sar) | [LiDAR](#lidar) | [GEDI](#gedi) | [InSAR](#insar) | [Landuse](#landuse) | [Visualisation](#visualisation) | [EO code Competitions](#eo-code-competitions) | [ARD links](#ard-links) | [Useful EO code based twitter accounts](#useful-eo-code-based-twitter-accounts) | [List of Great GitHub accounts](#great-github-accounts) | [EO Geospatial companies or orgs making big contributions](#eo-geospatial-companies-or-orgs-making-big-contributions) |

\| [Cloud Native Geospatial](#cloud-native-geospatial) | [STAC](#stac) | [COG](#cog)

These sections are non EO code specific, but included to be relevant <br>
\| [Interesting Non EO parts Python](#interesting-non-eo-parts-python) | [Interesting Non EO parts other languages](#interesting-non-eo-parts-other-languages) | [Data](#data) | [A footnote on awesome](#a-footnote-on-awesome)

#### Start Here

## Earth Observation Introduction

If you are not familiar with Earth Observation then these links may help set context before you start using data. I didn't initially aim at including links like these but if you are not familiar with Earth Observation then some good resources to get you going may help prior to diving into code.

* [Earth Observation Text books](https://www.eoa.org.au/earth-observation-textbooks) - Earth Observation: Data, Processing and Applications is an Australian Earth Observation (EO) community undertaking to describe EO data, processing and applications in an Australian context and includes a wide range of local case studies to demonstrate Australia’s increasing usage of EO data.
* [ESA newcomers guide](https://business.esa.int/newcomers-earth-observation-guide) - The aim of this guide is to help non-experts in providing a starting point in the decision process for selecting an appropriate Earth Observation (EO) solution.
* [The state of satellites](https://landscape.satsummit.io/) - The satellite systems we use to capture, analyze, and distribute data about the Earth are improving every day, creating bold new opportunities for impact in global development.
* [Landsats Enduring Legacy](https://my.asprs.org/landsat) - pdf download over 600 pages of remote sensing!

You may also wish to navigate a search of the terms `satellite-imagery` and `earth-observation` to get the latest list of topics that have these terms in their headers

* [satellite-imagery](https://github.com/topics/satellite-imagery)
* [earth-observation](https://github.com/topics/earth-observation)

Two excellent videos (approx 20mins) about `Earth observation`

[I Couldn't Find a Video Explaining Satellite Images, So I Made One](https://www.youtube.com/watch?v=xy5qR0cBFGs)

[How Radar Satellites See through Clouds (Synthetic Aperture Radar Explained)](https://www.youtube.com/watch?v=zMsCyEAOrh0)

Not sure the best place for data catalogs is but this is a good start if that interests you [Data Catalogs](https://github.com/opengeos/geospatial-data-catalogs) ⭐ 661 | 🐛 0 | 🌐 Python | 📅 2026-08-28

* [Mapping Data Sources](https://github.com/kevinbullock/Mapping-data) ⭐ 18 | 🐛 1 | 🌐 HTML | 📅 2025-10-21 - Aggregating sources of mapping data [An AI version](https://kevinbullock.github.io/Mapping-data/)

## Open EO

OpenEO covers many of the bases, hard to know whether to break it into different categories, it has many components. At present I mention it here at the start only.<br>

* [Open EO](https://openeo.org/) - openEO develops an open API to connect `R`, `Python`, `JavaScript` and other clients to big Earth observation cloud back-ends in a simple and unified way.
* [openeo-processes](https://github.com/Open-EO/openeo-processes) ⭐ 60 | 🐛 73 | 🌐 JavaScript | 📅 2026-06-19 - Interoperable processes for openEO's big Earth observation cloud processing [website](https://processes.openeo.org/)

## Remote Sensing.info

remotesening.info warrents its own section, the vast array of tools and processing software is incredible
[RemoteSensing](https://github.com/remotesensinginfo) - Short tutorials and reference to useful software tools for the acquisition and processing of remote sensed Earth Observation data

* [ARCSI](https://github.com/remotesensinginfo/arcsi) ⭐ 46 | 🐛 5 | 🌐 Python | 📅 2024-07-28 - Software to automate the production of optical analysis ready data (ARD) from Landsat, Sentinel-2 and others
* [eodatadown](https://github.com/remotesensinginfo/eodatadown) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-02-03 - The Earth Observation Data Downloader (EODataDown) is a tool for automatically downloading and processing EO data to an analysis ready data product. This software forms a core component of a monitoring system based on EO data.
* [RSGISLib](http://rsgislib.org/rsgislib.html) - The Remote Sensing and GIS software library (RSGISLib) is a collection of tools for processing remote sensing and GIS datasets. The tools are accessed using `Python` bindings.
* more to come..

## `Python` processing of optical imagery (non deep learning)

This section full of great code and projects related to processing optical satellite imagery with `Python` . Please suggest groupings or re assignments if needed - the idea is to make the Python code examples here easier to find. Categories are highly subjective.

### Download

* [sentinelsat](https://github.com/sentinelsat/sentinelsat) ⚠️ Archived - Search and download Copernicus Sentinel satellite images [sentinelsat docs](https://sentinelsat.readthedocs.io/en/stable/) `Python`
* [Landsat-Util](https://github.com/developmentseed/landsat-util) ⭐ 698 | 🐛 36 | 🌐 Python | 📅 2022-04-14 - A utility to search, download and process Landsat 8 satellite imagery `Python`
* [landsatexplore](https://github.com/yannforget/landsatxplore) ⭐ 240 | 🐛 65 | 🌐 Python | 📅 2024-11-30 - Search and download Landsat scenes from EarthExplorer. `Python`
* [LANDSAT-Download](https://github.com/olivierhagolle/LANDSAT-Download) ⭐ 209 | 🐛 17 | 🌐 Python | 📅 2020-11-12 - Automated download of LANDSAT data from USGS website
* [Sentinel-download](https://github.com/olivierhagolle/Sentinel-download) ⭐ 194 | 🐛 15 | 🌐 Python | 📅 2018-09-30 - Automated download of Sentinel-2 L1C data from ESA (through wget) `Python`
* [phidown](https://github.com/ESA-PhiLab/phidown/tree/main) ⭐ 104 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-06-12 - Manage, search, and download Earth Observation data with Φ-down from Copernicus missions with ease and efficiency. [docs](https://esa-philab.github.io/phidown/)
* [sat-extractor](https://github.com/FrontierDevelopmentLab/sat-extractor) ⭐ 81 | 🐛 3 | 🌐 Python | 📅 2022-07-04 - Extract Satellite Imagery from public constellations at scale `Python`
* [pylandsat](https://github.com/yannforget/pylandsat) ⭐ 65 | 🐛 10 | 🌐 Python | 📅 2023-06-07 - Search, download, and preprocess Landsat imagery `Python`
* [get\_modis](https://github.com/jgomezdans/get_modis) ⭐ 62 | 🐛 5 | 🌐 Python | 📅 2022-08-30 - Downloading MODIS data from the USGS repository `Python`
* [esa\_sentinel](https://github.com/jonas-eberle/esa_sentinel) ⚠️ Archived - ESA Sentinel Search & Download API
* [Sedas API](https://github.com/SatelliteApplicationsCatapult/sedas_pyapi) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2021-07-15 - `Python` client library for the SeDAS API
* [EODAG](https://eodag.readthedocs.io/en/latest/) - Command line tool and a plugin-oriented Python framework for searching, aggregating results and downloading remote sensed images while offering a unified API for data access regardless of the data provider.
* [data-prep-scripts](https://lpdaac.usgs.gov/tools/data-prep-scripts/) - This collection of `R` and `Python` scripts can be used to download data and perform basic data processing functions such as georeferencing, reprojecting, converting, and reformatting data. All scripts are available for download from the LP DAAC User Resources [BitBucket Code Repository](https://git.earthdata.nasa.gov/projects/LPDUR).
* [Stream NASA data directly into Python objects](https://nbviewer.jupyter.org/gist/scottyhq/a1ddbb12f97764860160370229b19261) - Skip the download! Stream NASA data directly into Python objects from [blog post](https://medium.com/pangeo/intake-stac-nasa-4cd78d6246b7)

### Processing imagery - post processing

* [felicette](https://github.com/plant99/felicette) ⚠️ Archived - Satellite imagery for dummies. `Python`

* [geonotebook](https://github.com/OpenGeoscience/geonotebook) ⭐ 1,086 | 🐛 39 | 🌐 Python | 📅 2019-01-21 - A Jupyter notebook extension for geospatial visualization and analysis `Python`

* [CostalSat](https://github.com/kvos/CoastSat) ⭐ 887 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2026-06-05 - Global shoreline mapping tool from satellite imagery `Python`

* [verde](https://github.com/fatiando/verde) ⭐ 666 | 🐛 46 | 🌐 Python | 📅 2026-08-04 - Processing and gridding spatial data using Green's functions

* [EarthPy](https://github.com/earthlab/earthpy) ⭐ 536 | 🐛 45 | 🌐 Python | 📅 2026-08-16 - A package built to support working with spatial data using open source python. [docs](https://earthpy.readthedocs.io/en/latest/)

* [pyresample](https://github.com/pytroll/pyresample) ⭐ 385 | 🐛 125 | 🌐 Python | 📅 2026-08-06 - Geospatial image resampling in `Python`

* [geocube](https://github.com/corteva/geocube) ⭐ 381 | 🐛 8 | 🌐 Python | 📅 2026-07-20 - Tool to convert geopandas vector data into rasterized xarray data. `Python` [docs](https://corteva.github.io/geocube/stable/)

* [EOReader](https://github.com/sertit/eoreader) ⭐ 346 | 🐛 60 | 🌐 Python | 📅 2026-08-03 - Opensource `Python` library reading optical and SAR sensors, loading and stacking bands in a sensor-agnostic way.

* [s2p](https://github.com/cmla/s2p) ⭐ 264 | 🐛 32 | 🌐 Python | 📅 2025-10-17 - Satellite Stereo Pipeline `Python`

* [RasterFrames / pyrasterframes](https://github.com/locationtech/rasterframes) ⭐ 256 | 🐛 143 | 🌐 Jupyter Notebook | 📅 2025-12-30 - brings together Earth-observation (EO) data access, cloud computing, and DataFrame-based data science. [docs](https://rasterframes.io/)

* [bv](https://github.com/daleroberts/bv) ⭐ 233 | 🐛 1 | 🌐 Python | 📅 2017-01-17 - Quickly view satellite imagery, hyperspectral imagery, and machine learning image outputs directly in your iTerm2 terminal. `Python`

* [xcube](https://github.com/dcs4cop/xcube) ⭐ 230 | 🐛 174 | 🌐 Python | 📅 2026-08-28 - xcube is a `Python` package for generating and exploiting data cubes powered by xarray, dask, and zarr

* [mapchete](https://github.com/ungarj/mapchete) ⭐ 211 | 🐛 51 | 🌐 Python | 📅 2026-08-27 - Tile-based geodata processing using rasterio & Fiona `Python`

* [onearth](https://github.com/nasa-gibs/onearth) ⭐ 203 | 🐛 1 | 🌐 Python | 📅 2026-08-04 - High-performance web services for tiled raster imagery and vector tiles `Python`

* [cresi](https://github.com/avanetten/cresi) ⭐ 202 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2022-08-25 - Road network extraction from satellite imagery, with speed and travel time estmates

* [nansat](https://github.com/nansencenter/nansat) ⭐ 188 | 🐛 100 | 🌐 Python | 📅 2026-07-02 - Scientist friendly Python toolbox for processing 2D satellite Earth observation data. `Python`[docs](https://nansat.readthedocs.io/en/latest/index.html)

* [StarFM for Python](https://github.com/nmileva/starfm4py) ⭐ 150 | 🐛 1 | 🌐 Python | 📅 2023-02-08 - The STARFM fusion model for `Python` (image fusion)

* [unmixing](https://github.com/arthur-e/unmixing) ⭐ 124 | 🐛 6 | 🌐 Python | 📅 2019-12-19 - Interactive tools for spectral mixture analysis of multispectral raster data in `Python`

* [tifviewer](https://github.com/nkeikon/tifviewer) ⭐ 102 | 🐛 1 | 🌐 Python | 📅 2026-06-23 - A simple GeoTIFF viewer for the command line `Python`

* [6S\_emulator](https://github.com/samsammurphy/6S_emulator) ⭐ 86 | 🐛 2 | 🌐 HTML | 📅 2020-08-07 - Atmospheric correction in Python using a 6S emulator

* [Telluric](https://github.com/satellogic/telluric) ⭐ 86 | 🐛 52 | 🌐 Jupyter Notebook | 📅 2025-02-12 - telluric is a `Python` library to manage vector and raster geospatial data in an interactive and easy way

* [Opensource-OBIA\_processing\_chain](https://github.com/tgrippa/Opensource_OBIA_processing_chain) ⭐ 75 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2020-09-10 - An open-source semi-automated processing chain for urban OBIA classification. `Grass` `Python`

* [Opensource\_OBIA\_processing\_chain](https://github.com/tgrippa/Opensource_OBIA_processing_chain) ⭐ 75 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2020-09-10 - An open-source semi-automated processing chain for urban OBIA classification.

* [SIAC](https://github.com/MarcYin/SIAC) ⭐ 72 | 🐛 3 | 🌐 C | 📅 2026-08-01 - A sensor invariant Atmospheric Correction (SIAC) [alg doc](http://www2.geog.ucl.ac.uk/~ucfafyi/Atmo_Cor/)

* [CometTS](https://github.com/CosmiQ/CometTS) ⭐ 62 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2019-10-23 - Comet Time Series Toolset for working with a time-series of remote sensing imagery and user defined polygons

* [ukis-csmask](https://github.com/dlr-eoc/ukis-csmask) ⭐ 51 | 🐛 0 | 🌐 Python | 📅 2025-07-10 - masks clouds and cloud shadows in Sentinel-2, Landsat-8, Landsat-7 and Landsat-5 images `Python`

* [SIF tools](https://github.com/cfranken/SIF_tools) ⭐ 47 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-02-04 - some tools for accessing OCO-2 data

* [Python-Remote-Sensing-Scripts](https://github.com/JavierLopatin/Python-Remote-Sensing-Scripts) ⭐ 44 | 🐛 0 | 🌐 Python | 📅 2023-05-19 - `Python` 3. X scripts for remote sensing processing

* [Remote Sensing indicies calc](https://github.com/rander38/Remote-Sensing-Indices-Derivation-Tool) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2018-03-19 - Calculate spectral remote sensing indices from satellite imagery

* [pyrgis](https://github.com/PratyushTripathy/pyrsgis) ⭐ 35 | 🐛 10 | 🌐 Python | 📅 2025-09-20 - This repository cointains the source code of the 'pyrsgis' `Python` package.

* [LandSurfaceClustering](https://github.com/lhalloran/LandSurfaceClustering) ⭐ 34 | 🐛 0 | 🌐 Python | 📅 2019-10-29 - Land surface classification using remote sensing data with unsupervised machine learning (k-means) `Python`

* [Python-for-remote-sensing](https://github.com/Seyed-Ali-Ahmadi/Python-for-Remote-Sensing) ⭐ 33 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-02-13 - `Python` codes for remote sensing applications will be uploaded. [blog](https://earthobserv.com/)

* [spatialist](https://github.com/johntruckenbrodt/spatialist) ⭐ 32 | 🐛 4 | 🌐 Python | 📅 2026-08-27 - A `Python` module for spatial data handling

* [tiletanic](https://github.com/DigitalGlobe/tiletanic) ⭐ 24 | 🐛 4 | 🌐 Python | 📅 2025-04-04 - `Python` library to support generalized geographic tiling schemes

* [S2\_TOA\_TO\_LAI](https://github.com/MarcYin/S2_TOA_TO_LAI) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2020-12-01 - From Sentinel 2 TOA reflectance to LAI

* [landsat and sentinel fusion](https://github.com/yannforget/landsat-sentinel-fusion) ⭐ 23 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-03-06 - Complementarity Between Sentinel-1 and Landsat 8 Imagery for Built-Up Mapping in Sub-Saharan Africa `Python`

* [ipyearth](https://github.com/davidbrochart/ipyearth) ⭐ 21 | 🐛 2 | 🌐 JavaScript | 📅 2018-10-29 - An IPython Widget for Earth Maps `Python`

* [Planet Movement](https://github.com/rhammell/planet-movement) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2020-08-16 - Find and process Planet image pairs to highlight object movement. `Python`

* [get\_river\_width](https://github.com/briannapagan/get_river_width/blob/master/get_river_width.py) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2019-11-29 - Find the river width (and other properties) from a masked water image `Python`

* [jeolib-pyjeo](https://github.com/ec-jrc/jeolib-pyjeo) ⭐ 18 | 🐛 2 | 🌐 Python | 📅 2026-08-11 - pyjeo is a library for image processing for geospatial data implemented in JRC Ispra. `Python`

* [MTG FRP Fire Progression](https://github.com/PedroVenancio/mtg-frp-fire-progression) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2025-12-15 - `Python` script for creating hourly and cumulative fire progression polygons from MTG (Meteosat Third Generation) FRP (Fire Radiative Power) data, with calibration against reference burned areas and fire intensity estimation

* [vegetation health](https://github.com/tommylees112/vegetation_health) ⭐ 12 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2019-05-02 - Predicting vegetation health from precipitation and temperature

* [cedar-datacube](https://github.com/ceholden/cedar-datacube) ⚠️ Archived - cedar - Create Earth engine Datacubes of Analytical Readiness `Python` [docs](https://ceholden.github.io/cedar-datacube/master/)

* [pykic](https://github.com/EkicierNico/pykic) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2024-02-03 - 'Python' module for remote sensing and GIS domain (image/signal, vector, miscellaneous processing)

* [esda dissertation](https://github.com/Rabscuttler/esda-dissertation) ⭐ 8 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-02-17 - MSc Energy Systems & Data Analytics dissertation project notebooks - identifying solar PV from aerial imagery with computer vision `Python`

* [geff\_notebooks](https://github.com/cvitolo/geff_notebooks) ⭐ 8 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2021-05-19 - Jupyter notebooks to post-process fire danger data using `Python`/`xarray`

* [extract\_water](https://github.com/redfoxgis/extract_water/blob/master/extract_water.py) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2020-02-01 - Extract water from nIR imagery `Python`

* [openaq-s5](https://github.com/JamesOConnor/openaq-s5) ⭐ 5 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2022-12-08 - Map openaq data onto Sentinel5P data using AWS lambda

* [IEO](https://github.com/DrGuy/ieo) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2024-04-15 - Irish Earth Observation (IEO) remote sensing data processing Python module `Python`

* [stems - Spatio-temporal Tools for Earth Monitoring Science](https://github.com/ceholden/stems) ⚠️ Archived - Spatio-temporal Tools for Earth Monitoring Science `Python` [docs](https://ceholden.github.io/stems/master/)

* [Satellite-Image-Analysis](https://github.com/MasterPhysicist/Satellite-Image-Analysis) ⭐ 1 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-03-19 - PlanetScope, Landsat-8 and Sentinel-2 Image analysis `Python` codes

* [fc-up42](https://github.com/petescarth/fc-up42) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2019-10-03 - UP42 Block for Fractional Cover calculation from Sentinel 2 L2A Data `Python`

* [IEOtools](https://github.com/DrGuy/IEOtools) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-08-04 - Tools for managing Earth observation data. Currently only supports Landsat imagery `Python`

* [tatortot](https://github.com/GeoBigData/tatortot) ⚠️ Archived - Prototype for a simple image annotation tool `Python`

* [river-width](https://github.com/redfoxgis/river-width) - Extracts water features from 4 band NAIP imagery and calculates river metrics. `Python`

* [Intro to Python GIS](https://automating-gis-processes.github.io) - Great free 3-day course by the University of Helsinki on GIS processing with Python

* [nansat-lite](https://gitlab.com/jobel-open-source/nansat-lite) - nansat-lite is not a full nansat build for `Python` 3.5. Only bits of code from main classes, to start with. Eventually, if need it, more code will be added.

### Cloud Native Geospatial

* [GeoLambda](https://github.com/developmentseed/geolambda) ⭐ 306 | 🐛 21 | 🌐 Dockerfile | 📅 2026-07-02 - Create and deploy Geospatial AWS Lambda functions `Python`
* [rio-viz](https://github.com/developmentseed/rio-viz) ⭐ 168 | 🐛 7 | 🌐 HTML | 📅 2026-06-29 - Visualize Cloud Optimized GeoTIFF in browser `html` `Python`
* [aws-sat-api-py](https://github.com/RemotePixel/remotepixel-api) ⚠️ Archived - Process Satellite data using AWS Lambda functions
* [Sentinel-s3](https://github.com/developmentseed/sentinel-s3) ⭐ 12 | 🐛 2 | 🌐 Python | 📅 2019-10-22 - `Python` libraries for extracting Sentinel-2's metadata from Amazon S3
* [cng-workshop](https://github.com/Element84/cng-workshop) ⭐ 5 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-03-16 - Intro to cloud-native geospatial workshop
* [geocore](https://github.com/Canadian-Geospatial-Platform/geocore) ⭐ 3 | 🐛 24 | 🌐 SCSS | 📅 2025-12-23 - GeoCore is an Open Source Cloud Native (AWS) Geospatial Catalog | GeoCore est un catalogue géospatial Open Source Cloud Native (AWS)
* [cloud-native-geospatial](https://github.com/ua-datalab/cloud-native-geospatial) ⭐ 0 | 🐛 0 | 📅 2023-12-12 - resource [introduction to cloud native geospatial](https://ua-datalab.github.io/cloud-native-geospatial/)

#### STAC

* [stac-utils](https://github.com/stac-utils) - Tools for working with SpatioTemporal Asset Catalogs (STAC) (perhaps worth going here first for STAC) `Python` `Javascript`
  * [STAC Spec](https://github.com/radiantearth/stac-spec) ⭐ 922 | 🐛 47 | 🌐 JavaScript | 📅 2026-08-26 - SpatioTemporal Asset Catalog specification - making geospatial assets openly searchable and crawlable
  * [pystac](https://github.com/stac-utils/pystac) ⭐ 457 | 🐛 81 | 🌐 Python | 📅 2026-08-25 - `Python` library for working with any SpatioTemporal Asset Catalog (STAC)
    * [pystac-client](https://github.com/stac-utils/pystac-client) ⭐ 207 | 🐛 23 | 🌐 Python | 📅 2026-08-27 - `Python` client for STAC Catalogs and APIs
    * [stactools](https://github.com/stac-utils/stactools) ⭐ 113 | 🐛 43 | 🌐 Python | 📅 2024-12-23 - Command line utility and `Python` library for STAC
  * [stac-fastapi](https://github.com/stac-utils/stac-fastapi) ⭐ 323 | 🐛 41 | 🌐 Python | 📅 2026-08-28 - STAC API implementation with FastAPI. `Python`
  * [stackstac](https://github.com/gjoseph92/stackstac) ⭐ 270 | 🐛 60 | 🌐 Python | 📅 2024-08-10 - Turn a list of STAC items into a 4D xarray DataArray `Python`
  * [pgstac](https://github.com/stac-utils/pgstac) ⭐ 222 | 🐛 70 | 🌐 PLpgSQL | 📅 2026-08-24 - Schema, functions and a `Python` library for storing and accessing STAC collections and items in `PostgreSQL`
  * [pgstac](https://github.com/stac-utils/pgstac) ⭐ 222 | 🐛 70 | 🌐 PLpgSQL | 📅 2026-08-24 - Schema, functions and a python library for storing and accessing STAC collections and items in PostgreSQL
  * [pystac-client](https://github.com/stac-utils/pystac-client) ⭐ 207 | 🐛 23 | 🌐 Python | 📅 2026-08-27 - `Python` client for searching STAC APIs
  * [stac-geoparquet](https://github.com/stac-utils/stac-geoparquet) ⭐ 149 | 🐛 20 | 🌐 Python | 📅 2026-08-19 - Convert STAC items to geoparquet. `Python`
  * [stac-rs](https://github.com/stac-utils/stac-rs) ⭐ 144 | 🐛 28 | 🌐 Rust | 📅 2026-08-27 - `Rust` implementation of the SpatioTemporal Asset Catalog (STAC) specification
  * [stac-rs](https://github.com/stac-utils/stac-rs) ⭐ 144 | 🐛 28 | 🌐 Rust | 📅 2026-08-27 - Tools and libraries for the SpatioTemporal Asset Catalog (STAC) specification, written in `Rust`
  * [titiler-pgstac](https://github.com/stac-utils/titiler-pgstac) ⭐ 130 | 🐛 7 | 🌐 Python | 📅 2026-08-27 - TiTiler + PgSTAC
  * [stac-fastapi-pgstac](https://github.com/stac-utils/stac-fastapi-pgstac) ⭐ 111 | 🐛 36 | 🌐 Python | 📅 2026-08-25 - PostgreSQL backend for stac-fastapi using pgstac
  * [stac-server](https://github.com/stac-utils/stac-server) ⭐ 102 | 🐛 41 | 🌐 TypeScript | 📅 2026-08-26 - A Node-based STAC API, AWS Serverless, OpenSearch `Javascript`
  * [qgis-stac-plugin](https://github.com/stac-utils/qgis-stac-plugin) ⭐ 86 | 🐛 65 | 🌐 Python | 📅 2024-07-30 - QGIS plugin for reading STAC APIs `Python`
  * [stac-pydantic](https://github.com/stac-utils/stac-pydantic) ⭐ 83 | 🐛 9 | 🌐 Python | 📅 2026-08-17 - Pydantic data models for the STAC spec `Python`
  * [elastic search](https://github.com/stac-utils/stac-fastapi-elasticsearch-opensearch) ⭐ 78 | 🐛 32 | 🌐 Python | 📅 2026-08-28 - Elasticsearch backend for stac-fastapi with Opensearch support. `Python`
  * [easystac](https://github.com/cloudsen12/easystac) ⭐ 68 | 🐛 1 | 🌐 Python | 📅 2022-08-07 - A `Python` package for simple STAC queries
  * [stac-validator](https://github.com/stac-utils/stac-validator) ⭐ 62 | 🐛 11 | 🌐 Python | 📅 2026-08-05 - Validator for the stac-spec `Python`
  * [stac-layer](https://github.com/stac-utils/stac-layer) ⭐ 53 | 🐛 13 | 🌐 HTML | 📅 2023-10-14 - Visualize a STAC Item or Collection on a Leaflet Map
  * [stac-asset](https://github.com/stac-utils/stac-asset) ⭐ 47 | 🐛 18 | 🌐 Python | 📅 2026-08-17 - Read and download STAC Assets, using a variety of authentication schemes
  * [xpystac](https://github.com/stac-utils/xpystac) ⭐ 45 | 🐛 12 | 🌐 Python | 📅 2025-11-28 - For extending xarray.open\_dataset to accept pystac objects `Python`
  * [stac-nb](https://github.com/darrenwiens/stac-nb) ⭐ 35 | 🐛 3 | 🌐 Python | 📅 2022-10-22 - STAC in Jupyter Notebooks `Python`
  * [stac-check](https://github.com/stac-utils/stac-check) ⭐ 31 | 🐛 10 | 🌐 Python | 📅 2026-08-03 - Linting and validation tool for STAC assets
  * [stac-utils](https://github.com/stac-utils/stac-task) ⭐ 26 | 🐛 26 | 🌐 Python | 📅 2026-05-05 - Provides a class interface for running custom algorithms on STAC ItemCollections `Python`
  * [stac-api-validator](https://github.com/stac-utils/stac-api-validator) ⭐ 25 | 🐛 39 | 🌐 Python | 📅 2026-06-22 - A STAC API validation client `Python`
  * [stac-node-validator](https://github.com/stac-utils/stac-node-validator) ⭐ 21 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-22 - Simple validator for STAC Items, Catalogs, and Collections. STAC 1.0.0 compliant! `Javascript`
  * [stac-terminal](https://github.com/stac-utils/stac-terminal) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2023-10-31 - Output info on STAC Items in the terminal
  * [stac4s](https://github.com/stac-utils/stac4s) ⭐ 17 | 🐛 29 | 🌐 Scala | 📅 2026-07-19 - A `Scala` library with primitives to build applications using the SpatioTemporal Asset Catalogs specification
  * [stac-fields](https://github.com/stac-utils/stac-fields) ⭐ 11 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-04 - A minimal STAC library that contains a list of STAC fields with some metadata and helper functions for styling as HTML. `Javascript`
  * [stac-index](https://github.com/stac-utils/stac-index) ⭐ 10 | 🐛 17 | 🌐 Vue | 📅 2026-08-18 - A service that lists all available and registered STAC catalogs and APIs.
  * [pgstac-rs](https://github.com/stac-utils/pgstac-rs) ⚠️ Archived - `Rust` interface to pgstac
  * [stac-table](https://github.com/stac-utils/stac-table) ⚠️ Archived
  * [stac-migrate](https://github.com/stac-utils/stac-migrate) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-18 - A tool to migrate Items, Catalogs and Collections from old versions to the most recent one. `Javascript`

#### COG

* [titiler](https://github.com/developmentseed/titiler) ⭐ 1,153 | 🐛 24 | 🌐 Python | 📅 2026-08-24 - A modern dynamic tile server built on top of `FastAPI` and `Rasterio/GDAL`.
* [cogeo-mosaic](https://github.com/developmentseed/cogeo-mosaic) ⭐ 119 | 🐛 19 | 🌐 Python | 📅 2026-08-28 - Create and use COG mosaic based on mosaicJSON `Python`
* [cogeotiff](https://github.com/blacha/cogeotiff) ⭐ 116 | 🐛 17 | 🌐 TypeScript | 📅 2026-08-28 - High performance cloud optimised geotiff reader
* [async-cog-reader](https://github.com/geospatial-jeff/async-cog-reader) ⭐ 76 | 🐛 29 | 🌐 Python | 📅 2021-07-02 - Read Cloud Optimized GeoTiffs without GDAL`Python`
* [aiocogeo](https://github.com/geospatial-jeff/aiocogeo) ⭐ 76 | 🐛 29 | 🌐 Python | 📅 2021-07-02 - Asynchronous cogeotiff reader `Python`
* [COG Dumper](https://github.com/mapbox/COGDumper) ⭐ 72 | 🐛 3 | 🌐 Python | 📅 2026-06-29 - Dumps tiles out of a cloud optimized geotiff `Python`
* [COG Validator](https://github.com/rouault/cog_validator) ⭐ 69 | 🐛 1 | 🌐 Python | 📅 2023-11-08 - Cloud Optimized GeoTIFF validation service
* [Sentinel-2-cog](https://github.com/developmentseed/sentinel-2-cog) ⭐ 18 | 🐛 10 | 🌐 Python | 📅 2022-12-06 - Convert Sentinel-2 JPEG 2000 to COG with AWS Lambda `Python`
* [COG pptx/pdf](https://github.com/saheelBreezo/Cloud-Optimised-Geotiff/blob/master/Talk/Cloud_Optimized_GeoTIFF_Blue_Sky_Analytics.pdf) ⭐ 5 | 🐛 0 | 📅 2022-09-07 - talk on COG
* [ecw-converter](https://github.com/lifebit-ai/ecw-converter) - Dockerised `Python` scripts & Nextflow pipeline for converting ecw files to either geotiffs or Cloud Optimised Geotiffs (COGs)

### Case studies / Projects

* [Python from space](https://github.com/kscottz/PythonFromSpace) ⭐ 470 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2018-02-20 - `Python` Examples for Remote Sensing
* [Truck\_Detection\_Sentinel2\_COVID19](https://github.com/hfisser/Truck_Detection_Sentinel2_COVID19) ⭐ 101 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-06-12 - This repository is designated to detecting trucks using Sentinel-2 data. `Python`
* [Satellite imagery analysis with Python](https://github.com/parulnith/Satellite-Imagery-Analysis-with-Python) ⭐ 51 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2018-12-08 - Getting acquainted with the concept of satellite imagery data and how it can be analyzed to investigate real-world environmental and humanitarian challenges. `Python` `Jupyter Notebooks` [associated blog](https://medium.com/analytics-vidhya/satellite-imagery-analysis-with-python-3f8ccf8a7c32)
* [Povetry predition using satellite imagery](https://github.com/carsonluuu/Poverty-Prediction-by-Satellite-Imagery) ⭐ 43 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2020-11-23 - Poverty Prediction by Combination of Satellite Imagery
* [ap-latem](https://github.com/dymaxionlabs/ap-latam) ⚠️ Archived - Detection of slums and informal settlements from satellite imagery `Python`
* [SentinelBot](https://github.com/JamesOConnor/Sentinel_bot) ⭐ 17 | 🐛 4 | 🌐 Python | 📅 2022-12-08 - A twitter bot which processes raw sentinel data `Python` [SentinelBot on twitter](https://twitter.com/sentinel_bot)
* [Satellite imagery in Pakistan](https://github.com/iam-mhaseeb/Satellite-Imagery-Analysis-of-Vegetation-in-Southern-Pakistan) ⚠️ Archived - This repository contains a study how we can examine the vegetation cover of a region with the help of satellite data. The notebook in this repository aims to familiarise with the concept of satellite imagery data and how it can be analyzed to investigate real-world environmental and humanitarian challenges.
* [local\_structire\_wpb-severity](https://github.com/mikoontz/local-structure-wpb-severity) ⭐ 6 | 🐛 1 | 🌐 R | 📅 2022-03-17 - Analysis of drone imagery to characterize forest structure and severity of a tree killing insect `Python`
* [count blue pixels](https://github.com/craic/count_shelters) ⭐ 3 | 🐛 0 | 🌐 Ruby | 📅 2012-12-03 - This project is an experiment in using simple image processing techniques on satellite images downloaded from Google Maps in order to quantify the relative density of temporary shelters in adjacent qudarants. `Python` `Ruby`
* [Artificial Intelligence for Geospatial Analysis with Pytorch’s TorchGeo (multi parts)](https://towardsdatascience.com/artificial-intelligence-for-geospatial-analysis-with-pytorchs-torchgeo-part-1-52d17e409f09) - An end-to-end deep learning geospatial segmentation project using Pytorch and TorchGeo packages - [code](https://gist.github.com/cordmaur/d050973aa3ed980023e9239183a2cb66#file-earthsurfacewater_medium_2-ipynb)

### Company specific examples

(you may need to create an account to use these resources)

* [SentinelHub-py](https://github.com/sentinel-hub/sentinelhub-py) ⭐ 911 | 🐛 22 | 🌐 Python | 📅 2026-03-10 - Download and process satellite imagery in Python using Sentinel Hub services.
* [Planet notebooks](https://github.com/planetlabs/notebooks) ⭐ 678 | 🐛 15 | 🌐 Jupyter Notebook | 📅 2026-06-18 - interactive notebooks from Planet Engineering `Python`
* [sentinel2-cloud-detector](https://github.com/sentinel-hub/sentinel2-cloud-detector) ⭐ 493 | 🐛 4 | 🌐 Python | 📅 2026-01-15 - Sentinel Hub Cloud Detector for Sentinel-2 images in `Python`
* [Planet-client-API](https://github.com/planetlabs/planet-client-python) ⭐ 298 | 🐛 80 | 🌐 Python | 📅 2026-08-21 - `Python` client for Planet APIs
* [Orbit predictor](https://github.com/satellogic/orbit-predictor) ⭐ 151 | 🐛 18 | 🌐 Python | 📅 2025-06-16 - Python library to propagate satellite orbits.
* [up42-py](https://github.com/up42/up42-py) ⭐ 143 | 🐛 5 | 🌐 Python | 📅 2026-08-28 - Python SDK for UP42, the geospatial marketplace and developer platform. `Python`
* [icecube](https://github.com/iceye-ltd/icecube) ⭐ 86 | 🐛 6 | 🌐 Python | 📅 2021-12-09 - Create time-series datacubes for supervised machine learning with ICEYE SAR images. `Python`
* [Maxar GDBx tools](https://github.com/DigitalGlobe/gbdxtools) ⚠️ Archived - Python SDK for using GBDX.
* \[Project Eucalyptus]\(<https://github.com/Orbio-Earth/Project-Eucalyptus> ⭐ 47 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-06-26 - Open-source pipelines for satellite-based methane detection. Includes trained segmentation models, a synthetic plume generator, and benchmarking tools for Sentinel-2, Landsat 8/9, and EMIT. For research and non-commercial use. `Python`
* [sky truth offshore methane](https://github.com/SkyTruth/offshore-methane) ⭐ 10 | 🐛 3 | 🌐 Python | 📅 2025-10-01 - Offshore methane detection `Python`
* [gdbx-surface-water](https://github.com/gena/gbdx-surface-water) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2018-07-31 - Reservoir surface area detection with Digital Globe imagery and Bayesian methods
* [S2-superresolution](https://github.com/up42/s2-superresolution) - Deep Learning-based algorithm to upsample all Sentinel-2 bands to 10m. Also an example how to use GPUs on UP42. `Python`

### Reflectance / pre processing

* [Py6S](https://github.com/robintw/Py6S) ⭐ 222 | 🐛 18 | 🌐 Python | 📅 2025-10-22 - A `Python`interface to the 6S Radiative Transfer Model
* [prosail](https://github.com/jgomezdans/prosail) ⭐ 163 | 🐛 17 | 🌐 Python | 📅 2025-03-11 - `Python` bindings for the PROSAIL canopy reflectance model
* [radiometric\_normalization](https://github.com/planetlabs/radiometric_normalization) ⭐ 37 | 🐛 2 | 🌐 Python | 📅 2023-08-08 - Implementation of radiometric normalization workflows `Python`
* [color\_balance](https://github.com/planetlabs/color_balance) ⭐ 32 | 🐛 1 | 🌐 Python | 📅 2018-06-07 - Balance your colors! `Python`
* [PyProSail](https://github.com/robintw/PyProSAIL) ⭐ 25 | 🐛 2 | 🌐 Fortran | 📅 2023-03-08 - Python interface to the ProSAIL leaf/canopy reflectance model
* [ACOLITE\_MR](https://github.com/acolite/acolite_mr) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2021-04-21 - ACOLITE\_MR: Atmospheric correction for aquatic applications of metre-scale satellites
* [Landsat7 errors](https://github.com/gena/landsat7-errors) - Identifies errors in raw values of Landsat 7
* [data-retrieval-in-EO](https://gitlab.com/raul.lezameta/data-retrieval-in-EO/-/tree/master) - data-retrieval-in-EO, a project with reports from TU wien

### Python libraries related to EO

* [rasterio](https://github.com/mapbox/rasterio) ⭐ 2,564 | 🐛 156 | 🌐 Python | 📅 2026-08-28 - Rasterio reads and writes geospatial raster datasets
* [SatPy](https://github.com/pytroll/satpy) ⭐ 1,204 | 🐛 562 | 🌐 Python | 📅 2026-08-27 - `Python` package for earth-observing satellite data processing
* [xarray-spatial](https://github.com/makepath/xarray-spatial) ⭐ 969 | 🐛 81 | 🌐 Python | 📅 2026-08-27 - Raster-based Spatial Analysis for `Python`
* [rioxarray](https://github.com/corteva/rioxarray) ⭐ 622 | 🐛 79 | 🌐 Python | 📅 2026-07-27 - geospatial xarray extension powered by rasterio [docs](https://corteva.github.io/rioxarray/stable/)
* [RasterStats](https://github.com/perrygeo/python-rasterstats) ⭐ 561 | 🐛 34 | 🌐 Python | 📅 2026-05-23 - Summary statistics of geospatial raster datasets based on vector geometries. `Python`
* [Whitebox Python](https://github.com/giswqs/whitebox-python) ⭐ 422 | 🐛 1 | 🌐 Python | 📅 2026-01-31 - WhiteboxTools `Python` Frontend
* [pyimpute](https://github.com/perrygeo/pyimpute) ⭐ 129 | 🐛 6 | 🌐 Python | 📅 2023-01-15 - Spatial classification and regression using Scikit-learn and Rasterio `Python`
* [dask-rasterio](https://github.com/dymaxionlabs/dask-rasterio) ⭐ 98 | 🐛 2 | 🌐 Python | 📅 2020-11-28 - Read and write rasters in parallel using Rasterio and Dask `Python`
* [actinia core](https://github.com/mundialis/actinia_core) ⭐ 95 | 🐛 34 | 🌐 Python | 📅 2026-08-20 - Actinia Core is an open source REST API for scalable, distributed, high performance processing of geographical data that uses mainly GRASS GIS for computational tasks. `Python`
* [ukis-pysat](https://github.com/dlr-eoc/ukis-pysat) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2023-06-06 - generic classes and functions to query, access and process multi-spectral and SAR satellite images
* [Xarray pyconuk 2018](https://github.com/robintw/XArray_PyConUK2018) ⭐ 18 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-06-15 - Code and slides for my talk at PyCon UK 2018 on XArray `Python`
* \[titiler-eopf]\(<https://github.com/EOPF-Explorer/titiler-eopf> ⭐ 18 | 🐛 23 | 🌐 Jupyter Notebook | 📅 2026-08-24 - TiTiler application for EOPF dataset `Python`
* [actinia satellite plugin](https://github.com/mundialis/actinia_satellite_plugin) ⚠️ Archived - This actinia plugin is designed for efficient satellite data handling, especially Landsat and Sentinel-2 scenes `Python`
* [Scikit-eo](https://yotarazona.github.io/scikit-eo/tutorials/) - a rich suite of algorithms specifically designed for environmental studies

### Testing your code

* [image-similarity-measures](https://pypi.org/project/image-similarity-measures/) - Implementation of eight evaluation metrics to access the similarity between two images. `Python`
* [fake-geo-images](https://pypi.org/project/fake-geo-images/) - A module to programmatically create geotiff images which can be used for unit tests. `Python`

## Resources for `R`

R is not my area of expertise so this section is lighter than I'd like, plus I'd love to know what is a useful resource
Books! [Geospatial R Books](https://www.bigbookofr.com/geospatial.html) - some `R` books on geospatial

* [lidR](https://github.com/Jean-Romain/lidR) ⭐ 706 | 🐛 16 | 🌐 R | 📅 2026-08-14 - `R` package for airborne LiDAR data manipulation and visualisation for forestry application. Plus [lidRplugins](https://github.com/Jean-Romain/lidRplugins) ⭐ 51 | 🐛 4 | 🌐 R | 📅 2023-02-06 - Extra functions and algorithms for lidR package

* [Spatiotemporal Arrays: Raster and Vector Datacubes](https://github.com/r-spatial/stars) ⭐ 611 | 🐛 26 | 🌐 R | 📅 2026-08-20 - Spatiotemporal Arrays, Raster and Vector Data Cube

* [rnoaa](https://github.com/ropensci/rnoaa) ⭐ 340 | 🐛 28 | 🌐 R | 📅 2025-02-04 - R interface to many NOAA data APIs

* [getSpatialData](https://github.com/16EAGLE/getSpatialData) ⭐ 312 | 🐛 43 | 🌐 R | 📅 2023-07-10 - An `R` package making it easy to query, preview, download and preprocess multiple kinds of spatial data [docs](https://jakob.schwalb-willmann.de/getSpatialData/)

* [whiteboxR](https://github.com/giswqs/whiteboxR) ⭐ 186 | 🐛 5 | 🌐 R | 📅 2025-10-21 - An R frontend of the advanced geospatial data analysis platform - [whitebox-tools](https://github.com/jblindsay/whitebox-tools) ⭐ 1,195 | 🐛 175 | 🌐 Rust | 📅 2026-05-26.

* [GDAL Cubes](https://cran.r-project.org/web/packages/gdalcubes/index.html) - Earth Observation Data Cubes from Satellite Image Collections. Also [here on github](https://github.com/appelmar/gdalcubes_R) ⭐ 131 | 🐛 36 | 🌐 C++ | 📅 2026-05-29

* [ForestTools](https://github.com/andrew-plowright/ForestTools) ⭐ 93 | 🐛 2 | 🌐 C++ | 📅 2025-12-24 - Detect and segment individual tree from remotely sensed data

* [MODISTools](https://github.com/ropensci/MODISTools) ⚠️ Archived - Interface to the MODIS Land Products Subsets Web Services [Docs](https://docs.ropensci.org/MODISTools/)

* [landsatlinkr](https://github.com/jdbcode/LandsatLinkr) ⭐ 50 | 🐛 0 | 🌐 R | 📅 2024-08-20 - An automated system for creating spectrally consistent and cloud-free Landsat image time series stacks from a combination of MSS, TM, ETM+, and OLI sensors [project](http://jdbcode.github.io/LandsatLinkr/)

* [RGISTools](https://github.com/spatialstatisticsupna/RGISTools) ⭐ 50 | 🐛 10 | 🌐 R | 📅 2023-02-09 - Tools for Downloading, Customizing, and Processing Time Series of Satellite Images from Landsat, MODIS, and Sentinel

* [planetR](https://github.com/bevingtona/planetR) ⭐ 45 | 🐛 5 | 🌐 R | 📅 2023-01-17 - (early development) R tools to search, activate and download satellite imagery from the Planet API

* [planetR](https://github.com/bevingtona/planetR) ⭐ 45 | 🐛 5 | 🌐 R | 📅 2023-01-17 - `R` tools to search, activate and download satellite imagery from the Planet API.

* [rerddap](https://github.com/ropensci/rerddap) ⭐ 43 | 🐛 2 | 🌐 R | 📅 2026-07-08 - `R` client for working with ERDDAP servers [docs](https://docs.ropensci.org/rerddap/) reference the [ERDDAP Server](https://upwell.pfeg.noaa.gov/erddap/index.html)

* [tree\_segmentation](https://github.com/redfoxgis/tree_segmentation) ⭐ 42 | 🐛 2 | 🌐 R | 📅 2020-01-26 - LiDAR tree segmentation `R`

* [rHarmonics](https://github.com/MBalthasar/rHarmonics) ⭐ 29 | 🐛 0 | 🌐 R | 📅 2020-08-21 - `R` package for harmonic modelling of time-series data

* [cognition-datasources](https://github.com/geospatial-jeff/cognition-datasources) ⭐ 19 | 🐛 4 | 🌐 Python | 📅 2021-03-25 - Standardized query interface for searching geospatial assets via STAC.

* [caliver](https://github.com/ecmwf/caliver) ⭐ 18 | 🐛 2 | 🌐 R | 📅 2022-02-21 - caliver: CALIbration and VERification of gridded fire danger models `R`

* [Landsat\_land\_surface\_temperature](https://github.com/alyssakullberg/Landsat_land_surface_temperature) ⭐ 10 | 🐛 0 | 🌐 R | 📅 2022-11-03 - `R` Estimate land surface temperature using Landsat satellite imagery.

* [UAV-InvasiveSpp](https://github.com/JavierLopatin/UAV-InvasiveSpp) ⭐ 8 | 🐛 0 | 🌐 R | 📅 2019-02-13 - Mapping invasive tree species in Chile using UAV `R`

* [Spatial\_Data\_in\_R](https://github.com/joheisig/Spatial_Data_in_R) ⭐ 7 | 🐛 1 | 🌐 R | 📅 2019-03-27 - SWIRL-course on spatial data in `R`

* [Grassland-Species-Classification](https://github.com/JavierLopatin/Grassland-Species-Classification) ⭐ 5 | 🐛 0 | 🌐 R | 📅 2018-04-05 - Codes for: Javier Lopatin, Fabian E. Fassnacht, Teja Kattenborn, Sebastian Schmidtlein. Mapping plant species in mixed grassland communities using close range imaging spectroscopy. Remote Sensing of Environment 201, 12-23. `R`

* [Living England Project](https://github.com/naturalengland/Living_England) ⭐ 5 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-01-27 - Sharing workflows created by the Living England project, Natural England. Predominantly in `R`

* [Peatland-carbon-stock](https://github.com/JavierLopatin/Peatland-carbon-stock) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2019-06-10 - Codes for: Lopatin, J., et al. (2019). Using aboveground vegetation attributes as proxies for mapping peatland belowground carbon stocks. Remote Sens. Environ. 231, 111217 `R`

* [SpeciesRichness-GLMvsRF-LiDAR](https://github.com/JavierLopatin/SpeciesRichness-GLMvsRF-LiDAR) ⭐ 4 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-01-04 - `R`-codes for: Lopatin, J., Dolos, K., Hernández, J., Galleguillos, M., Fassnacht, F. E. (2016): Comparing Generalized Linear Models and random forest to model vascular plant species richness using LiDAR data in a natural forest in central Chile. Remote Sensing of Environment 173, pp. 200–210. 10.1016/j.rse.2015.11.029

* [clip\_time\_series](https://github.com/lecrabe/clip_time_series) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2017-08-10 - create snippets of Landsat and Sentinel imagery

* [swdt](https://github.com/be-marc/swdt) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2018-11-06 - Sentinel-1 Water Dynamics Toolkit `R`

* [R-Spatial](https://rspatial.org/raster/rs/1-introduction.html) - This book provides a short introduction to satellite data analysis with R.
  * [Remote Sensing analysis with R](https://rspatial.org/raster/rs/index.html) - Builds on above R-Spatial

* [R code for ML in Sat imagery](https://gist.github.com/franzalex/a95e227cab9b146a6092) - # Random Forest image classification Adapted from [stackoverflow](http://gis.stackexchange.com/a/57786/12899).

* [RasterVIS](https://cran.r-project.org/web/packages/rasterVis/index.html) - Methods for enhanced visualization and interaction with raster data. It implements visualization methods for quantitative data and categorical data, both for univariate and multivariate rasters. It also provides methods to display spatiotemporal rasters, and vector fields.

* [Landsat](https://cran.r-project.org/web/packages/landsat/index.html) - Processing of Landsat or other multispectral satellite imagery. Includes relative normalization, image-based radiometric correction, and topographic correction options.

* [A Step-by-Step Guide to Making 3D Maps with Satellite Imagery in R](https://www.tylermw.com/a-step-by-step-guide-to-making-3d-maps-with-satellite-imagery-in-r/) - Walk you through \[on] how to obtain the data required to make these types of maps, as well as the R code used to generate them

* [RStoolbox](https://bleutner.github.io/RStoolbox/) - RStoolbox is a R package providing a wide range of tools for your every-day remote sensing processing needs.

* [What\_are\_data\_cubes](https://edzer.github.io/UseR2020/#What_are_data_cubes) - Analyzing and visualising spatial and spatiotemporal data cubes - Part I

* [classifying\_satellite\_imagery\_in\_R](https://urbanspatial.github.io/classifying_satellite_imagery_in_R/) - For this tutorial, we use Landsat 8 imagery from Calgary

## Languages other than `Python` and `R`

* [Worldview](https://github.com/nasa-gibs/worldview) ⭐ 1,672 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-28 - Interactive interface for browsing global, full-resolution satellite imagery `Javascript` application [here](https://worldview.earthdata.nasa.gov/)
* [PDAL](https://github.com/PDAL/PDAL) ⭐ 1,404 | 🐛 132 | 🌐 C++ | 📅 2026-08-28 - PDAL is Point Data Abstraction Library. GDAL for point cloud data.
* [EO Browser Custom Scripts](https://github.com/sentinel-hub/custom-scripts) ⭐ 702 | 🐛 13 | 🌐 JavaScript | 📅 2026-08-13 - A repository of custom scripts to be used with Sentinel Hub `JavaScript`
* [stac-browser](https://github.com/radiantearth/stac-browser) ⭐ 412 | 🐛 81 | 🌐 JavaScript | 📅 2026-08-27 - A Vue-based STAC browser intended for static + dynamic deployment
* [GDAL with GoLang](https://github.com/lukeroth/gdal) ⭐ 319 | 🐛 27 | 🌐 Go | 📅 2026-05-31 - `Go` (golang) wrapper for GDAL, the Geospatial Data Abstraction Library
* [Global Forest Watch](https://github.com/Vizzuality/gfw) ⭐ 319 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-28 - Global Forest Watch: An online, global, near-real time forest monitoring tool
* [s1tbx](https://github.com/senbox-org/s1tbx) ⚠️ Archived - The Sentinel-1 Toolbox - `Java`
* [snap\_engine](https://github.com/senbox-org/snap-engine) ⭐ 213 | 🐛 21 | 🌐 Java | 📅 2026-08-26 - ESA Earth Observation Toolbox and `Java` Development Platform
* [force](https://github.com/davidfrantz/force) ⭐ 199 | 🐛 18 | 🌐 C | 📅 2026-08-27 - Framework for Operational Radiometric Correction for Environmental monitoring in `c`
* [RSGLib](https://github.com/remotesensinginfo/rsgislib) ⭐ 175 | 🐛 6 | 🌐 C++ | 📅 2026-06-18 - The remote sensing and GIS software library (RSGISLib) is a set of `C++` libraries and commands for the processing of spatial data (raster and vector). Functionality is via `Python` interface though
* [iris](https://github.com/ESA-PhiLab/iris) ⭐ 168 | 🐛 17 | 🌐 JavaScript | 📅 2026-02-06 - Semi-automatic tool for manual segmentation of multi-spectral and geo-spatial imagery. `Javascript`
* [ArchGDAL - Julia](https://github.com/yeesian/ArchGDAL.jl) ⭐ 150 | 🐛 95 | 🌐 Julia | 📅 2026-08-28 - `Julia` A high level API for GDAL - Geospatial Data Abstract
  * [ArchGDAL docs](http://yeesian.com/ArchGDAL.jl/latest/)
* [C++ gdalcubes](https://github.com/appelmar/gdalcubes) ⭐ 131 | 🐛 36 | 🌐 C++ | 📅 2026-05-29 - Earth observation data cubes from GDAL image collections `C++`
* [s2tbx](https://github.com/senbox-org/s2tbx) ⭐ 102 | 🐛 9 | 🌐 Java | 📅 2025-04-17 - Sentinel 2 Toolbox (s2tbx) - `Java`
* [Julia\_Geospatial](https://github.com/acgeospatial/Julia_Geospatial) ⭐ 68 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-12-19 - Examples for a blog series on Geospatial `Julia` using ArchGDAL
* [resto](https://github.com/jjrom/resto) ⭐ 61 | 🐛 6 | 🌐 PHP | 📅 2026-07-31 - A metadata catalog and search engine for geospatialized data `PHP` Stac!
* [sentinelhub-js](https://github.com/sentinel-hub/sentinelhub-js) ⭐ 58 | 🐛 26 | 🌐 TypeScript | 📅 2026-06-18 - Download and process satellite imagery in `JavaScript` or `TypeScript` using Sentinel Hub services.
* [staccato](https://github.com/planetlabs/staccato) ⭐ 55 | 🐛 9 | 🌐 Java | 📅 2023-07-05 - `Java` implementation of the STAC spec
* [landsat\_preprocess](https://github.com/ceholden/landsat_preprocess) ⚠️ Archived - IPython notebook documenting a workflow for preprocessing Landsat data `Shell`
* [s3tbx](https://github.com/senbox-org/s3tbx) ⭐ 49 | 🐛 8 | 🌐 Java | 📅 2025-04-17 - A toolbox for the OLCI and SLSTR instruments on board of ESA's Sentinel-3 satellite - `Java`
* [Fmask](https://github.com/GERSL/Fmask) ⭐ 27 | 🐛 3 | 🌐 Python | 📅 2026-08-27 - The software called Fmask (Function of mask) is used for automated clouds, cloud shadows, and snow masking for Landsats 4-8 and Sentinel 2 images. `Matlab`
* [stac-mode-validator](https://github.com/m-mohr/stac-node-validator) ⭐ 21 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-22 - Simple proof-of-concept to validate STAC Items, Catalogs, Collections and core extensions with node. `JavaScript`
* [tiffhax](https://github.com/emilyselwood/tiffhax) ⭐ 20 | 🐛 1 | 🌐 Go | 📅 2020-06-18 - tiff metadata hex viewer `Go`
* [stac4s](https://github.com/azavea/stac4s) ⭐ 17 | 🐛 29 | 🌐 Scala | 📅 2026-07-19 -a `scala` library with primitives to build applications using the SpatioTemporal Asset Catalogs specification
* [aiforearth-landcover-app](https://github.com/vannizhang/aiforearth-landcover-app) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2018-05-24 - web mapping app to test, tweak and train the land cover classification from a deep neural network model
* [LLR-landTrendr](https://github.com/jdbcode/LLR-LandTrendr) ⭐ 11 | 🐛 1 | 🌐 IDL | 📅 2016-07-20 - Landsat-based Detection of Trends in Disturbance and Recovery algorimth modified to accept LandsatLinkr-processed imagery. `IDL`
* [conda recipes](https://github.com/yannforget/conda-recipes) ⭐ 8 | 🐛 2 | 🌐 Shell | 📅 2017-04-07 - Conda recipes for remote sensing `Shell`
* [Landsat-solar-elevation](https://github.com/jdbcode/landsat-solar-elevation) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2017-08-09 - A web app that plots annual solar elevation at the time of Landsat overpass for locations throughout the earth `JavaScript`
* [Georust](https://github.com/georust) - A collection of geospatial tools and libraries written in `Rust`
* [GeoTrellis homepage](https://geotrellis.io/) - GeoTrellis is a geographic data processing engine for high performance applications. `Scala`
  * [GeoTrellis on Github - Scala](https://github.com/locationtech/geotrellis) ⭐ 1,372 | 🐛 250 | 🌐 Scala | 📅 2026-08-11
* [Perl extension for GDAL](https://metacpan.org/pod/Geo::GDAL) - Geo:: GDAL - `Perl` extension for the GDAL library for geospatial data
* [Orfeo ToolBox](https://gitlab.orfeo-toolbox.org/orfeotoolbox/otb) (OTB)- An open-source project for state-of-the-art remote sensing, including a fast image viewer, apps callable from `Bash`, `Python` or QGIS, and a powerful `C++` API.
* [pktools](http://pktools.nongnu.org/html/index.html) - pktools is a suite of utilities written in `C++` for image processing with a focus on remote sensing applications. It relies on the Geospatial Data Abstraction Library ([GDAL](http://www.gdal.org)) and OGR.

## Training and learning

* [Open Geo Tutorial V2](https://github.com/patrickcgray/open-geo-tutorial) ⭐ 334 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-05-24 - Tutorial of fundamental remote sensing and GIS methodologies using open source software in `Python`
* [Open Geo Tutorial V1](https://github.com/ceholden/open-geo-tutorial) ⭐ 265 | 🐛 5 | 🌐 HTML | 📅 2019-08-10 - Tutorial of basic remote sensing and GIS methodologies using open source software (GDAL in `Python` or `R`)
* [pyGIS](https://github.com/mmann1123/pyGIS) ⭐ 197 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2026-08-20 - pyGIS is an online textbook covering all the core geospatial functionality available in `Python`. This includes handling vector and raster data, satellite remote sensing, machine learning and deep learning applications
* [Earth Data Lab](https://github.com/earthlab/earthlab.github.io) ⭐ 101 | 🐛 13 | 🌐 HTML | 📅 2025-07-21 - A site dedicated to tutorials, course and other learning materials and resources developed by the Earth Lab team
* [sentinel](https://github.com/techforspace/sentinel) ⭐ 80 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2017-06-12 - Repository created for the Earth Observation Sentinel project (use with SNAP) `Python`
* [profLewis-geog0111](https://github.com/profLewis/geog0111) ⭐ 28 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2020-06-08 - UCL Geography: 4th year course, Scientific Computing
* [training-workshop](https://github.com/planetlabs/training-workshop) ⭐ 14 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2024-06-24 - This repo contains all materials used on Planet's training workshop for Bahrain Defense Force
* [Foss4gUKJupyter](https://github.com/samfranklin/foss4guk19-jupyter) ⭐ 8 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-08-01 - FOSS4G UK 2019 Workshop "Geoprocessing with Jupyter Notebooks"
* [EO College Github](https://github.com/EO-College)
  * [tomography\_tutorial](https://github.com/EO-College/tomography_tutorial) ⭐ 132 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2023-03-27 - A tutorial for Synthetic Aperture Radar Tomography
* [Intro to Geospatial Vector and Raster](https://carpentries-incubator.github.io/geospatial-python/) - Data Carpentry’s aim is to teach researchers basic concepts, skills, and tools for working with data so that they can get more done in less time, and with less pain.
* [Andrew Cutts Github](https://github.com/acgeospatial) - I am an Earth Observation and Geospatial enthusiast, primarily using `Python` to automate and process images at scale using computer vision
  * [Satellite Imagery Python](https://github.com/acgeospatial/Satellite_Imagery_Python) ⭐ 207 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-05-03 - Sample sample scripts and notebooks on processing satellite imagery
  * [Geospatial Python Programming Course](https://github.com/acgeospatial/Geospatial_Python_CourseV1) ⭐ 87 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-01-03 - This is an collection of blog posts turned into a course format
* [Geoprocessing with Python - GIS circa 2009](https://www.gis.usu.edu/~chrisg/python/2009/) - This material is really old and some of it is outdated (not all, though!). One of these days I might get around to putting newer class materials online, but you're stuck with this for now.
* [Python for Geospatial Analysis](https://www.tomasbeuzen.com/python-for-geospatial-analysis/README.html) - A crashcourse introduction to using Python to wrangle, plot, and model geospatial data `Python`
* [Hackweek - 2025](https://pacehackweek.github.io/pace-2025/presentations/notebooks.html) - PACE Data Hackweek

## Deep learning and Machine Learning

* [Segment-geospatial](https://github.com/opengeos/segment-geospatial) ⭐ 4,125 | 🐛 6 | 🌐 Python | 📅 2026-08-24 - A `Python` package for segmenting geospatial data with the Segment Anything Model (SAM). [docs](https://samgeo.gishub.org/)
* [future learn course - artificial intelligence for earth monitoring](https://www.futurelearn.com/courses/artificial-intelligence-for-earth-monitoring)

#### Curated lists

[Robin Cole on satellite imagery and deep learning resources](https://github.com/robmarkcole/satellite-image-deep-learning) ⭐ 10,241 | 🐛 1 | 📅 2026-08-02 - Resources for deep learning with satellite & aerial imagery. <b>This is the best place to go for this topic</b> I've removed 95% of the associated links from awesome-eo-code as it is just a repetition.

* [awesome-satellite-imagery-datasets](https://github.com/chrieke/awesome-satellite-imagery-datasets) ⚠️ Archived - List of satellite image training datasets with annotations for computer vision and deep learning. `ARCHIVED REPO`
* [Deep Vector](https://github.com/deepVector/geospatial-machine-learning) ⭐ 707 | 🐛 1 | 📅 2018-06-21 - A curated list of resources focused on Machine Learning in Geospatial Data Science.

#### Labelling

* [satellite-imagery-labeling-tool](https://github.com/microsoft/satellite-imagery-labeling-tool) ⭐ 295 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2025-10-15 - This is a lightweight web-interface for creating and sharing vector annotations over satellite/aerial imagery scenes.

#### AI - LLM's - Copilots - GeoAI

* [Earth-Copilot](https://github.com/microsoft/Earth-Copilot/) ⭐ 187 | 🐛 7 | 🌐 Python | 📅 2026-08-11 - An AI powered geospatial application that allows you to explore and visualize Earth science data using natural language.

## GDAL of course

* [GDAL Cheat Sheet](https://github.com/dwtkns/gdal-cheat-sheet) ⭐ 1,223 | 🐛 5 | 📅 2024-06-13 - Cheat sheet for GDAL/OGR command-line tools
* [loam](https://github.com/azavea/loam) ⭐ 226 | 🐛 18 | 🌐 JavaScript | 📅 2023-11-09 - `Javascript` wrapper for GDAL in the browser
* [mrf](https://github.com/nasa-gibs/mrf) ⭐ 89 | 🐛 12 | 🌐 Python | 📅 2026-07-07 - GDAL-compatible file format driver designed for fast access to imagery
* [docker-base-gdal](https://github.com/perrygeo/docker-gdal-base) ⭐ 60 | 🐛 1 | 🌐 Dockerfile | 📅 2022-12-23 - A base docker image for geospatial applications
* [GDAL / OGR cookbook](https://pcjericks.github.io/py-gdalogr-cookbook/) - This cookbook has simple code snippets on how to use the Python GDAL/OGR API
* [GDAL tutorial](https://jakobmiksch.eu/post/gdal_ogr/) - This blogpost gives in an introduction to GDAL/OGR and explains how the various command line tools can be used.
* [An Introduction to GDAL](https://www.youtube.com/watch?v=N_dmiQI1s24) - An Introduction to GDAL - Robert Simmon
* [A Gentle Introduction to GDAL prt 1](https://medium.com/planet-stories/a-gentle-introduction-to-gdal-part-1-a3253eb96082) - command line working
* [A Gentel Introduction to GDAL prt 2](https://medium.com/planet-stories/a-gentle-introduction-to-gdal-part-2-map-projections-gdalwarp-e05173bd710a) - Map Projections
* [A Gentel Introduction to GDAL prt 3](https://medium.com/planet-stories/a-gentle-introduction-to-gdal-part-3-geodesy-local-map-projections-794c6ff675ca) - Geodesy
* [A Gentel Introduction to GDAL prt 4](https://medium.com/planet-stories/a-gentle-introduction-to-gdal-part-4-working-with-satellite-data-d3835b5e2971) - Working with Satellite Data
* [A Gentel Introduction to GDAL prt 5](https://medium.com/@robsimmon/a-gentle-introduction-to-gdal-part-5-shaded-relief-ec29601db654) - Shaded Relief
* [A Gentel Introduction to GDAL prt 6](https://medium.com/@robsimmon/a-gentle-introduction-to-gdal-part-6-1-visualizing-data-8e6e7d6ef641) - Visualizing Data
* [A Gentel Introduction to GDAL prt 7](https://medium.com/@robsimmon/a-gentle-introduction-to-gdal-part-7-transforming-data-178df8640dd2) - Transforming Data
* [A Gentel Introduction to GDAL prt 8](https://medium.com/@robsimmon/a-gentle-introduction-to-gdal-part-8-reading-scientific-data-formats-1a1f70d5388c) - Reading Scientific Data Formats
* [A Gentel Introduction to GDAL prt 9](https://medium.com/@robsimmon/a-gentle-introduction-to-gdal-part-9-automation-with-bash-46a13c51faa5) - Automation with Bash
* [A Gentel Introduction to GDAL prt 10](https://medium.com/@robsimmon/a-gentle-introduction-to-gdal-part-10-python-the-command-line-d38e89d28636) - Python & the Command Line

## Earth Observation coding on YouTube

(presenters listed where possible)<br>
There are many videos relating to Earth Observation and coding, especially Python. This is really such a small collection of videos here. I have attempted to only include ones with good audio and code examples.

* [xArray at PyConUK2018 - Robin Wilson](https://www.youtube.com/watch?v=Dgr_d8iEWk4) - Processing thousands of satellite images to understand air quality in the UK - it's efficient and easy with XArray
* [Visualizing & Analyzing Earth Science Data Using PyViz & PyData - Julia Signell](https://youtu.be/-XMXNmGRk5c?t=455) - In this talk, we'll work through some specific workflows and explore how various tools - such as Intake, Dask, Xarray, and Datashader - can be used to effectively analyze and visualize these data. Working from within the notebook, we'll iteratively build a product that is interactive, scalable, and deployable.
* [Hands on Satellite Imagery 2019 edition - Sara Safavi](https://www.youtube.com/watch?v=j15MryznWn4) - In this tutorial, gain hands-on experience exploring Planet’s publicly-available satellite imagery and using Python tools for geospatial and time-series analysis of medium- and high-resolution imagery data. Using free & open source libraries, learn how to perform foundational imagery analysis techniques and apply these techniques to real satellite data.
* [Python from space - Katherine Scott](https://www.youtube.com/watch?v=rUUgLsspTZA\&t) - In this talk we will work through a jupyter notebook that covers the satellite data ecosystem and the python tools that can be used to sift through and analyze that data. Topics include python tools for using Open Street Maps data, the Geospatial Data Abstraction Library (GDAL), and OpenCV and NumPy for image processing.
* [Remote Sening with Python in Jupyter](https://www.youtube.com/watch?v=OsgZSlv4t-U) - In this video we're looking at using Google Earth Engine in Jupyter with the Python API.
* [Writing Image Processing Algorithms with ArcGIS/ArcPy - Jamie Drisdelle](https://www.youtube.com/watch?v=FenT61l-xyQ) - learn how your algorithms can integrate with the raster processing and visualization pipelines in ArcGIS. We’ll demonstrate the concept and discuss the API by diving deep into a few interesting examples with a special focus on multidimensional scientific rasters.
* [Google Earth Engine Python - Qiusheng Wu](https://www.youtube.com/playlist?list=PLAxJ4-o7ZoPccOFv1dCwvGI6TYnirRTg3) - Introducing the geemap Python package for interactive mapping with Google Earth Engine and ipyleaflet.
* [Google Earth Engine EE101 Condensed - Noel Gorelick](https://www.youtube.com/watch?v=m1ejxSi3l8s) - Introduction to the Earth Engine API and a conceptual overview of key functionality such as compositing, reducing, mapping, zonal statistics and cluminating with building a small app.
* [Image classification with RandomForests using the R language](https://www.youtube.com/watch?v=fal4Jj81uMA)In this video I show how to import a Landsat image into R and how to extract pixel data to train and fit a RandomForests model. I also explain how to conduct image classification and how to speed it up through parallel processing.
* [GeoPython 2019 stream](https://www.youtube.com/watch?v=3KRYObqpMlk) - 17:23 Machine Learning for Land Use/Landcover Statistics of Switzerland (Adrian Meyer), 50:58 How to structure geodata, 1:18:13 Terrain segmentation with label bootstrapping for lidar datasets, case of doline detection (Rok Mihevc), 2:34:41 Bias in machine learning, 3:06:23 Software for planning research aircraft missions (Reimar Bauer), 3:32:38 How Technology Moves Fast (PJ Hagerty) , 5:02:05 Spotting Sharks with the TensorFlow Object Detection API (Andrew Carter), 5:40:23 Center for Open Source Data and AI Technologies (CODAIT), 6:03:40 Bayesian modeling with spatial data using PyMC3 (Shreya Khurana) (Sound at 6:04:23 ^^), 7:02:45 Understanding and Implementing Generative Adversarial Networks(GANs) (Anmol Krishan Sachdeva), 7:37:00 Messaging with Satellites from Anywhere on the Planet (Andrew Carter), 8:04:52 Automation of the definition and optimizatino of census sampling areas using AREA (GRID3) (Freja Hunt), 8:35:26 Coastline Mapping with Python, Satellite Imagery and Computer Vision (Rachel Keay)
* [Google Earth Engine in QGIS](https://www.youtube.com/playlist?list=PL8jLygUmAosykCyE-5Pr6zpcB_UqnbFiZ) - This playlist looks at the GEE plugin for QGIS
* [Handling and analysing vector and raster data cubes with R](https://www.youtube.com/watch?v=9by7zsGms40) - Edzer Pebesma (Institute for Geoinformatics, University of Münster) Summary: vector and raster data cubes include vector and raster data as special cases, but extend this to vector time series, OD matrices, multi-band raster data, multi-band raster time series, multi-attribute vector or raster time series, and more general to array data where one ore more dimensions are associated with space and/or with time. Examples come from pretty much all areas dealing with spatiotemporal data. This tutorial will go through a large number of examples to illustrate this idea, mostly focusing on the packages stars and sf and those supporting their classes (like tmap, mapview, gstat, ggplot2).
* [QiushengWu's youtube](https://www.youtube.com/c/QiushengWu) - This youtube channel has pretty much everything you need Earth Engine, git, colab, Python, Geoscience. Highest quality stuff.
* [The OpenDataCube Conference 2021](https://www.youtube.com/playlist?list=PLlZzWSPAR5GbGTRR68XDKPonOL8dOyYB5) - Playlist from the 2021 conference
* [Dask and Geopandas](https://www.youtube.com/watch?v=ZpA9jgSqAkk) - Scalable geospatial data analysis with Dask| Dask Summit 2021

## Earth Engine

`JavaScript` & `Python` & `R`

Best to start here [Awesome\_GEE](https://github.com/giswqs/Awesome-GEE) ⭐ 1,238 | 🐛 0 | 📅 2026-08-27 - A curated list of Google Earth Engine resources.

* [GEE Map](https://github.com/giswqs/geemap) ⭐ 4,019 | 🐛 54 | 🌐 Python | 📅 2026-08-27 - A Python package for interactive mapping with Google Earth Engine, ipyleaflet, and ipywidgets
* [Earth Engine API](https://github.com/google/earthengine-api) ⭐ 3,403 | 🐛 21 | 🌐 JavaScript | 📅 2026-08-24 - `Python` and `JavaScript` bindings for calling the Earth Engine API.
* [Python GEE notebooks](https://github.com/giswqs/earthengine-py-notebooks) ⭐ 1,554 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2021-03-16 - A collection of 360+ Jupyter Python notebook examples for using Google Earth Engine with interactive mapping
* [rgee](https://github.com/r-spatial/rgee) ⭐ 777 | 🐛 63 | 🌐 R | 📅 2026-08-24 - Google Earth Engine for `R` [docs](https://csaybar.github.io/rgee/)
* [crop\_yield\_prediction](https://github.com/JiaxuanYou/crop_yield_prediction) ⭐ 421 | 🐛 11 | 🌐 Python | 📅 2023-05-27 - Crop Yield Prediction with Deep Learning with GEE
* [ee-palettes](https://github.com/gee-community/ee-palettes) ⭐ 343 | 🐛 2 | 🌐 HTML | 📅 2020-09-23 - A set of common color palettes for Google Earth Engine
* [geetools](https://github.com/fitoprincipe/geetools-code-editor) ⭐ 323 | 🐛 9 | 📅 2023-10-02 - A set of tools to use in Google Earth Engine Code Editor `JavaScript` [docs](https://github.com/fitoprincipe/geetools-code-editor/wiki) ⭐ 323 | 🐛 9 | 📅 2023-10-02
* [EEwPython](https://github.com/csaybar/EEwPython) ⭐ 287 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2024-06-23 - A series of Jupyter notebook to learn Google Earth Engine with `Python`
* [gee-up](https://github.com/samapriya/geeup) ⭐ 140 | 🐛 0 | 🌐 Python | 📅 2025-12-31 - Simple CLI for Google Earth Engine Uploads [docs](https://pypi.org/project/geeup/)
* [geeguide](https://github.com/ndminhhus/geeguide) ⭐ 136 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2021-06-29 - Harmonization of Landsat and Sentinel 2 in Google Earth Engine, documentation and scripts
* [ee-jupyter-examples](https://github.com/tylere/ee-jupyter-examples) ⭐ 88 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2017-03-31 - Example Jupyter Notebooks, including ones that use the Earth Engine `Python` API
* [geebap](https://github.com/fitoprincipe/geebap) ⭐ 86 | 🐛 2 | 🌐 Python | 📅 2024-05-30 - Best Available Pixel (BAP) composite in Google Earth Engine (GEE) using the `Python` API
* [gee\_asset\_manager](https://github.com/samapriya/gee_asset_manager_addon) ⭐ 80 | 🐛 3 | 🌐 Python | 📅 2026-01-06 - Google Earth Engine Asset Manager with Addons [docs](https://samapriya.github.io/gee_asset_manager_addon/)
* [ee-tensorflow-notebooks](https://github.com/gee-community/ee-tensorflow-notebooks) ⭐ 76 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2020-04-01 - Repository to place example notebooks for Deep Learning applications with TensorFlow and Earth Engine.
* [Best Available Pixel](https://github.com/saveriofrancini/bap) ⭐ 64 | 🐛 0 | 🌐 JavaScript | 📅 2023-11-23 - Best Available Pixel calculation using Google Earth Engine `Javascript`
* [radiometric-slope-correction](https://github.com/ESA-PhiLab/radiometric-slope-correction) ⚠️ Archived - Radiometric Slope Correction of Sentinel-1 data on Google Earth Engine
* [Planet-GEE\_Pipeline](https://github.com/samapriya/Planet-GEE-Pipeline-CLI) ⭐ 42 | 🐛 3 | 🌐 Python | 📅 2023-05-12 -Planet and Google Earth Engine Pipeline Command Line Interface Tool [docs](https://pypi.org/project/ppipe/)
* [GoogleEarthEngine-side-projects](https://github.com/chrieke/GoogleEarthEngine-side-projects) ⭐ 28 | 🐛 0 | 🌐 JavaScript | 📅 2020-12-27 - Google Earth Engine side projects and tutorial scripts `JavaScript`
* [global-river-ice-dataset-from-landsat](https://github.com/seanyx/global-river-ice-dataset-from-Landsat) ⭐ 28 | 🐛 0 | 🌐 JavaScript | 📅 2019-12-30 - `Python` (Google Earth Engine), `JavaScript` (Google Earth Engine) and `R` code to extract river ice condition from Landsat satellites, to develop empirical model, and to predict future changes in river ice
* [GEE code archive](https://github.com/gena/ee-code-editor-archive) ⭐ 23 | 🐛 0 | 🌐 JavaScript | 📅 2022-09-03 - Unsorted archived Earth Engine scripts `JavaScript`
* [HMS-Smoke](https://github.com/tianjialiu/HMS-Smoke) ⭐ 21 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-06 - HMS Smoke Explorer: To visualize NOAA's Hazard Mapping System (HMS) smoke product `Javascript`
* [Ecuador\_SEPAL](https://github.com/sig-gis/Ecuador_SEPAL) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2020-06-26 - processing script for Sentinel-2 and Landsat-8
* [GoogleEarthEngine](https://github.com/evan-delancey/GoogleEarthEngine) ⭐ 12 | 🐛 1 | 🌐 JavaScript | 📅 2018-07-18 - forestry related work
* [remote-sensing-resistance](https://github.com/mikoontz/remote-sensing-resistance) ⭐ 11 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2021-01-08 - Does heterogeneity in forest structure make a forest resistant to wildfire?
* [jupyterlab-ee](https://github.com/tylere/jupyterlab-ee) ⭐ 11 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2017-11-21 - Experiments related to getting JupyterLab and Earth Engine to work together. `Python`
* [cloud frequency app](https://github.com/robintw/CloudFrequencyApp) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2018-04-29 - CloudFrequency webapp, using Google App Engine `Python` `JavaScript`
* [Building\_Identification\_Damage\_Assessment](https://github.com/welkinland/Building_Identification_Damage_Assessment) ⭐ 6 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-09-21 - Building Extraction and Damage Assessment from High Resolution Multi-spectral Images `Python`
* [geecrop](https://github.com/profLewis/geecrop) ⭐ 2 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-05-14 - Earth Engine-based crop information
* [GEE\_Functions](https://github.com/JavierLopatin/GEE_Functions) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2019-06-19 - A set of functions to work in Google Engine `Javascript`
* [Fire\_Pattern\_Analysis\_CONUS](https://github.com/welkinland/Fire_Pattern_Analysis_CONUS) ⭐ 1 | 🐛 0 | 🌐 HTML | 📅 2020-09-21 - Analysis of fire patterns and drivers in CONUS `Python`
* [ox\_gee\_tutorial](https://github.com/tommylees112/ox_gee_tutorial) ⭐ 0 | 🐛 0 | 📅 2019-11-15 - Oxford MSc Introduction to Hydrological Applications in Google Earth Engine
* [EE-Examples](https://github.com/gorelick/EE-Examples) ⭐ 0 | 🐛 0 | 📅 2017-02-07 - `Javascript` some (old?) example scripts from Noel Gorelick - lead author [Google Earth Engine: Planetary-scale geospatial analysis for everyone](https://www.sciencedirect.com/science/article/pii/S0034425717302900)
* [from GEE to Numpy to Geotiff](https://mygeoblog.com/2017/10/06/from-gee-to-numpy-to-geotiff/) - Use the GEE python api to export your data to numpy and store the result as a geotiff.
* [Google Earth Engine Community](https://github.com/gee-community) - This organization contains content contributed by the Earth Engine developer community. This is not an officially supported Google product.
* [Geo4Good 2019 workshop materials](https://sites.google.com/earthoutreach.org/geoforgood19/agenda/breakout-sessions) - 2019 material javascript and Python to be found here
* [2018 GEE summit - Dublin materials](https://sites.google.com/earthoutreach.org/eeus2018/agenda/session-descriptions) - 2018 material javascript and Python to be found here
* [10 tips for becoming an Earth Engine expert](https://medium.com/google-earth/10-tips-for-becoming-an-earth-engine-expert-b11aad9e598b) - Keiko Nomura shares her 10 favourite tips
* [Earth Engine Developer list](https://groups.google.com/forum/#!forum/google-earth-engine-developers) - registration required
* [Earth Engine Beginner's Cookbook](https://developers.google.com/earth-engine/tutorials/community/beginners-cookbook) - n this tutorial, we will introduce several types of geospatial data, and enumerate key Earth Engine functions for analyzing and visualizing them. This cookbook was originally created as a workshop during Yale-NUS Data 2.0 hackathon, and later updated for Yale GIS Day 2018 and 2019. `JavaScript`
* [Google Earth Engine Repos](https://github.com/topics/earth-engine) - all the repos matching `earth-engine`

## Open Data Cube

* [Digital Earth Australia Notebooks](https://github.com/GeoscienceAustralia/dea-notebooks) ⭐ 535 | 🐛 47 | 🌐 Jupyter Notebook | 📅 2026-08-28 - Repository for Jupyter Notebooks, tools and workflows for continental-scale earth observation/geospatial analysis with Open Data Cube and `xarray` `Python`
* [geocube](https://github.com/corteva/geocube) ⭐ 381 | 🐛 8 | 🌐 Python | 📅 2026-07-20 - Tool to convert geopandas vector data into rasterized xarray data `Python`
* [Digital Earth Africa Sandbox Notebooks](https://github.com/digitalearthafrica/deafrica-sandbox-notebooks) ⭐ 238 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2026-08-28 - Extra documentation about using ODC with Jupyter Notebooks with DE Africa-specific examples `xarray` `Python`
* [ODC STAC](https://github.com/opendatacube/odc-stac) ⭐ 202 | 🐛 16 | 🌐 Python | 📅 2026-07-29 - A stand-alone Python library that allows the loading of STAC Items into an ODC-compatible Xarray `xarray` `Python`
* [odc-tools](https://github.com/opendatacube/odc-tools) ⭐ 64 | 🐛 40 | 🌐 Python | 📅 2026-08-26 - ODC features that DEA is experimenting with or prototyping with the intention of being integrated into odc-core in the future
* [datacube-explorer](https://github.com/opendatacube/datacube-explorer) ⭐ 64 | 🐛 48 | 🌐 JavaScript | 📅 2026-08-28 - Web-based exploration of Open Data Cube collections
* [dea-coastlines](https://github.com/GeoscienceAustralia/dea-coastlines) ⭐ 64 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2026-07-24 - Extracting tidally-constrained annual shorelines and robust rates of coastal change from freely available Earth observation data at continental scale
* [data\_cube\_notebooks](https://github.com/ceos-seo/data_cube_notebooks) ⭐ 55 | 🐛 34 | 🌐 Jupyter Notebook | 📅 2023-10-06 - Jupyter Notebook examples for our Data Cube capable algorithms and functions `Python`
* [openeo\_odc\_driver](https://github.com/SARScripts/openeo_odc_driver) ⭐ 11 | 🐛 7 | 🌐 Python | 📅 2024-10-08 - OpenEO processing engine written in `Python` based on OpenDataCube, `Xarray` and `Dask`.
* [odc-sh](https://github.com/sentinel-hub/odc-sh) ⭐ 3 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-05-31 - Sentinel Hub plugin for Open data cube
* [Opendatacube](https://github.com/opendatacube)
  * [Datacube Core](https://github.com/opendatacube/datacube-core) ⭐ 585 | 🐛 83 | 🌐 Python | 📅 2026-08-28 - Open Data Cube analyses continental scale Earth Observation data through time `Python` `xarray`
  * [Datacube OWS](https://github.com/opendatacube/datacube-ows) ⭐ 85 | 🐛 37 | 🌐 Python | 📅 2026-08-24 - Open web services for the Open Data Cube. Supports WMS, WMTS and WCS for any dataset indexed into the ODC `Python`

## Other Datacube-related Python

* [Google Earth Engine Python examples](https://github.com/renelikestacos/Google-Earth-Engine-Python-Examples) ⭐ 327 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-04-08 - Various examples for Google Earth Engine in `Python` using Jupyter Notebook
* [stackstac](https://github.com/gjoseph92/stackstac) ⭐ 270 | 🐛 60 | 🌐 Python | 📅 2024-08-10 - Turn a STAC catalog into a dask-based xarray `Python`

## Planetary Computer

* [Mircosoft PlanetaryComputer](https://github.com/microsoft/PlanetaryComputer) ⭐ 207 | 🐛 80 | 📅 2024-11-19 - Issues, discussions, and information about the Microsoft Planetary Computer
  * [PlanetaryComputerExamples](https://github.com/microsoft/PlanetaryComputerExamples) ⭐ 455 | 🐛 34 | 🌐 Jupyter Notebook | 📅 2026-08-14 - Examples of using the Planetary Computer `Python`
  * [planetary-computer-apis](https://github.com/microsoft/planetary-computer-apis) ⭐ 129 | 🐛 33 | 🌐 Python | 📅 2026-08-24
  * [sdk-python](https://github.com/microsoft/planetary-computer-sdk-for-python) ⭐ 85 | 🐛 10 | 🌐 Python | 📅 2025-05-28 - Planetary Computer SDK for `Python`
  * [PlanetaryComputerDataCatalog](https://github.com/microsoft/PlanetaryComputerDataCatalog) ⭐ 46 | 🐛 30 | 🌐 TypeScript | 📅 2026-08-14 - Data catalog for the Microsoft Planetary Computer [website](https://planetarycomputer.microsoft.com/)
  * [reading-stac](https://planetarycomputer.microsoft.com/docs/quickstarts/reading-stac/) - Reading Data from the STAC API
* [Sentinel2 on planetary computer](https://github.com/Element84/geo-notebooks/blob/main/notebooks/odc-planetary-computer.ipynb) ⭐ 67 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-04-06 - notebook explores Sentinel-2 data on Microsoft's Planetary Computer `Python`
* [hottest panchayats kerala](https://github.com/shijithpk/hottest-panchayats-kerala) ⭐ 11 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-02-24 - Figuring out what the hottest villages in Kerala are with the help of Microsoft's Planetary Computer. `Python`
* [planetary-computer-deep-dives](https://github.com/TomAugspurger/planetary-computer-deep-dives) ⭐ 7 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-11-16 - `Python`
* [gmv planetary computer S2 alerts](https://github.com/globalmangrovewatch/gmw_planetary_computer_s2_alerts) ⭐ 6 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-05-18 - Repo with the code producing the GMW alerts using the Microsoft Planetary Computer `Python`
* [satio-pc](https://github.com/dzanaga/satio-pc) ⭐ 5 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-04-11 - Compute Sentinel features on Planetary Computer `Python`

## QGIS and Grass

* [grass-dev-py3-pdal](https://github.com/OSGeo/grass/tree/master/docker) ⭐ 1,154 | 🐛 703 | 🌐 C | 📅 2026-08-28 - Dockerfile which compiles GRASS GIS 7.9 master with Python 3 and PDAL suppor
* [Qgis Earth Engine Plugin](https://github.com/gee-community/qgis-earthengine-plugin) ⭐ 513 | 🐛 16 | 🌐 Python | 📅 2026-08-25 - Integrates Google Earth Engine and QGIS using Python API
  * [QGIS Earth Engine Plugin - installation guide](https://gee-community.github.io/qgis-earthengine-plugin/)
* [NASA Earthdata QGIS Plugin](https://github.com/opengeos/qgis-nasa-earthdata-plugin) ⭐ 82 | 🐛 3 | 🌐 Python | 📅 2026-07-20 - A QGIS plugin for searching and visualizing NASA Earthdata
* [TSTools - archived](https://github.com/ceholden/TSTools) ⚠️ Archived - QGIS2 plugin tools for remote sensing timeseries `Python`
* [qgis-plugin-planet](https://github.com/planetlabs/qgis-planet-plugin) ⭐ 53 | 🐛 30 | 🌐 Python | 📅 2026-04-03 - Browse, filter, preview and download Planet Inc imagery in QGIS. `Python`
* [OpenEO QGIS Plugin](https://openeo.org/documentation/1.0/qgis/) - The openEO QGIS plugin enables exploring openEO backends including batch jobs, collections, and web services within QGIS

## Climate and weather based resources

These are `Python` resources. Please see [R resources](#resources-for-r) for info on R

* [MetPy](https://github.com/Unidata/MetPy) ⭐ 1,437 | 🐛 375 | 🌐 Python | 📅 2026-08-24 - MetPy is a collection of tools in Python for reading, visualizing and performing calculations with weather data. `Python`
  * [aqua-monitor](https://github.com/Deltares/aqua-monitor) ⭐ 60 | 🐛 43 | 🌐 JavaScript | 📅 2025-04-08 - Monitoring surface water changes from space at global scale. Also checkout the [app](https://aqua-monitor.appspot.com/) `Python`
  * [MetPy docs](https://unidata.github.io/MetPy/latest/)`Python`
* [Climate data science](https://github.com/willyhagi/climate-data-science) ⚠️ Archived - Climate Data Science and Earth Observation with `Python`
* [eumetsat -python](https://github.com/guidocioni/eumetsat-python) ⚠️ Archived - Shows how to read and plot satellite data from EUMETSAT NETCDF files `Python`
* [s3 tools](https://github.com/maximlamare/s3_tools) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2019-03-06 - A collection of sentinel 3 processing tools `Python`
* [eumetsat](https://github.com/openclimatefix/eumetsat) ⚠️ Archived - Tools for downloading and processing satellite images from EUMETSAT
* [Ocean Color - Modis](https://github.com/JackieVeatch/ocean_color) ⭐ 4 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-12-13 - introduction to accessing and plotting ocean color satellite data from MODIS `Python`
* [coda\_eumetsat](https://github.com/nicolaerosca/coda_eumetsat) ⚠️ Archived - Coda Eumetsat (coda.eumetsat.int) client for downloading data
* [COST-EUMETSAT-Training](https://github.com/gher-ulg/COST-EUMETSAT-Training) ⭐ 2 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-02-08 - Material, data and presentations for the COST-EUMETSAT training school
* [unidata on GOES-16](https://unidata.github.io/python-gallery/examples/mapping_GOES16_TrueColor.html) - This notebook shows how to make a true color image from the GOES-16 Advanced Baseline Imager (ABI) level 2 data. We will plot the image with matplotlib and Cartopy.`Python`
* [ai4eo-forecast](https://gitlab.com/Pablo-DBG/ai4eo-forecast) - Developing an open source library to compare Earth Observation and weather forecast services with the actual measurements and assess the accuracy of the forescast `Python`

### EUMETlab

Such a vast collection of resources that it warrants a sub section within Climate and weather based resources

* [EUMETlab](https://gitlab.eumetsat.int/eumetlab) - This page contains groups of code repositories that have been made open to the public by EUMETSAT and our collaborators.
  * [atmosphere](https://gitlab.eumetsat.int/eumetlab/atmosphere/atmosphere) - LTPy - Learning tool for Python on Atmospheric Composition Data is a Python-based training course on Atmospheric Composition Data. The training course covers modules on data access, handling and processing, visualisation as well as case studies.
  * [sentinel-downloader](https://gitlab.eumetsat.int/eumetlab/cross-cutting-tools/sentinel-downloader) - Python-based Sentinel satellite data downloader. This script allows for batch downloading of Sentinel data selected by various criteria include date, location, sensor, child products, flags and more.
  * [olci-iop-processor](https://gitlab.eumetsat.int/eumetlab/oceans/ocean-science-studies/olci-iop-processor) - Code to produce Inherent Optical Properties from Level-2 OLCI data.

## DEM projects

* [Tin Terrain](https://github.com/heremaps/tin-terrain) ⚠️ Archived - A command-line tool for converting heightmaps in GeoTIFF format into tiled optimized meshes.
* [DEM.net](https://github.com/dem-net/DEM.Net) ⭐ 354 | 🐛 18 | 🌐 C# | 📅 2026-04-18 - Digital Elevation model library in C#. 3D terrain models, line/point Elevations, intervisibility reports. [Docs](https://elevationapi.com/)
* [TauDEM](https://github.com/dtarb/TauDEM) ⭐ 275 | 🐛 94 | 🌐 C++ | 📅 2026-07-24 - Terrain Analysis Using Digital Elevation Models (TauDEM) software for hydrologic terrain analysis and channel network extraction. [Docs](http://hydrology.usu.edu/taudem/taudem5/index.html)
* [Stereo Mapping to create Elevation with Python](https://github.com/cmla/s2p) ⭐ 264 | 🐛 32 | 🌐 Python | 📅 2025-10-17 - Satellite Stereo Pipeline
* [dsm2dtm](https://github.com/seedlit/dsm2dtm) ⭐ 64 | 🐛 0 | 🌐 Python | 📅 2026-05-10 - Python library for converting Digital Surface Models (DSMs) to Digital Terrain Models (DTMs).
* [DSM2DTM](https://github.com/mprakhar/DSM2DTM) ⭐ 17 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2019-04-23 - Code for the paper - Comparison of Digital Building Height Models Extracted from AW3D, TanDEM-X, ASTER, and SRTM Digital Surface Models over Yangon City `Python`
* [The Stereo Pipeline (NASA)](https://ti.arc.nasa.gov/tech/asr/groups/intelligent-robotics/ngt/stereo/) - The NASA Ames Stereo Pipeline (ASP) is a suite of free and open source automated geodesy and stereogrammetry tools designed for processing stereo imagery captured from satellites

## SAR

* [pyroSAR](https://github.com/johntruckenbrodt/pyroSAR) ⭐ 612 | 🐛 46 | 🌐 Python | 📅 2026-08-28 - framework for large-scale SAR satellite data processing
* [sarsen](https://github.com/bopen/sarsen) ⭐ 317 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2026-08-26 - Algorithms and utilities for Synthetic Aperture Radar (SAR) sensors
* [RITSAR](https://github.com/dm6718/RITSAR) ⭐ 259 | 🐛 6 | 🌐 Python | 📅 2020-02-24 - Synthetic Aperture Radar (SAR) Image Processing Toolbox for `Python`
* [OpeSARToolkit](https://github.com/ESA-PhiLab/OpenSarToolkit) ⭐ 246 | 🐛 16 | 🌐 Python | 📅 2026-02-04 - High-level functionality for the inventory, download and pre-processing of Sentinel-1 data in the `python` language.
* [PyRAT](https://github.com/birgander2/PyRAT) ⭐ 226 | 🐛 10 | 🌐 Python | 📅 2025-01-16 - General purpose Synthetic Aperture Radar (SAR) postprocessing software package `Python`
* [Spacenet6 - SAR buildings](https://github.com/SpaceNetChallenge/SpaceNet_SAR_Buildings_Solutions) ⭐ 76 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2020-12-04 - The winning solutions for the SpaceNet 6 Challenge `Python`
* [sarbian](https://github.com/EO-College/sarbian) ⭐ 65 | 🐛 8 | 🌐 Shell | 📅 2019-09-04 - a plug’n play Operation System (based on Debian Linux) with all the freely and openly available SAR processing software
* [sentineldenoised](https://github.com/nansencenter/sentinel1denoised) ⭐ 53 | 🐛 15 | 🌐 Jupyter Notebook | 📅 2024-04-04 - Thermal noise subtraction, scalloping correction, angular correction `Python`
* [sea\_ice\_drift](https://github.com/nansencenter/sea_ice_drift) ⭐ 49 | 🐛 5 | 🌐 Python | 📅 2023-05-24 - Sea ice drift from Sentinel-1 SAR imagery using open source feature tracking `Python`
* [Step by step: Radar-based flood mapping with Python](https://un-spider.org/advisory-support/recommended-practices/recommended-practice-flood-mapping/python-step-by-step) and [github link](https://github.com/UN-SPIDER/radar-based-flood-mapping) ⭐ 44 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-02-21 - This repository contains a Jupyter Notebook for automatic flood extent mapping using space-based information. `Python`
* [S1\_NRB](https://github.com/SAR-ARD/S1_NRB) ⭐ 34 | 🐛 26 | 🌐 Python | 📅 2026-04-21 - A prototype processor for the Sentinel-1 Normalised Radar Backscatter product.
* [STAC Sentinel1](https://github.com/stactools-packages/sentinel1) ⭐ 31 | 🐛 7 | 🌐 Python | 📅 2025-05-13 - stactools package for working with sentinel1 data `Python`
* [SAR docker](https://github.com/mortcanty/SARDocker) ⭐ 29 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2016-12-16 - Source files for Docker image mort/sardocker/
* [S1\_ARD](https://github.com/johntruckenbrodt/S1_ARD) ⭐ 21 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-01-18 - repository for testing analysis-readiness of Sentinel-1 RTC backscatter `Python`
* [PySAR](https://github.com/bminchew/PySAR) ⭐ 20 | 🐛 1 | 🌐 C++ | 📅 2016-12-22 - PyAR is a perpetually incomplete, general-purpose toolbox for common post-processing tasks involving synthetic aperture radar (SAR).`Python` `C++`
* [infrastructure](https://github.com/ESA-PhiLab/infrastructure) ⚠️ Archived - Mapping and monitoring of infrastructure in desert regions with Sentinel-1
* [sentinel1-opds](https://github.com/earthobservatory/sentinel1-opds) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2021-02-04 - sentinel1-opds ingestion `Python`
* [s1prepro](https://github.com/benjimin/s1prepro) ⭐ 14 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2018-05-29 - Automated pre-processing of Sentinel 1 (satellite radar imagery) `Python`
* [sentinel1-Biodiversity](https://github.com/So-YeonBae/Sentinel1-Biodiversity) ⭐ 12 | 🐛 0 | 🌐 R | 📅 2021-09-15 - Code, example dataset, and instructions of Sentinel-1 data pre-processing and pixel-based summary statistics used in "Radar vision for mapping forest biodiversity from space" `Python`
* [awesome SAR](https://github.com/lveci/awesome-sar) ⭐ 11 | 🐛 0 | 📅 2016-07-11 - A curated list of awesome Synthetic Aperture Radar (SAR) software, libraries, and resources.
* [rice\_sentinel1](https://github.com/AndrewPham9/rice_sentinel1) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2020-03-23 - classify rice from sentinel 1 data `Python`
* [OST\_Notebook](https://github.com/ESA-PhiLab/OST_Notebooks) - The notebooks within this repository provide getting started tutorials for the use of the Open SAR Toolkit, found here in the ESA-philab github channel.

## LiDAR

* [Lidar](https://github.com/giswqs/lidar) ⭐ 301 | 🐛 9 | 🌐 Python | 📅 2026-05-25 - Terrain and hydrological analysis based on LiDAR-derived digital elevation models (DEM)
* [IcePyx](https://github.com/icesat2py/icepyx) ⭐ 258 | 🐛 113 | 🌐 Python | 📅 2026-08-24 - Python tools for obtaining and working with ICESat-2 data
* [usgs-lidar](https://github.com/hobu/usgs-lidar) ⭐ 172 | 🐛 31 | 🌐 JavaScript | 📅 2026-08-28 - AWS Entwine Point Tiles USGS LiDAR Public Dataset GitHub repo
* [ICESAT tools](https://github.com/icesat-2UT/PhoREAL) ⭐ 103 | 🐛 11 | 🌐 Python | 📅 2025-02-26 - Tools and code for Icesat-2 data analysis (Python)
* [ICESAT extraction script](https://gist.github.com/bzgeo/950f3db986b3513311ed42efe2395171) - Python script to convert from ICESat-2 ATL08 HDF data to shapefile. Usage: 'python icesat2\_shp.py

### GEDI

* [rGEDI](https://github.com/carlos-alberto-silva/rGEDI) ⭐ 184 | 🐛 1 | 🌐 R | 📅 2026-03-27 - rGEDI: An R Package for NASA's Global Ecosystem Dynamics Investigation (GEDI) Data Visualization and Processing.
* [gedi-tutorials](https://github.com/ornldaac/gedi_tutorials) ⭐ 132 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-07-23 - GEDI L3 and L4 Tutorials
* [pyGEDI](https://github.com/EduinHSERNA/pyGEDI) ⭐ 109 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2022-07-17 - pyGEDI is a Python Package for NASA's Global Ecosystem Dynamics Investigation (GEDI) mission, data extraction, analysis, processing and visualization.
* [pysl4land](https://github.com/remotesensinginfo/pysl4land) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2023-01-23 - `Python` tools to process spaceborne lidar (GEDI and ICESAT2) for land (pySL4Land) applications
* [q\_research](https://github.com/HeatherKmtb/q_research) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2022-02-04 - For processing of ICESat GLAS, GEDI and ICESat-2 LiDAR data, to derive q parameter for canopy height to density relationship `Python`
* [gedi](https://github.com/rodolfolotte/gedi) ⭐ 4 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-08-19 - `Python` tutorial to process and handle LiDAR GIDE datasets
* [GEDI\_Yucatan](https://github.com/JohMast/GEDI_Yucatan) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2021-01-08 - Supplementary material for the study: Space Lidar for Archaeology? Reanalyzing GEDI Data for Detection of Ancient Maya Buildings `R`
* [sprnca\_gedi](https://github.com/rbavery/sprnca_gedi) ⭐ 3 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2020-04-12 - WIP to map Foliage Height Diversity along the San Pedro Riparian Corridor with NASA's GEDI Lidar `Python`
* [GEDI extraction script](https://gist.github.com/KMarkert/c68ccf53260d7b775b836bf2e11e2ec3) - Python script to take GEDI level 2 data and convert variables to a geospatial vector format

## InSAR

* [MintPy](https://github.com/insarlab/MintPy) ⭐ 829 | 🐛 67 | 🌐 Python | 📅 2026-08-24 - Miami InSAR time-series software in Python
* [isce2](https://github.com/isce-framework/isce2) ⭐ 662 | 🐛 253 | 🌐 Python | 📅 2026-06-30 - InSAR Scientific Computing Environment version 2 `Python`
* [LiCSBAS](https://github.com/yumorishita/LiCSBAS) ⭐ 283 | 🐛 4 | 🌐 Python | 📅 2024-11-29 - LiCSBAS package to carry out InSAR time series analysis using LiCSAR products
* [ISCE](https://github.com/isce-framework/isce3) ⭐ 232 | 🐛 164 | 🌐 Python | 📅 2026-08-25 - InSAR Scientific Computing Environment version 3 alpha
* [PyRate](https://github.com/GeoscienceAustralia/PyRate) ⚠️ Archived - A Python tool for estimating velocity and time-series from Interferometric Synthetic Aperture Radar (InSAR) data.
* [snap2stamps](https://github.com/mdelgadoblasco/snap2stamps) ⭐ 127 | 🐛 6 | 🌐 Python | 📅 2026-01-13 - Using SNAP as InSAR processor for StaMPS
* [ARIRA-tools](https://github.com/aria-tools/ARIA-tools) ⭐ 124 | 🐛 13 | 🌐 Python | 📅 2026-08-18 - Tools for exploiting ARIA standard products `Python`
* [InSARFlow](https://github.com/levuvietphong/InSARFlow) ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2022-07-25 - Parallel InSAR processing for Time-series analysis
* [ROI\_PAC-Sentinel1](https://github.com/RaphaelGrandin/ROI_PAC-Sentinel1) ⭐ 51 | 🐛 0 | 🌐 Shell | 📅 2017-12-17 - InSAR processing of Sentinel-1 using ROI\_PAC
* [insar\_scripts](https://github.com/scottyhq/insar_scripts) ⭐ 24 | 🐛 0 | 🌐 Perl | 📅 2014-08-29 - Useful scripts for working with roipac data `Python`
* [ISCE\_utils](https://github.com/EJFielding/ISCE_utils) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2019-05-09 - Small utility scripts for working with InSAR Scientific Computing Environment (ISCE) products `Python`
* [Pyrocko](https://pyrocko.org/) - Can be utilized flexibly for a variety of geophysical tasks, like seismological data processing and analysis, modelling of InSAR, GPS data and dynamic waveforms, or for seismic source characterization.

## Landuse

* [demeter](https://github.com/JGCRI/demeter) ⭐ 34 | 🐛 10 | 🌐 HTML | 📅 2026-01-21 - A land use land cover disaggregation and change detection model  `Python`

## Visualisation

* [Greppo](https://github.com/greppo-io/greppo) ⭐ 420 | 🐛 36 | 🌐 Python | 📅 2023-03-07 - Python framework for building geospatial web-applications
* [Tree height and canopy cover map in 3D](https://github.com/nkeikon/GEDI-experiment) ⭐ 7 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-04-19 - Use Kepler.gl to visualise 3D and 2D data
* [Video map](https://github.com/openearth/videomap) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2022-12-26 - Tools to create, , export and share video maps
* [Tiled video!](http://gena.github.io/experiments/mapbox/debug/tiled-video-no2.html)

## Regular blogs of significant interest or posts of interest

* [Philipp Gartner blog](https://philippgaertner.github.io/)
* [Series Temporelles](https://labo.obs-mip.fr/multitemp/)
* [The downlinq](https://medium.com/the-downlinq)
* [GEDI canopy data](https://medium.com/@abt0020/extracting-canopy-height-with-gedi-data-5af8c87df158) - How we processed data to retrieving canopy height
* [spectral reflectance](https://www.spectralreflectance.space/) - weeking substack on EO news

## EO code Competitions

* [challenges 2020](https://github.com/esowc/challenges_2020) ⭐ 49 | 🐛 0 | 📅 2021-05-03 - ECMWF Summer of Weather Code 2020 challenges
* [challenges 2021](https://github.com/esowc/challenges_2021) ⭐ 44 | 🐛 9 | 📅 2021-10-16 - ECMWF Summer of Weather Code 2021 challenges
* [drivendataorg - cloud-cover-winners](https://github.com/drivendataorg/cloud-cover-winners) ⭐ 25 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-08-24 - Code from the winning submissions for the On Cloud N: Cloud Cover Detection Challenge
* [AtmosHack2018](https://github.com/wekeo/AtmosHack2018) ⭐ 6 | 🐛 0 | 📅 2018-11-14 - Contains information and resources for Copernicus Hackathon 2018 in Helsinki
* [Julia Wagemann github](https://github.com/jwagemann) - Making open meteorological and climate data better accessible. `Python`, `Jupyter` and `R`.
* See also [Sentinel hub competitions](https://www.sentinel-hub.com/develop/community/contest/) <br><i>'older' competitions of note</i></br>
* [Planet: Understanding the Amazon from Space](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/overview) - Use satellite data to track the human footprint in the Amazon rainforest
* [DeepGlobe Building Extraction Challenge](https://competitions.codalab.org/competitions/18544) - We would like to pose the challenge of automatically detecting buildings from satellite images.
* [DSTL feature extraction](https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection) - Kagglers are challenged to accurately classify features in overhead imagery
* [crowdAI misisng maps challenge](https://www.aicrowd.com/challenges/mapping-challenge) - Building Missing Maps with Machine Learning
  * [openAI solution](https://github.com/neptune-ai/open-solution-mapping-challenge) ⭐ 387 | 🐛 55 | 🌐 Python | 📅 2021-03-22 - Open solution to the Mapping Challenge

## ARD links

* [S1\_S2\_ARD\_code\_list](https://github.com/jncc/s1-s2-ard-code-list) ⭐ 22 | 🐛 0 | 🌐 HTML | 📅 2022-07-13 - A curated list supporting the use of Sentinel-1 and Sentinel-2 analysis-ready data (ARD) via application programming interface (API)

## Useful EO code based twitter accounts

* [pyGEDI](https://twitter.com/pyGEDI) - pyGEDI is a Python Package for NASA's Global Ecosystem Dynamics Investigation (GEDI) mission, data extraction, analysis, processing and visualization.

## Great Github accounts

Please do explore these accounts, there are some absolutely brilliant projects on these accounts. This was previously a section containing examples, but these are better grouped into the other headings and repitition of links removed. However I feel its very important to highlight individuals wherever possible, ordered by github account name.

\| [Chis Holden](https://github.com/ceholden) | [Christoph Rieke](https://github.com/chrieke) | [gena](https://github.com/gena) | [jgomezdans](https://github.com/jgomezdans) - [blog](http://jgomezdans.github.io/) | [Johntruckhenbrodt](https://github.com/johntruckenbrodt) | [Marcus Netler](https://github.com/neteler) | [Oliverhagolle](https://github.com/olivierhagolle) | [PerryGeo](https://github.com/perrygeo) | [giswqs - Qiusheng Wu](https://github.com/giswqs) | [rhammell](https://github.com/rhammell) | [Remote pixel](https://github.com/RemotePixel) | [robintw](https://github.com/robintw) | [Evan Roualt](https://github.com/rouault) | [samapriya](https://github.com/samapriya) | [shakasom](https://github.com/shakasom) | [yannforget](https://github.com/yannforget) | [Pete Bunting](https://github.com/petebunting) | [Vincent Sarago](https://github.com/vincentsarago) |

## EO Geospatial companies or orgs making big contributions

Github accounts only with examples of work. This section used to contain examples of work, these have been now regrouped into other sections to make them easier to find.

\| [development seed](https://github.com/developmentseed) | [mapbox](https://github.com/mapbox) | [Planet Labs, now just Planet](https://github.com/planetlabs) | [Digital Globe - now Maxar](https://github.com/DigitalGlobe) | [Azavea](https://github.com/azavea) | [Radiant Earth foundation](https://github.com/radiantearth) | [Sentinel Hub](https://github.com/sentinel-hub) | [PyTroll](https://github.com/pytroll) | [CosmiQ](https://github.com/CosmiQ) | [Theia software and tools](https://www.theia-land.fr/en/softwares-and-tools/) | [sparkgeo](https://github.com/sparkgeo) | [Geoscience Australia](https://github.com/GeoscienceAustralia) | [Dymaxion Labs](https://github.com/dymaxionlabs) | [Satellogic](https://github.com/satellogic) | [senbox-org](https://github.com/senbox-org) | [Nasa-gibs](https://github.com/nasa-gibs) | [mundialis](https://github.com/mundialis) | [ESA\_PhiLab](https://github.com/ESA-PhiLab) | [Element 84](https://github.com/Element84)

## Interesting Non EO parts Python

This bit could potentially become the most valuable resource. Lets not ignore other sectors/industries/data science, instead lets embrace it and learn from all that other amazing stuff! This my prelude to saying we are earth data scientists

* [Deep learning with Python notebooks](https://github.com/fchollet/deep-learning-with-python-notebooks) ⭐ 20,278 | 🐛 217 | 🌐 Jupyter Notebook | 📅 2025-09-18 - Jupyter notebooks for the code samples of the book "Deep Learning with Python"
* [Awesome Semantic Segmentation](https://github.com/mrgloom/awesome-semantic-segmentation) ⭐ 10,847 | 🐛 17 | 📅 2021-05-08 - awesome-semantic-segmentation
* [Change your Jupyter Theme](https://github.com/dunovank/jupyter-themes) ⭐ 9,818 | 🐛 205 | 🌐 CSS | 📅 2025-06-22 - Custom Jupyter Notebook Themes
* [introduction to ml with Python](https://github.com/amueller/introduction_to_ml_with_python) ⭐ 8,164 | 🐛 28 | 🌐 Jupyter Notebook | 📅 2024-03-14 - Notebooks and code for the book "Introduction to Machine Learning with `Python`"
* [Xarray](https://github.com/pydata/xarray) ⭐ 4,191 | 🐛 1,423 | 🌐 Python | 📅 2026-08-28 - N-D labeled arrays and datasets in Python
* [dtreeviz](https://github.com/parrt/dtreeviz) ⭐ 3,155 | 🐛 75 | 🌐 Jupyter Notebook | 📅 2026-01-02 - A `Python` library for decision tree visualization and model interpretation.
* [realtime covid19 graphs in USA](https://github.com/k-sys/covid-19) ⭐ 1,361 | 🐛 43 | 🌐 Jupyter Notebook | 📅 2020-09-22 - A collection of work related to COVID-19
* [TernausNet - used in DSTL kaggle competition (came 3rd)](https://github.com/ternaus/TernausNet) ⭐ 1,063 | 🐛 10 | 🌐 Python | 📅 2022-10-26 - UNet model with VGG11 encoder pre-trained on Kaggle Carvana dataset
* [GeoStats, Resources](https://github.com/GeostatsGuy/Resources/blob/master/README.md) ⭐ 396 | 🐛 0 | 📅 2025-08-27 - Geostatistics
* [Introduction to Python for computational science](https://github.com/fangohr/introduction-to-python-for-computational-science-and-engineering) ⭐ 391 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2024-04-14 - Book: Introduction to Python for Computational Science and Engineering
* [Python\_tips](https://github.com/gpetepg/python_tips) ⭐ 157 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-08-24 - Some Python tips for beginner to intermediate users. Also used as a personal cheat sheet.
* [GDSL-UL/Teaching\_Links](https://github.com/GDSL-UL/Teaching_Links) ⭐ 125 | 🐛 1 | 📅 2022-05-19 - In this repo we have aimed to provide links to useful teaching resources for teaching Geographic / Spatial Data Science, GIS and Statistics. (perhaps misplaced in this list?)
* [Classification-Algorithm](https://github.com/usmanr149/Classification-Algorithm) ⭐ 2 | 🐛 5 | 🌐 HTML | 📅 2022-11-22 - Classification algorithm workshop for WiMLDS `Python`
* [Python data science handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
* [A-Z of tips and tricks for Python](https://www.freecodecamp.org/news/an-a-z-of-useful-python-tricks-b467524ee747/) - 'Most of these ‘tricks’ are things I’ve used or stumbled upon during my day-to-day work. '
* [Visual intro into Numpy](https://jalammar.github.io/visual-numpy/)- Visualizing machine learning one concept at a time
* [unidata Python workshop](https://unidata.github.io/python-training/workshop/workshop-intro/) - Would you like some in-depth training on the scientific Python ecosystem for atmospheric science and meteorology? Work through our workshop materials at your own pace to learn and practice the syntax, functionality, and utility of this powerful programming language, or return to the material after taking the workshop in-person to further your understanding of the material you were taught.
* [Another Book on Data Science](https://www.anotherbookondatascience.com/) - Learn R and Python in Parallel
* [Matplotlib colab notebook tutorial](https://colab.research.google.com/github/ageron/handson-ml2/blob/master/tools_matplotlib.ipynb#scrollTo=gG7Fh4EMV2ey) - This notebook demonstrates how to use the matplotlib library to plot beautiful graphs.
* [PostGIS raster cheatsheet](http://www.postgis.us/downloads/postgis20_raster_cheatsheet.pdf) - Useful tips on rasters in PostGIS
* [65 data science books on Springer](https://towardsdatascience.com/springer-has-released-65-machine-learning-and-data-books-for-free-961f8181f189) - not checked but perhaps useful
* [Intro to Numerical Computing - youtube](https://www.youtube.com/watch?v=V0D2mhVt7NE) - Intro to Numerical Computing with NumPy (Beginner) | SciPy 2018 Tutorial | Alex Chabot-Leclerc
* [Matplotlib\_Cheatsheet](https://nbviewer.jupyter.org/urls/gist.githubusercontent.com/Jwink3101/e6b57eba3beca4b05ec146d9e38fc839/raw/f486ca3dcad44c33fc4e7ddedc1f83b82c02b492/Matplotlib_Cheatsheet) - Matplotlib\_Cheatsheet `Python`
* [practical-python](https://dabeaz-course.github.io/practical-python/) - Practical Python Programming A course by @dabeaz

## Interesting Non EO parts other languages

This section is aimed more a data science/programming resources that 'might' be applicable to Earth Observation, that are <b>not </b>Python

* [Efficient R programming](https://csgillespie.github.io/efficientR/) - This is the online version of the O’Reilly book: Efficient R programming. Code is [here](https://github.com/csgillespie/efficientR) ⭐ 737 | 🐛 33 | 🌐 TeX | 📅 2025-02-27

## Data

I don't really want to add many data resources to this list as it creeps out of scope but this part contains some good data links \[not necessarily EO]

* [Environmental\_Intelligence](https://github.com/rockita/Environmental_Intelligence) ⭐ 301 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2022-12-28 - Data for Environmental Intelligence: A mega list of Earth System Datasets covering earth observations, climate, water, forests, biodiversity, ecology, protected areas, natural hazards, marine and the tracking of UN's Sustainable Development Goals
* [gibs](https://earthdata.nasa.gov/eosdis/science-system-description/eosdis-components/gibs) - This is EO
* [awesome-gee-community-datasets](https://samapriya.github.io/awesome-gee-community-datasets/) - Community Datasets added by users and made available for use at large

## A footnote on awesome

There are many awesome lists relating to 'Geo'. I use that term as widely as possible. This list is not meant to replace these lists. Earth Observation is still <b>way</b> behind the GIS world in terms of audience, reach, number of users etc. Things are changing though, by bringing these links together I hope you can see that there has been so much progress in the last 5 years. I do hope these links are helpful espcially to those who are new to Earth Observation, but also to people like me who with several years of experience think they may have seen it all - we haven't and there is still so much to learn. Earth Observation is not just an academic 'thing' or a basemap anymore, it forms the basis for a growing and diverse business environment. Lets embrace this.

Finally, I wanted to acknowledge a couple of awesome Earth Observation lists that you may list to check out:

* [awesome-Geospatial](https://github.com/sacridini/Awesome-Geospatial) ⭐ 5,271 | 🐛 1 | 📅 2026-08-28 - Long list of geospatial tools and resources
* [awesome-remote-sensing-change-detection](https://github.com/wenhwu/awesome-remote-sensing-change-detection) ⭐ 2,313 | 🐛 2 | 📅 2026-04-16 - List of datasets, codes, and contests related to remote sensing change detection.
* [Awesome Geospatial Companies](https://github.com/chrieke/awesome-geospatial-companies) ⭐ 888 | 🐛 5 | 🌐 Python | 📅 2026-07-09 - List of 500+ geospatial companies (GIS, Earth Observation, UAV, Satellite, Digital Farming, ..)
* [Awesome Sentinel](https://github.com/Fernerkundung/awesome-sentinel) ⭐ 583 | 🐛 3 | 📅 2025-02-20 - curated list of awesome tools, tutorials and APIs for Copernicus Sentinel satellite data
* [awesome-remote-sensing](https://github.com/attibalazs/awesome-remote-sensing) ⭐ 114 | 🐛 3 | 📅 2026-01-18 - Collection of Remote Sensing Resources

#### End

[![CC BY 1.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 1.0 International License][cc-by].

[![CC BY 1.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/1.0/

[cc-by-image]: https://i.creativecommons.org/l/by/1.0/88x31.png

[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%201.0-lightgrey

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
