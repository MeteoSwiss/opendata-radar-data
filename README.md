[MeteoSwiss - Open Data](https://github.com/MeteoSwiss/opendata/blob/main/README.md) > [Understanding MeteoSwiss' Open Data products](https://github.com/MeteoSwiss/opendata/blob/main/README.md#understanding-meteoswiss-open-data-products) > D. Radar Data

# D. Radar Data
MeteoSwiss operates a [network of five weather radar stations](https://www.meteoswiss.admin.ch/weather/measurement-systems/atmosphere/weather-radar-network.html) which record every type of precipitation and storms in real time, are fully automated and, between them, cover the whole of Switzerland.

The following radar products are planned to be made available:

- D1 - Precipitation products - Radar-based, Combined
- D2 - Reflectivity-based products - ...
- D3 - Hail products - Probability of Hail, Maximum Expected Severe Hail Size
- D4 - Convection Products - ...
- D5 - Polar 3D Products - ...

<!--
**Precipitation Products**
- D1 - [Radar-based Precipitation](#d1---radar-based-precipitation) *PRECIP --> Basic Radar (Web)*
- D2 - [Combined Precipitation](d2---combined-precipitation) *CombiPrecip --> Advanced Radar (Web)*
<!-- - D3 - RainForest Precipitation - *not yet realised* -->

**Reflectivity-based Products**
- D4 - MAX-ECHO, Echo-Top 15dB, Echo-Top 45dBZ *--> Advanced Radar (Web)*
<!-- - D5 - CAPPI 3D - *not yet realised* -->
<!-- - D6 - Reflectivity Height - *not yet realised* -->

**Hail Products**
- D7 - Probability of Hail, /with Analysis *POH --> Advanced Radar (Web)*
- D8 - Maximum Expected Severe Hail Size, /with Analysis *MESHS --> Advanced Radar (Web)*
-->

<!--
**Convection Products**
- D9 - Vertical Integrated Liquid content (VIL) - *not yet realised*
- D10 - Vertical Integrated Liquid content density (VIL-Density) - *not yet realised*
- D11 - Thunderstorm Radar Tracking (TRT) - *not yet realised*
- D12 - Mesocyclone Detection - *not yet realised*

**Polar 3D Products**
- D13 - Reflectivity, Radial Wind - *not yet realised*
- D14 - Hydrometeor Classification - *not yet realised*
- D15 - Dealiased Wind - *not yet realised*
- D16 - Vertical Wind Profile - *not yet realised*
-->

<br>

---

## D1 - Radar-based Precipitation
... 

cf. [https://github.com/MeteoSwiss/publication-opendata?tab=readme-ov-file#2621-basic-radar-data](https://github.com/MeteoSwiss/publication-opendata?tab=readme-ov-file#2621-basic-radar-data)

<br>

The coordinate system is [`Swiss LV95`](https://www.swisstopo.admin.ch/en/the-swiss-coordinates-system) / [`EPSG:2056`](https://epsg.io/2056). 

The data format is [`HDF5`](https://www.hdfgroup.org/solutions/hdf5/) with an estimated volume of ... MB per file.

<br>

The following data files are available for download:

| *Parameter*                            | *Product*                          | Time interval | Update cycle   | Data files (see STAC Assets)                                       |
|:---------------------------------------|:-----------------------------------|:------------- |:---------------|:-------------------------------------------------------------------|
| **Radar-based Precipitation**          | Instantaneus                       | 5min          | 5min           | ch.meteoswiss.ccs4r2nj:RZCyyjjjHHMM*.*01                           |

<br>

## D2 - Combined Precipitation
Combined precipitation is an [extended radar product](https://www.meteoswiss.admin.ch/services-and-publications/service/weather-and-climate-products/radard-avanced.html) combining observations from Swiss weather radars with other data, such as those obtained from the numerical weather model. *For certain meteorological phenomena, such as hail occurring in conjunction with a thunderstorm, these extended products provide more detail than the basic radar products.*

cf. [https://github.com/MeteoSwiss/publication-opendata?tab=readme-ov-file#2623-combiprecip-data](https://github.com/MeteoSwiss/publication-opendata?tab=readme-ov-file#2623-combiprecip-data)

Data visualisations see e.g. Martin Schilliger/Stadt Zürich, Schutz & Rettung's [Radar Visualisation for HDF5/NetCDF files](https://github.com/martinschilliger/Radar-Visualisation).

<br>
