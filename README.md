# Gross National Income as a function of Deaths by Risk Factors 
## Linear Regression Analysis

This project analyzes the relationship between the number of deaths worldwide due to leading risk factors and the financial prosperity of these countries, as measured by their Gross National Income (GNI) per capita. The goal of the projects is to understand which of the risk factors has the largest impact on GNI. The country list is reduced to just the low to mid level GNI countries, in order to better understand which risk factors might impact the growth from low to mid income. Python is used to merge the various data sources, create a linear regression model, and validate the results. After collecting, cleaning, and merging the data a model is built using forward selection stepwise regression. The resulting model has an Adjusted R-squared value of .676. For a simple linear model without higher order terms, this is a good starting point for crafting a more comprehensive model. The risk factors having the largest impact are then identified.

![number-of-deaths-by-risk-factor](https://github.com/jeg-msba/GNI-Linear-Regression-Model/assets/111711622/fa95b38a-71a5-45c4-8c2a-a224d2f4e585)

GNI-Death Risk Analysis.docx is the report on this project. It describes the data aquisition, cleaning, merging of data, the model building, and model validation.
GNI-vs-deathrate.ipynb is a deepnote python notebook with the code used to clean and merge data, build the model, and validate the model.
number-of-deaths-by-risk-factor.csv, API_NY.GNP.PCAP.CD_DS2_en_csv_v2, and API_SP.POP.TOTL_DS2_en_csv_v2 are the three data sources for this project
