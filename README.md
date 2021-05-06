# PRISMA: Convert from HDF-EOS to netCDF format

See `PRISMA_HDFEOS_to_netCDF.ipynb`

PRISMA data is delivered as an HDF5 file with an internal structure that can't be easily read by netCDF readers. This notebook:

- Briefly explores the contents of a PRISMA HDF file, useful for checking data quality
- Converts the PRISMA HDF structure into an xarray dataset, saving as netCDF

The notebook operates on PRISMA L2D data. It will need to be modified to work with other processing levels due to different naming conventions within the PRISMA HDF file.

# PRISMA: Visualisation tools

See `PRISMA_visualisation.ipynb`

The hyperspectral cube captured by PRISMA is difficult to explore with static visualisation tools. Use this notebook explore the cube and spectrograms with some handy hvplots.