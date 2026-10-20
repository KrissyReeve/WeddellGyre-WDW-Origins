# WeddellGyre-WDW-Origins
Code and analysis for 
# On the origins and transformation of Warm Deep Water within the Weddell Gyre 
Krissy A. Reeve1, C. Hancock2, and F. A. Haumann1,3

1Alfred Wegener Institute Helmholtz Centre for Polar and Marine Research, Bremerhaven, Germany.
2Department of Earth, Ocean and Atmospheric Science, Florida State University, Tallahassee, USA.
3Ludwig-Maximilians-Universität München, Munich, Germany.
Corresponding author: Krissy A. Reeve (Krissy.Anne.Reeve@gmail.com) 
Author of code:  Krissy A. Reeve (Krissy.Anne.Reeve@gmail.com) 

(Edited for sharing)

Aim: To determine what is Warm Deep Water, how does it enter the gyre, and how does the main advective pathways result in its modification and formation.
Hypothesis: The WDW is made up of both UCDW and LCDW, and is transformed from the source water masses primarily by WW. 

## Objectives:

Define UCDW as Tmax and dO2min, and LCDW as Smax: map. Do this for the gridded mean field from WOA, and for the ungridded Argo floats.
Along selected streamlines, determine the long-term mean variation of Tmax, Smax and dO2min throughout the gyre. 

## Abstract

The Weddell Gyre is a key region for returning deep water to the surface in its upwelling centre, and for the formation and transit route of Antarctic Bottom Water, thus playing a role in the closure of the southern limb of the overturning circulation, ventilating the deep ocean, and regulating the carbon budget. The main source of heat to the Weddell Gyre, however, is poorly understood, including whether Upper or Lower Circumpolar Deep Water make up the main source water mass. A lack of observations limit our understanding of the circulation pathways that advect the source waters into the gyre. Understanding the origins of Warm Deep Water is essential to understanding the impact of a changing climate system. In this study, we attempt to find clarity on these issues using a gridded annual mean product from WOA23 and ungridded Argo float data, in order to tease out what the key sources are that feed the Warm Deep Water, and how and where this process occurs. 

## Data

Gridded: WOA23 annual mean 2015-2022: 1/4° resolution for temperature and salinity, and 1° resolution grid for dissolved oxygen concentration.

Ungridded: biogeochemical Argo float data downloaded for south of 50°S and stored as a structured array where level one fields list each argo float by ['f',WMO]

WOA:
Temp: 
Dataset: woa23_B5C2_t00_04.nc
Catalog: /thredds-ocean/catalog/woa23/DATA/temperature/netcdf/B5C2/0.25/catalog.html
woa23/DATA/temperature/netcdf/B5C2/0.25/woa23_B5C2_t00_04.nc
https://www.ncei.noaa.gov/thredds-ocean/catalog/woa23/DATA/temperature/netcdf/B5C2/0.25/catalog.html?dataset=woa23/DATA/temperature/netcdf/B5C2/0.25/woa23_B5C2_t00_04.nc
Salinity:
Dataset: woa23_B5C2_s00_04.nc
Catalog: /thredds-ocean/catalog/woa23/DATA/salinity/netcdf/B5C2/0.25/catalog.html
woa23/DATA/salinity/netcdf/B5C2/0.25/woa23_B5C2_s00_04.nc
https://www.ncei.noaa.gov/thredds-ocean/catalog/woa23/DATA/salinity/netcdf/B5C2/0.25/catalog.html?dataset=woa23/DATA/salinity/netcdf/B5C2/0.25/woa23_B5C2_s00_04.nc
Oxygen (dissolved):
Dataset: woa23_all_o00_01.nc
Catalog: /thredds-ocean/catalog/woa23/DATA/oxygen/netcdf/all/1.00/catalog.html
woa23/DATA/oxygen/netcdf/all/1.00/woa23_all_o00_01.nc
https://www.ncei.noaa.gov/thredds-ocean/catalog/woa23/DATA/oxygen/netcdf/all/1.00/catalog.html?dataset=woa23/DATA/oxygen/netcdf/all/1.00/woa23_all_o00_01.nc
