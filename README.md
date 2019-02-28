# Project 2 - Ames Housing Data and Kaggle Challenge

### Forward
The goal of this project is to predict the the Ames housing sale price by using regression models. Within this repository, you will find a documented process for sourcing, cleaning, modeling, and evaluating data. The models and methods contained here are intended for use by Zillow or other housing price websites for reference but we invite and encourage anybody to use this analysis to predict what there house sale price might be. (We will also submit our sale price for Kaggle competition!)

# Executive Summary

### Problem Statement
 Zillow requested General Assembly(G.A) Data Science team to help predict the Ames housing sale price for their website improvement. Linear regression models will be used to find the model of best fit to predict the house price.

### Kaggle Ames Housing Data - [Here](https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge/data)

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses.

- **train.csv** -- this data contains all of the training data for your model. The target variable (SalePrice) is removed from the test set!
- **test.csv** -- this data contains the test data for your model. You will feed this data into your regression model to make predictions.
- **sample_sub_reg.csv** -- An example of a correctly formatted submission for this challenge (with a random number provided as predictions for SalePrice. Please ensure that your submission to Kaggle matches this format.
- Review the [data description](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt).

### Project Workflow
- 1) [Data_Cleaning and EDA](https://github.com/ggoo156/Project_2_Ames_housing_prediction/blob/master/code/1.%20Data%20Cleaning%20and%20EDA.ipynb)
- 2) [Preprocessing_and_Feature_Engineering](https://github.com/ggoo156/Project_2_Ames_housing_prediction/blob/master/code/2.%20Preprocessing%20and%20Feature%20Engineering.ipynb)
- 3) [Modeling_and_Evaluation](https://github.com/ggoo156/Project_2_Ames_housing_prediction/blob/master/code/3.%20Modeling%20%26%20Evaluation.ipynb)

### Conclusion
- Overall quality, above ground living area square feet, and garage area are the features that has the high correlation with the sale price.
- Among the linear regression, elastic net performs the best for predicting Ames housing sale price.


