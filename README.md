# Land Surface Phenology with Sentinel-2


This repository contains the Google Earth Engine code that was developed for the estimation of Land Surface Phenology (LSP) metrics (start and end of season (SoS and EoS)) with Sentinel-2 at high latitudes. 

The LSP extraction method is the threshold method.

The repository contains the following files:

- Estimation of SoS and EoS with time series smoothing (20-day composition and cubic interpolation)
  https://code.earthengine.google.com/c60b360731a4cb40bffa539614654da7
  
- Estimation of SoS and EoS without time series smoothing (linear interpolation over the raw time series)
  https://code.earthengine.google.com/eb012e6e0637d9fc4f5c8e32ed4a126a
  
Adrià Descals - a.descals@creaf.uab.cat / CREAF - Centre de Recerca Ecològica i Aplicacions Forestals
