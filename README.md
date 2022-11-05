# Project Name
House Price Prediction
Regression model using regularisation for Housing Price Prediction.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
Model the price of houses with the available independent variables.

    The model will be used by the management to understand how exactly the prices vary with the variables. Surprise Housing can adapt their strategy based on the model and focus on yield high return areas.
    The model will also be used by the management to understand the pricing dynamics of a new market(here Australia)

Data Description: Surprise Housing has collected the Data set from the sale of houses in Australia. The data is provided in CSV file. 
Data Dictionary is provided separately to understand the data.


## Conclusions

The below are the top 5 perdictor variables influencing the `SalePrice` based on Lasso regression
- `GrLivArea`: Above grade (ground) living area square feet
- `GarageCars` Size of garage in car capacity
- `BsmtFinSF1` Type 1 basement finished square feet
- `OverallQual_Good` The overall material and finish of the house is `Good`
- `YearRemodAdd` Remodel date or the construction date

## Technologies Used
### Linear algebra & data processing
numpy	
pandas
### Scientific and technical computing
scipy
### Estimate statistical models, and perform statistical tests
statsmodels 
### Visualization
matplotlib 
plotly
seaborn
### Modeling & Evaluation
sklearn.linear_model for Linear, Ridge & Lasso
sklearn.model_selection for GridSearchCV
sklearn.metrics for model evaluation

## Acknowledgements
IIIT-B & Upgrad Study Materials


## Contact
Created by [@elcommselva] - feel free to contact me!
