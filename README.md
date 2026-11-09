# CO2-Storage-Whale-South-Whale-Basins-Data
Repository containing data generated for study of CO2 storage potential in the Whale and South Whale basins

- Modelling : This folder contains files relevant to the reflectivity models and synthetic seismic data.
  - 3D_Models.ipynb : Jupyter notebook file containing code used to generate reflectivity models and subsequent synthetic seismic data.
  - Anticline_Model_ext_stat : Text file containing wavelet used for the anticline model.
  - Diapir_model_ext_stat : Text file containing wavelet used for diapir truncation model.
  - Pinchout_model_ext_stat : Text file containing wavelet used for pinchout model.

- Well_Log_Analysis : This folder contains files related to the analysis of well logs, such as code for generating plots and equations used for log generation.
  - pressure_temperature_plots.ipynb : This is a jupyter notebook containing the code developed to make plots of the pressure and temperature data from the wells in my study area.
  - por_perm_eider_core.xlsx : This is an Excel spreadsheet used to calculate the relationship between porosity and permeability of the Eider Fm, determined from the core analysis of the samples from the neighbouring Scotian Basin.
  - Lithology_logs_simple.xlsx : This is an Excel spreadsheet in which each sheet contains the lithology log of one of the wells in the study area. These lithology logs were made from the lithology logs available on the CNLOER website, and simplified to make facies logs in Petrel
