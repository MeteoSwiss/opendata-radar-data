[MeteoSwiss - Open Data](https://github.com/MeteoSwiss/opendata/blob/main/README.md) > [Understanding MeteoSwiss' Open Data products](https://github.com/MeteoSwiss/opendata/blob/main/README.md#understanding-meteoswiss-open-data-products) > D. Radar Data

# D. Radar Data
MeteoSwiss operates a network of five weather radar stations which record every type of precipitation and storms in real time, are fully automated and, between them, cover the whole of Switzerland. The sites are
- Albis near Zurich (equipped with the latest technology (dual polarisation) in 2012, monitors the atmosphere of the whole of northern Switzerland)
- Monte Lema in the Canton of Ticino (equipped with the latest technology (dual polarisation) in 2011, monitors the atmosphere of the whole of southern Switzerland)
- La Dôle near Geneva (equipped with the latest technology (dual polarisation) in 2011)
- Pointe de la Plaine Morte in the Canton of Valais (equipped with the latest technology (dual polarisation), commenced operation in 2014 and monitors the atmosphere in the inner Alpine region)
- Weissfluhgipfel in the Canton of Graubünden (equipped with the latest technology (dual polarisation), commenced operation in 2016, and monitors the atmosphere in the inner Alpine region) 

The following radar data are available:

**Precipitation Products**
- D1 - [Radar-based Precipitation](#d1---radar-based-precipitation) *PRECIP*
- D2 - [Combined Precipitation](d2---combined-precipitation) *CombiPrecip*
- D3 - RainForest Precipitation - *not yet realised*

**Reflectivity-based Products**
- D4 - *MAX-ECHO*
- D5 - *Echo-Top 15dBZ*
- D6 - *Echo-Top 45dBZ*

**Hail Products**
- D7 - *Probability of Hail* *POH*
- D8 - *Probability of Hail with Analysis* *POH*
- D9 - *Maximum Expected Severe Hail Size* *MESHS*
- D10 - *Maximum Expected Severe Hail Size with Analysis* *MESHS*
- D11 - CAPPI 3D - *not yet realised*
- D12 - Reflectivity Height - *not yet realised*

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
