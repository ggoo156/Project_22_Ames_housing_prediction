# Project 2 - Ames Housing Data and Kaggle Challenge

### Forward
The goal of this project is to predict the the Ames housing sale price. Within this repository, you will find a documented process for sourcing, cleaning, modeling, and evaluating data. The models and methods contained here are intended for use by Zillow or other housing price websites for reference but we invite and encourage anybody to use this analysis to predict what there house sale price might be. (We will also submit our sale price for Kaggle competition!)

# Executive Summary

### Problem Statement
New York City is the biggest city on the east coast of the United States and there are tons of different kinds of foods and restaurants in the melting pot. With the huge food market, NYC restaurant inspection is one of the most important issue since there are various ways to cook, store, and serve different kinds of food. I resolved to tap into this wealth of information, and use it to create a tool to provide NYC restaurant inspectors by applying statistical models with some recommendations. (although a savvy user could use this analysis as a reference to predict the inspection score (grade) of their own restaruant!). 

### Kaggle Ames Housing Data
- [**DOHMH NYC Inspection Results**](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j)
- [**New York State ZIP Codes-County FIPS Cross-Reference**](https://data.ny.gov/Government-Finance/New-York-State-ZIP-Codes-County-FIPS-Cross-Referen/juva-r6g2)

### Project Files and Workflow
- [1.Data_Collection]
- [2.Expolratory_Data_Analysis]
- [3.Preprocessing]
- [4.Modeling]
- [5.Conclusion]



Welcome to Project 2! It's time to start modeling.

**Primary Learning Objectives:**
1. Creating and iteratively refining a regression model
2. Using [Kaggle](https://www.kaggle.com/) to practice the modeling process
3. Providing business insights through reporting and presentation.

You are tasked with creating a regression model based on the Ames Housing Dataset. This model will predict the price of a house at sale.

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses.

Secondly, we are hosting a competition on Kaggle to give you the opportunity to practice the following skills:

- Refining models over time
- Use of train-test split, cross-validation, and data with unknown values for the target to simulate the modeling process
- The use of Kaggle as a place to practice data science

As always, you will be submitting a technical report and a presentation. **You may find that the best model for Kaggle is not the best model to address your data science problem.**

## Set-up

Before you begin working on this project, please do the following:

1. Sign up for an account on [Kaggle](https://www.kaggle.com/)
2. **IMPORTANT**: Click this link ([Regression Challenge Sign Up](https://www.kaggle.com/t/cf68f4a276f44b59a3c6c843dbf9ed1e)) to **join** the competition (otherwise you will not be able to make submissions!)
3. Review the material on the [DSI-US-6 Regression Challenge](https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge)
4. Review the [data description](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt).

## The Modeling Process

1. The train dataset has all of the columns that you will need to generate and refine your models. The test dataset has all of those columns except for the target that you are trying to predict in your Regression model.
2. Generate your regression model using the training data. We expect that within this process, you'll be making use of:
    - train-test split
    - cross-validation / grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library)
3. Predict the values for your target column in the test dataset and submit your predictions to Kaggle to see how your model does against unknown data.
    - **Note**: Kaggle expects to see your submissions in a specific format. Check the challenge's page to make sure you are formatting your CSVs correctly!
    - **You are limited to models you've learned in class**. In other words, you cannot use XGBoost, Neural Networks or any other advanced model for this project.
4. Evaluate your models!
    - consider your evaluation metrics
    - consider your baseline score
    - how can your model be used for inference?
    - why do you believe your model will generalize to new data?

## Submission

**Materials must be submitted by the beginning of class on December 7.**

Your technical report will be hosted on Github Enterprise. Make sure it includes:

- A README.md (that isn't this file)
- Jupyter notebook(s) with your analysis and models (renamed to describe your project)
- At least one successful prediction submission on [DSI-US-6 Regression Challenge](https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge) --  you should see your name in the "[Leaderboard](https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge/leaderboard)" tab.
- Data files
- Presentation slides
- Any other necessary files (images, etc.)

**Check with your local instructor for how they would like you to submit your repo for review.**

---

## Presentation Structure

- **Must be within time limit established by local instructor.**
- Use Google Slides or some other visual aid (Keynote, Powerpoint, etc).
- Consider the audience. **Check with your local instructor for direction**.
- Start with the **data science problem**.
- Use visuals that are appropriately scaled and interpretable.
- Talk about your procedure/methodology (high level).
- Talk about your primary findings.
- Make sure you provide **clear recommendations** that follow logically from your analyses and narrative and answer your data science problem.
