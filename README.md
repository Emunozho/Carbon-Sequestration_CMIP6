# Supplementary data and code for the article "Tradeoffs between carbon assimilation and release reveal a key role of the tropics in long-term global-scale carbon sequestration" by E. Muñoz et al. and supervised by C. Sierra.

This repository contains code and data to reproduce all results from this publication. 
In particular, the `Data` folder contains NetCDF files with carbon sequestration (CS) calculation using outputs from a set of models participating in CMIP6, a set of models participating in TRENDY v13, CarboScope, CAMS, and X-BASE (FLUXCOM-X).
The files `CMIP6_CS_nep.nc` and `CMIP6_CS_nbp.nc` contain the CS results obtained from NEP and NBP outputs from CMIP6, respectively, computed between 1850-2014, while the files `CMIP6_CS_nep_2001-2024.nc` and `CMIP6_CS_nbp_2001-2024.nc` contain the results from the shorter period 2001-2014.
The files `TRENDY_CS_nbp_2001-2014.nc`,`CarboScope_CS_nbp_2001-2014.nc`, and `CAMS_CS_nbp_2001-2014.nc` contain the CS results from NBP outputs from TRENDY, CarboScope, and CAMS, respectively, calculated between 2001-2014. 
The files `TRENDY_CS_nep_2001-2014.nc` and `X-BASE_CS_nee_2001-2014.nc` contain the CS results from NEP (or NEE) outputs from TRENDY and XBASE, respectively, calculated 2001-2014. 

The weights to calculate the average ensembles of CMIP6 and TRENDY models are in the folder `Data/Weights` and the land mask in `landsea`.

Due to their large size, the source data from the CMIP6, TRENDY, CarboScope, CAMS, and X-BASE products are not available in this repository, but they are available at: 

CMIP6: https://cmip-data-pool.dkrz.de or at https://esgf-node.ipsl.upmc.fr/projects/cmip6-ipsl (openly available).

TRENDYv13: https://globalcarbonbudgetdata.org/closed-access-requests.html (closed access).

CarboScope nbetEXToc_v2024E: https://www.bgc-jena.mpg.de/CarboScope/?ID=nbetEXToc_v2024E (openly available).

CAMS: https://ads.atmosphere.copernicus.eu/datasets/cams-global-greenhouse-gas-inversion?tab=download (openly available).

X-BASE: https://meta.icos-cp.eu/collections/zfwf1Ak2I7OlziGDTX8Xl6_T (openly available).
