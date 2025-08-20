# Workflow for Prevalence Mapping
This repository contains data and the reproducible report for the following paper: 

Dong, Qianyu, Yunhan Wu, Zehang Richard Li, and Jon Wakefield. [Toward a Principled Workflow for Prevalence Mapping Using Household Survey Data.](https://arxiv.org/abs/2504.16435) _arXiv:2504.16435_ (2025).

## Supplementary materials

[Reproducible report](reproducible_report.pdf).

## Data

`Data/TIFF` folder contains the following spatial raster files:

 - `KEN_population_v2_0_agesex_f15_49.tif`: population of female aged 15 to 49 in Kenya in 2022
 - `average_ndvi_buffered.tif`: vegetation index 
 - `average_ntl_buffered.tif`: night time light
 - `health_buffered.tif`: travel time to the nearest healthcare facility
 - `ken_ppp_2019.tif`: overall population in 2019
 
 `Data/covariate` folder contains Admin-1 and Admin-2 area-level covariates preprocessed from the spatial raster files. See the supplementary materials for details.

`Data/TableA.csv` contains census-based urban/rural population information used to calculate the urban/rural fraction of the targeted survey population across all provided administrative levels. 

`Data/anc_data.csv` contains cluster-level survey data with an anonymized household ID. See the reproducible report for how they can be reproduced from raw DHS data. 
