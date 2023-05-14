# Analysis of Factors that Affect Homelessness Rates

The purpose of this project is the analysis of 1) market factors that have established effects on homelessness 2) whether there are alternative modeling approaches that outperform the models perfored in the following U.S. Department of Housing and Urban Development [HUD] 2019 report: 
[Market Predictors of Homelessness](https://www.huduser.gov/portal/sites/default/files/pdf/Market-Predictors-of-Homelessness.pdf) data set describes a model-based approach to understanding the relationship between local housing market factors and homelessness.

# Data
This project uses the following data sets:
05b_analysis_file_update.csv
HUD TO3 - 05b Analysis File - Data - Dictionary.csv

Dictionary.csv is the detailed description of each variable and its associated domain.
HUD's report of these data sets [Market Predictors of Homelessness](https://www.huduser.gov/portal/sites/default/files/pdf/Market-Predictors-of-Homelessness.pdf) states that their study combined multiple datasets to identify factors that affect homelessness rates: housing market, economic conditions, safety net, demographic composition, and climate conditions

# Data Preparation
The described data sets were cleaned and prepared in the Maxine_Lanier_Homelessness_Data_Preparation.ipynb file. 
Relevant columns for analysis of our question were selected, confusing columns renamed, rows were kept only if they are from the year 2017 and the total homeless count is present, the unit for rate of homelessness, sheltered, and unshelted were converted to rates per 10,000 people, units for input variables/ predictors converted to percentages of total population, and the set was not yet split into training and testing data sets. 
Clean data set: 
clean_homelessness_data.csv
https://github.com/maxinelanier/Homelessness/blob/main/clean_homelessness_data.csv
