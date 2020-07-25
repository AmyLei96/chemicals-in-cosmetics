# Chemicals in Cosmetics
## Overview
Consumers are generally not aware of the potentially hazardous ingreidents in the cosmetics that they use on a daily basis. In order to make such information available to the public, The California Safe Cosmetics Progam in the California Department of Public Health has been collecting information on these hazardous ingredients in cosmetic products sold in Caliofrnia since 2005. Under the California Safe Cosmetics Act, manufacturers, packers, and/or distributors named on the product label are required to report a list of all cosmetic products that contain any ingredients which may cause cancer, birth defects, or issues related to development and reproduction. 

## Data
Raw data about the cosmetic companies that have reported hazardous ingredients in their products is aggregated by the CDPH and made available by [HealthData.gov](https://healthdata.gov/dataset/chemicals-cosmetics). The dataset is updated frequently, but for the purpose of this exercise the most recent update is from June 2020.

Free-text columns are cleaned using the Python pandas library in an effort to reduce redundant company and brand names that have been recorded in different formats. 

## Files
- cscpopendata.csv: raw dataset
- cscopendata_clean.csv: cleaned dataset
- cali_chemicals_cosmetics.ipynb: Jupyter notebook for cleaning the free-text columns

## Analysis and Visualization
Further data wrangling, analysis, and visualization are done in Tableau and can be found on [Tableau Public](https://public.tableau.com/views/ChemicalsinCosmetics_15953635587470/Dashboard1?:language=en&:display_count=y&publish=yes&:origin=viz_share_link).
