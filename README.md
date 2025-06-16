# Survey Exploration and Analysis: 2025 Filipinx Survey
Use of Jupyter Notebook, 
Utilization of Libraries: Pandas, MadPlotLib, Plotly for Data Visualizations
Exploration and analysis of 2025 Filipinx Survey conducted by Amado Khaya Institute

# Executive Summary

The importance of proper data cleaning, munging, wrangling, manipulation cannot be overstated. The preponderance of data columns, or features, the amount of errors or null values, required careful selection and aggregation in order to form analysis of survey responses. 

# Contents:

- [Data Dictionary](#Data-Dictionary)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

## Data Dictionary

A data description was provided and can be found here: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt

All features listed below were engineered for both training and testing datasets.

|Feature|Type|Description|
|---|---|---|
|**age**|*int*| Age of the house when it was sold 
|**total_fin_sf**|*int*| Total living area 'under HVAC' 
|**total_baths**|*float*| Total number of bathrooms including half-baths (0.5)
|**good_features**|*float*| Count of good or positive features 
|**bad_features**|*float*| Count of bad or negative features

## Conclusions and Recommendations:

#### Having a clear goal while feature engineering, data munging, and modeling are the key to accurate results with this dataset. Knowing what features were important and how to leverage them to have an affect on the target helped immensely. Grouping or clumping features together was fruitful and will be used again for other projects of this magnitude. Models where we utilized our engineered features fared much better than ones using only one variable. Creating dummy variables and scaling our variables also increased the accuracy of our predictions. 
#### Deliberately avoiding features that are inherently problematic, such as zip code or neighborhood, prevent our models from having a sociological bias. 
#### Future projects with this dataset could include using other models besides linear regression such as Ridge/Lasso/Elastic Net and utilizing a pipeline to deploy each of these hyperparameter tuners. 
