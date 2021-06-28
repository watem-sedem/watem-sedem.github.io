# Welcome to CN-WS

Hi there! This website holds the documentation for CN-WS and related projects. The Curve-Number/WaTEM-SEDEM (or in short **CN-WS**) is a model used to estimate erosion, water run-off and overland sediment routing and transport to river. This page links to the several packages and codes used in the CN-WS project. The project is subdivided in a number of smaller projects. The are shortly introduced in the sections below. 

## CN-WS

This project is the heart of CN-WS: it contains all algorithms and formula's orginally developed by KU Leuven in the Pascal programming language. The documentation for this project is currently under development.

## pycnws

This project is used to standerdize and automate data processing and data formatting for any catchment (applied in Flanders) for the CN-WS core code. The package makes use of [Python](https://www.python.org/) (via [conda](https://docs.conda.io/en/latest/index.html)), [SAGA-GIS](http://www.saga-gis.org/) and [GDAL](https://gdal.org/). The code and documentation for this project is currently under development.

## R-factor

In this project, code is developed to compute the rainfall erosivity (R-factor). In short, the R-factor is a factor that quantifies the effect of rainfall on water erosion. This factor is used in CN-WS to compute values for the RUSLE equation. 

- GitHub-page: https://github.com/cn-ws/rfactor
- Documentation: https://cn-ws.github.io/rfactor/index.html

## Contact

For any question considering any of these projects, please contact us at cn-ws@omgeving.vlaanderen.be.

## Powered by

![image](_static/png/DepartementOmgeving_logo.png)

![image](_static/png/KULeuven_logo.png)

![image](_static/png/VMM_logo.png)

![image](_static/png/fluves_logo.png)


