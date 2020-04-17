# OEAS895_FinalProject

This repo contains all of my code for my OEAS895 Ocean Data final project, in which a supervised machine learning algorithm is used to predict N2 fixation rates in the Mid-/South Atlantic Bight in Aug, 2016, from satellite-derived sea surface data and in situ measurements. The .csv files necessary to run these scripts are available in a Google Drive folder unless otherwise noted. This repo includes the following scripts:

1) OEAS895_ProjectPart2_ExploratoryDataAnalysis.ipynb - exploratory analysis of target and predictor datasets; satellite netCDF files and ETOPO model output (bathymetry) used in this script are not provided in the Google Drive folder but can be uploaded upon request or shared via Dropbox or accessed following the links/citations embedded in the script

2) OEAS895_ProjectPart3_A_SupplementalExploratoryDataAnalysis_CompareSatandInSituData.ipynb - satellite-derived sea surface parameters are compared to measured sea surface parameters

3) OEAS895_ProjectPart3_A_BinCTDData.ipynb - bins CTD data at a given depth interval for each cast and creates a mean profile of all casts per station; the raw CTD data file is not provided as it is exceptionally cumbersome

4) OEAS895_ProjectPart3_A_CollateSurfacePredictorDataset_nosal.ipynb - satellite data are binned and compiled into a single spreadsheet; satellite netCDF files and ETOPO model output (bathymetry) used in this script are not provided in the Google Drive folder but can be uploaded upon request or shared via Dropbox or accessed following the links/citations embedded in the script

5) OEAS895_ProjectPart3_B_RandomForestModel_ProfilePred_NFR.ipynb - RF model is built from measured N2 fixation rates and hydrographic parameters measured in situ; the model is used to predict rates from satellite-derived sea surface parameters

6) OEAS895_ProjectPart3_B_RandomForestModel_SatPred_NFR.ipynb - RF model is built from measured N2 fixation rates and hydrographic parameters measured in situ; the model is used to predict rates from CTD data binned in script 3

7) OEAS895_ProjectPart3_C_DataAnalysis.ipynb - predicted and measured rates are visualized and areal N2 fixation rates are calculated based on both measured and predicted (from CTD data) values; the files containing seafloor bathymetry and the high-resolution coastline are not included in the Google Drive folder but can be provided if you'd like them

All processed data (.csv) are accessed by these scripts from "..\Calculations\".
