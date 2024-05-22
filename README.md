# esdp1-test

This repository contains a jupyter notebook ("load_era5.ipynb") that downloads era5 surface temperature data from the Coepernicus data store, regrids data, and plots.

The file load_era5.ipynb first downloads era5 surface temperature data from the Coepernicus Data Store using the cdsapi library. Global surface temperature is then plotted. Next, the era5 data is converted to the icon grid using the cdo package, triangulated and plotted. ERA5 data requests can be modifified and different icon grids can be used as described in the jupyter notebook.

ERA5_surface.nc is the era5 surface temperature netcdf file downloaded using the cdsapi package.

icon_grid_0008_R02B05_G.nc is the icon grid netcdf file used for grid conversion. 

ERA5_surface_icon_grid.nc is the ERA5 data converted to the icon grid. 

.cdsapirc.txt is a sample API key file that needs to be stored in your home directory for the cdsapi package to work properly. 
