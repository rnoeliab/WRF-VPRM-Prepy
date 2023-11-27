# WRF-VPRM-PrepPy

The Weather Research and Forecasting (WRF) Model is a state of the art mesoscale numerical weather prediction system designed for both atmospheric research and operational forecasting applications. The model serves a wide range of meteorological applications across scales from tens of meters to thousands of kilometers. Coupled with the Vegetation Photosynthesis and Respiration Model (VPRM) (referred to as WRF-VPRM), has used to better understand the effects that mesoscale transport has on atmospheric CO2 distributions.

To run WRF-VPRM is necessary to prepare some data such as input (Anthropogenic, Fires and Biogenic Emissions) and Boundary conditions.

Therefore, a pre-processing tô obtain the input fields tô run WRF-VPRM v4.2.1 model is executed here.

First, clone this repository:
- git clone "[https://github.com/rnoeliab/Inputs-WRF-VPRM.git](https://github.com/rnoeliab/Inputs-WRF-VPRM.git)"

Second, go to "[pys](https://github.com/rnoeliab/Inputs-WRF-VPRM/tree/main/pys)" directory

## 1. Anthropogenic Emissions

First, write:

chmod +x "download_edgar_ghg.sh", then run the code "./download_edgar_ghg.sh". This code will download CO, CO2 and CH4 emissions data from different sources. This information will be necessary to  

Second, run EDGARtoAE.py. For this step, is necessary install...


run the download.sh code

## 2. Fires Emissions

## 3. Biogenic Emissions

## 4. Background Fields
