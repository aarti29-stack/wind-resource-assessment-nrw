# Wind Resource Assessment & Energy Yield Modelling – NRW

## Overview
This project develops a reproducible Python workflow to identify wind-suitable areas in Regierungsbezirk Köln (NRW) and estimate annual energy production for representative turbine locations.

## What this project does
- Identifies wind-suitable areas using official NRW geodata
- Processes multi-year DWD hourly wind data
- Extrapolates wind speeds to hub height (Hellmann method)
- Applies distance-weighted interpolation
- Estimates annual energy production using turbine power curves

## Files
- 01_spatial_site_selection.ipynb
- 02_wind_resource_modelling.ipynb

## Tools
Python, GeoPandas, Pandas, NumPy, Matplotlib
