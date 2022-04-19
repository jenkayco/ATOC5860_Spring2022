Application lab Repository for ATOC5860 Objective Data Analysis
Spring 2022 
Jennifer E. Kay, University of Colorado, Jennifer.E.Kay@colorado.edu
Last updated: April 19, 2022

0) Lecture code in folder lecture_code

1) Application Lab #1 files in the folder lab1
ATOC5860_applicationlab1.docx = guidance for the lab on statistical significance testing, start here
ATOC5860_applicationlab1_bootstrapping.ipynb
ATOC5860_applicationslab1_ztest_ttest.ipynb
TS_timeseries_cesmle_1850.nc
TS_timeseries_cesmle_1920_2100.nc
nino34.long.anom.data.txt
snow_enso_data.csv

2) Application Lab #2 files in folder lab2
ATOC5860_applicationlab2_guidance.docx - guidance for the lab on regression/autocorrelation/AR1 process, start here
ATOC5860_applicationlab2_AR1_Nstar.ipynb
ATOC5860_applicationlab2_AR1_regression_AO.ipynb
christman_2016.csv
monthly.ao.index.b50.current.ascii

3) Application Lab #3 files in folder lab3
ATOC5860_applicationlab3_guidance.docx - guidance for lab3 on EOF/PCA analysis guidance
ATOC5860_applicationlab3_eof_analysis_cosineweightingLAST_cartopy.ipynb - application lab on EOF/PCA of Sea Surface Temperatures
ATOC5860_applicationlab3_eof_analysis_NOcosineweighting_cartopy.ipynb - application lab on EOF/PCA of Sea Surface Temperatures, no cosine weighting of latitude
ATOC5860_applicationlab3_eigenfaces.ipynb - application lab on EOF/PCA of faces
att_faces.npy - data needed for ATOC5860_applicationlab3_eigenfaces.ipynb
***Note: The data needed for ATOC5860_applicationlab3_eof_analysis_cosineweighting_cartopy.ipynb are too big to upload to github***
***Please download yourself from http://www.metoffice.gov.uk/hadobs/hadisst/data/download.html
or if logged into CU account from https://drive.google.com/file/d/10-hoqJQPrwOj8cXeel6-EcXU_zPuAkXZ/view?usp=sharing3) 

4) Application Lab #4 files in folder lab4
ATOC5860_applicationlab4.docx - guidance for lab4 on spectral analysis
ATOC5860_applicationlab4_fft_EPICA.ipynb - spectral analysis of ice core data over many glacial cycles
edc3deuttemp2007.txt, edc3deuttemp2007_nohead.txt - ice core data
ATOC5860_applicationlab4_fft_christman.ipynb - spectral analysis of weather data from Fort Collins, Colorado
Christman_data_nomissing.csv - weather data from Fort Collins, Colorado
ATOC5860_applicationlab4_fft_mesa.ipynb - spectral analysis of weather data from the NCAR Mesa Lab Boulder, Colorado
mesa_data_2016-2021_withmissing.csv - weather data from NCAR Mesa Lab Boulder, Colorado
TidesAtmosphere.pdf - relevant for weather data, atmospheric tides?
LombScarglePeriodogram_nonuniform_missingdata_FFT_forreference.pdf - relevant for spectral analysis

5) Application Lab #5 files in folder lab5
ATOC5860_applicationlab5.docx - guidance on lab5 filtering
ATOC5860_applicationlab5_check_python_convolution.ipynb - understand python functions used to smooth/filter in the time domain
ATOC5860_applicationlab5_synthetic_data_with_filters.ipynb - filter analysis of synthetic data
ATOC5860_applicationlab5_ENSO_mrbutterworth.ipynb - filter analysis of ENSO in a climate model
CESM1_LENS_Coupled_Control.cvdp_data.401-2200.nc - data for lab5. The data are available on github and can be pushed from the command line.  
But the data are considered large (68 MB) and cannot be pushed via the web-based github GUI.

6) Application Lab #6 in folder lab6
ATOC5860_applicationlab6.docx - guidance on lab6 machine learning
ATOC5860_applicationlab6_cluster_mesa_data.ipynb - k-means clustering of weather data from Boulder, Colorado
NCAR_mesa_data_2016-2021_withmissing.csv - data needed for ATOC5860_applicationlab6_cluster_mesa_data.ipynb
ATOC5860_applicationlab6_supervised_ML.ipynb - supervised machine learning of weather data from Fort Collins, Colorado
christman_2016.csv - data needed for ATOC5860_applicationlab6_supervised_ML.ipynb
environment.yml - environment needed for ATOC5860_applicationlab6_supervised_ML.ipynb
