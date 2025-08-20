# WorkflowPaper
This repository contains data and supplementary file for "Toward a Principled Workflow for Prevalence Mapping Using Household Survey Data"

## Data

 The TIFF folder contatins TIFF files:

 - KEN_population_v2_0_agesex_f15_49.tif: population of female aged 15 to 49 in Kenya in 2022
 - average_ndvi_buffered.tif: vegetation index 
 - average_ntl_buffered.tif: night time light
 - health_buffered.tif: travel time to the nearest healthcare facilit
 - ken_ppp_2019.tif: overall population in 2019
 
The covariate folder contatins Admin-1 and Admin-2 covariates preprocessed from TIFF files

TableA.csv contains census-based urban/rural population information used to calculate the urban/rural fraction of the targeted survey population across all provided administrative levels. 

anc_data.csv contains preprocessed survey data with an anonymized cluster ID.