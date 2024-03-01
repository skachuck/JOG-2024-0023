Antarctic ice shelf height changes and basal melt rates for 1994–2018 from satellite radar altimetry.

(Data used by Adusumilli et al., 2020, Nature Geoscience)

Code to read and process these data will be available at:
https://github.com/sioglaciology/ice_shelf_change 

The GitHub page also includes data and code necessary to reproduce Figs. 1–4 in the manuscript.

Summary
-------
We provide two new datasets of basal melt rates for all of Antarctica’s ice shelves. One dataset provides melt rates at high spatial resolution for nearly all ice shelf areas, averaged over the period 2010-2018. The second dataset allows for the evaluation of annual estimates of basal melt rates at lower resolution for the period 1994-2018. Together, these datasets reveal large variability in total meltwater fluxes from individual Antarctic ice shelves, with distinct, regionally variable, signatures of temporal variability for different modes of ocean-driven melting. Our data allow us to better isolate the glaciological and climate drivers of current ice sheet mass loss and provide improved metrics for calibration and validation of melt rates used in both ice-ocean and Earth-system models. 

Data files
----------

1) ANT_iceshelf_melt_rates_CS2_2010-2018_v0.h5
Average basal melt rates for Antarctic ice shelves for the 2010–2018 period at high spatial resolution, estimated using CryoSat-2 data. Interpolated values in regions with missing data are provided as a separate field. We are currently working on using ICESat-2 data to improve the estimates over regions with missing CryoSat-2 data.

2) ANT_iceshelf_height_changes_RA_1994_2018_v0.h5
Height changes for all Antarctic ice shelves between 1994 and 2018 from satellite radar altimetry. This file also includes all the components required to estimate changes in basal melt rates: changes in firn air content (from GSFC-FDMv0), surface mass balance (from MERRA-2) and ice dynamics (changes in ice dynamics were estimated for Amundsen Sea sector ice shelves only). 






