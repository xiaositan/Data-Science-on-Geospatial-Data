# Data-Science-on-Geospatial-Data
## Procuring and Reading Geospatial Data
The Copernicus Data Store (CDS) is a one stop shop for a wide range of historical and real time geospatial data from various remote sensing and on-the-ground weather observations. The CDS API allows for programmatic access to this data store. This API is used to obtain the following data from the ERA5-Land Hourly Reanalysis Dataset. The section in square brackets refers to the specifics of the download - 
* Temperature of air at 2m above the surface - **[2m Temperature - 2019 - December - 12:00 - Whole Available Region - NetCDF]**
* Total precipitation - **[Total Precipitation - 2019 - December -12:00 - Whole Available Region - NetCDF]**
* Volumetric soil water layer 1 - **[Volumetric soil water layer 1 - 2019 - December - 12:00 - Whole Available Region - NetCDF]**

_Useful Links :_
* https://cds.climate.copernicus.eu/api-how-to 
* https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-land?tab=overview

## Deep Learning on Geospatial Data
The following notebook is an approach to design a neural network to predict the **[Total Precipitation]** from the two input variables **[Temperature of air at 2m above the surface, Volumetric soil water layer 1]**. 
