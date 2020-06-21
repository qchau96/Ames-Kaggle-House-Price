# Ames-Kaggle-House-Price
![Image](https://storage.googleapis.com/kaggle-competitions/kaggle/5407/media/housesbanner.png)

  The Ames Housing dataset was compiled by Dean De Cock for use in data science education, and was posted on [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). The data set describing the sale of individual residential property in Ames, Iowa from 2006 to 2010. The data set contains 2930 observations and a large number of explanatory variables (23 nominal, 23 ordinal, 14 discrete, and 20 continuous) involved in assessing home values. With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges me to predict the final price of each home.

  For this project, I have conducted a detailed EDA to understand the data and important features. I also performed data preprocessing and feature engineering based on exploratory analysis. Finally, I train Ridge, Lasso, XGBoost, and LightGBM models, and take average predictions from these models to predict final price of each house. 

  By the time I write this notebook, my best model **score** is **0.11664**, approximately top **9.6%** in the Kaggle leaderboard.
  
## Table of Contents

- **I. Introduction**

- **II. Exploratory Data Analysis**
1. Sale Price
   
2. Numerical Variables
   
3. Correlations Between Numerical Features
 
- **III. Data Preprocessing and Feature Engineering**

1. Missing Values
    
2. Feature Engineering
    
      - a. Create New variables
      - b. Label Encoding
      - c. Numerical Variables to Factors
      - d. Outliers
 3. Skewness and Normalizing Data
 
       - a. Scaling Data
       - b. One-hot Encoding
       
- **IV. Modeling**

1. Regularized Regressions
        - a. Ridge Regression
        - b. Lasso Regression
2. XGBoost
    
3. LightGBM
    
4. Averaging model

- **V. Conclusion**
- **VI. Reference**
