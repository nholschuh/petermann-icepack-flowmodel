# petermann-icepack-flowmodel
Uses icepack (Python finite element glacial flow model developed by Daniel Shapero) to model dynamics of Petermann Glacier, NW Greenland. Uses many of icepack's unique features such as the inverse solver, the 3D advection-diffusion heat transport forward model, and the hybrid flow model. Both the 2D flowline and the 3D basin model are defined by a monolayer extruded mesh. For questions about icepack refer to Daniel Shapero's github at https://github.com/icepack/icepack



### Dependencies required for running the notebooks in this repository
Need icepack () and firedrake () -- install instructions are provided here: https://icepack.github.io/install/

Up to date versions of: numpy, matplotlib, xarray, rioxarray, rasterio, geojson, sys, os, glob



### Additional run notes:
It is also important that you copy our interpolate_xr function into the icepack source directory, and modify init so it recognizes interpolate_xr as an available function.

