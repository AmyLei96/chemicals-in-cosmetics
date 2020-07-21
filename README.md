# Chemicals in Cosmetics
## Overview
Consumers are generally not aware of the potentially hazardous ingreidents in the cosmetics that they use on a daily basis. In order to make such information available to the public, The California Safe Cosmetics Progam (CSCP) in the California Department of Public Health (CDPH) has been collecting information on these hazardous ingredients in cosmetic products sold in Caliofrnia since 2005. Under the California Safe Cosmetics Act, manufacturers, packers, and/or distributors named on the product label are required to report a list of all cosmetic products that contain any ingredients which may cause cancer, birth defects, or issues related to development and reproduction. 

## Data
Raw data about the cosmetic companies that have reported hazardous ingredients in their products is aggregated by the CDPH and made available by [HealthData.gov](https://healthdata.gov/dataset/chemicals-cosmetics). The dataset is updated frequently, but for the purpose of this exercise the most recent update is from June 2020.

Columns containing free-text are cleaned using the Python pandas library in an effort to mainly reduce redundant company and brand names that are recorded in different formats. 

## Files
- cscpopendata.csv: raw dataset
- cscopendata_clean.csv: cleaned dataset

## Visualization
A dashboard of the trends in the cleaned dataset can be found on Tableau Public.
