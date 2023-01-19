# Bains-et-al.-2022
Supplementary data and analysis for "Comprehensive longitudinal study of home-cage activity, including climbing, reveals new complex phenotypic profile in the N171-82Q HD mouse model with implications for refined preclinical studies."

## Purpose
This repository houses data, code and example analysis outputs to align with Frontiers guidelines to authors. 

## Use
### /data
This folder contains data to be analysed by R scripts. 
* **cage_sum_60hr_change_mean_HD.csv**
     
     Data summed within a cage and averaged over the last 30 minutes of darkness per day of recording. Three days of recording in total. 

* **cage_sum_60hr_first_30_mean_HD.csv**
     
     Data summed within a cage and averaged over the first 30 minutes of darkness per day of recording. Three days of recording in total. 

* **cage_sum_60hr_period_mean_WT.csv**
     
     Data summed within a cage and averaged over light of dark periods per day of recording. Three days of recording in total.

### /analysis code
This folder contains R scripts to analyse data using lmer package. 

* **HD_distance&climbing_last30_RScript.txt**
     R script to run over cage_sum_60hr_change_mean_HD and cage_sum_60hr_first_30_mean_HD. Please update file names (line 10) and Distance/Climbing (line 11) as          required. 

* **WT_distance&climbing_dark&light_periods_Rscript.txt**
     R script to run over caage_sum_60hr_period_mean_WT. Please update file names (line 10), Distance/Climbing (line 11) and Light/Dark (line 12) as required. 
     
### /analysis output
This folder contains output files from /analysis code which are used to generate p values for the publication and figures. 
| analysis output | analysis code | data| 
| --- | --- | --- |
|emm_cage_sum_60_hr_WT_Dark_distance.csv, emm_cage_sum_60_hr_WT_Dark_climbing.csv, emm_cage_sum_60_hr_WT_Light_distance.csv, emm_cage_sum_60_hr_WT_Light_climbing.csv|WT_distance&climbing_dark&light_periods_Rscript|cage_sum_60hr_period_mean_WT|
|||
