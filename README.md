# access-om2_postprocessing
Postprocessing scripts for ocean heat/salt budget analyses of ACCESS-OM2 output

Fabio Boeira Dias - University of Tasmania/CSIRO

Routines were created and used as part of my PhD project (2015-2019), and are divided in two folders.
Ferret_scripts contain the first step of postprocessing; relies on a descriptor file (.des) that gathers several output (usually 10 or 20-years of yearly (ocean.nc) or monthly (ocean_month.nc) files. Usually includes spatial expression (i.e. global, zonal, vertical integrations of the tendency diagnostics) and sometimes also includes time averages. Output are saved into NetCDF files.
Python_scripts contain the second step of postprocessing. Generally they include loading the NetCDF files from Ferret process and ploting figures for peer-reviewed publications.


