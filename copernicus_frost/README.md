# Risk of late frost in a warmer climate

Study conducted at the Copernicus C3S User Learning Workshop  
March 2020, Zurich, Switzerland  

Daniel Steinfeld, Tobias Steber and Joël Durand  

## Motivation:
April 2017 in Europe: after an extremely warm March and April, temperatures in the lowlands dropped well below zero degrees Celsius for several days – with damage to vegetation, fruit and vines, resulting in losses of aprox. €3.3bn.

## Risk
Frost occurence (FD) after warm period exceeding a certain amount of Growing Degree Days (GDD).

## Data
ERA-Interim and climate simulations are downloaded from the CDS Copernicus Data Store: https://cds.climate.copernicus.eu/#!/home

Agroclimatic indicators from 1981 - 2010 (historical) and 2017 - 2099 (RCP6 future scenario):
- Biologically effective degree days (GDD): Sum of daily mean temperatures (TG) above 10°C and less than 30°C, over 10 days.
- Frost Days (FD): Number of days per 10 days when TN $<$ 0°C, where TN is the daily minimum temperature. This indicator provides information on frost damage.

## Script
Python script fd_after_gdd.ipynb downloads the data and calculates/visualizes the __GDD until last FD__.


