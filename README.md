[MeteoSwiss - Open Data](https://github.com/MeteoSwiss/opendata/blob/main/README.md) > [Understanding MeteoSwiss' Open Data products](https://github.com/MeteoSwiss/opendata/blob/main/README.md#understanding-meteoswiss-open-data-products) > D. Radar Data

# D. Radar Data
MeteoSwiss operates a [network of five weather radar stations](https://www.meteoswiss.admin.ch/weather/measurement-systems/atmosphere/weather-radar-network.html) which record every type of precipitation and storms in real time, are fully automated and, between them, cover the whole of Switzerland.

The following radar products are available:

**Precipitation Products**
- D1 - [Radar-based Precipitation](#d1---radar-based-precipitation) *PRECIP*
- D2 - [Combined Precipitation](d2---combined-precipitation) *CombiPrecip*
- D3 - RainForest Precipitation - *not yet realised*

**Reflectivity-based Products** ?
- D4 - ? *MAX-ECHO*
- D5 - ? *Echo-Top 15dBZ*
- D6 - ? *Echo-Top 45dBZ*
- D7 - CAPPI 3D - *not yet realised*
- D8 - Reflectivity Height - *not yet realised*

**Hail Products**
- D9 - *Probability of Hail* *POH*
- D10 - *Probability of Hail with Analysis* *POH*
- D11 - *Maximum Expected Severe Hail Size* *MESHS*
- D12 - *Maximum Expected Severe Hail Size with Analysis* *MESHS*

**Convection Products**
- D13 - Vertical Integrated Liquid content (VIL) - *not yet realised*
- D14 - Vertical Integrated Liquid content density (VIL-Density) - *not yet realised*
- D15 - Thunderstorm Radar Tracking (TRT) - *not yet realised*
- D16 - Mesocyclone Detection - *not yet realised*

**Polar 3D Products**
- D17 - Reflectivity, Radial Wind - *not yet realised*
- D18 - Hydrometeor Classification - *not yet realised*
- D19 - Dealiased Wind - *not yet realised*
- D20 - Vertical Wind Profile - *not yet realised*

<br>

---

## 1. Basic radar data
... 

cf. [https://github.com/MeteoSwiss/publication-opendata?tab=readme-ov-file#2621-basic-radar-data](https://github.com/MeteoSwiss/publication-opendata?tab=readme-ov-file#2621-basic-radar-data)

### Data granularity, update frequency, format and volume
There are files of [data granularity](https://github.com/MeteoSwiss/opendata-download?tab=readme-ov-file#data-granularity) `...`, `...`, `...`, `...` *and [update frequency](https://github.com/MeteoSwiss/opendata-download/blob/main/README.md#update-frequency) hourly (`now`), daily (`recent`) or yearly (`historical`) for each station*.

Data format is [`...`](...) with an estimated volume of ... MB per file.

See example data files: [`...`](...).

### Parameter metadata
*See example parameter metadata files of [data granularity](https://github.com/MeteoSwiss/opendata-download?tab=readme-ov-file#data-granularity): [`...`](...) and [`...`](...).*

<!-- ### Codes -->
<!-- ... -->

### Station metadata
*See example [station metadata file](...).*

### Data visualisation
See e.g. MeteoSwiss' [...](...).

## 2. Extended radar data
[Extended radar products](https://www.meteoswiss.admin.ch/services-and-publications/service/weather-and-climate-products/radard-avanced.html) combine observations from Swiss weather radars with other data, such as those obtained from the numerical weather model. For certain meteorological phenomena, such as hail occurring in conjunction with a thunderstorm, these extended products provide more detail than the basic radar products. ...

cf. [https://github.com/MeteoSwiss/publication-opendata?tab=readme-ov-file#2622-advanced-radar-data](https://github.com/MeteoSwiss/publication-opendata?tab=readme-ov-file#2622-advanced-radar-data)

### Data granularity, update frequency, format and volume
There are files of [data granularity](https://github.com/MeteoSwiss/opendata-download?tab=readme-ov-file#data-granularity) `...`, `...`, `...`, `...` *and [update frequency](https://github.com/MeteoSwiss/opendata-download/blob/main/README.md#update-frequency) hourly (`now`), daily (`recent`) or yearly (`historical`) for each station*.

Data format is [`...`](...) with an estimated volume of ... MB per file.

See example data files: [`...`](...).

### Parameter metadata
*See example parameter metadata files of [data granularity](https://github.com/MeteoSwiss/opendata-download?tab=readme-ov-file#data-granularity): [`...`](...) and [`...`](...).*

<!-- ### Codes -->
<!-- ... -->

### Station metadata
*See example [station metadata file](...).*

### Data visualisation
See e.g. MeteoSwiss' [...](...).

## 3. Combined precipitation calculations
... 

cf. [https://github.com/MeteoSwiss/publication-opendata?tab=readme-ov-file#2623-combiprecip-data](https://github.com/MeteoSwiss/publication-opendata?tab=readme-ov-file#2623-combiprecip-data)

### Data granularity, update frequency, format and volume
There are files of [data granularity](https://github.com/MeteoSwiss/opendata-download?tab=readme-ov-file#data-granularity) `...`, `...`, `...`, `...` *and [update frequency](https://github.com/MeteoSwiss/opendata-download/blob/main/README.md#update-frequency) hourly (`now`), daily (`recent`) or yearly (`historical`) for each station*.

Data format is [`...`](...) with an estimated volume of ... MB per file.

See example data files: [`...`](...).

### Parameter metadata
*See example parameter metadata files of [data granularity](https://github.com/MeteoSwiss/opendata-download?tab=readme-ov-file#data-granularity): [`...`](...) and [`...`](...).*

<!-- ### Codes -->
<!-- ... -->

### Station metadata
*See example [station metadata file](...).*

### Data visualisation
See e.g. MeteoSwiss' [...](...).

See e.g. Martin Schilliger/Stadt Zürich, Schutz & Rettung's [Radar Visualisation for HDF5/NetCDF files](https://github.com/martinschilliger/Radar-Visualisation).
