# Data

This project uses hourly **ERA5 climate data** obtained from the Copernicus Climate Data Store.

https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels?tab=overview

The dataset covers a location in **Giza, Egypt**, from January 2000 to May 2025 and contains meteorological variables including:

* Land surface temperature
* Surface pressure
* Mean sea level pressure
* Total precipitation
* 10 m wind components

The raw dataset is not included in this repository.

The preprocessing notebook documents the transformations applied to the original data and produces the processed dataset used for model development.
