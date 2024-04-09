# About this Project
In this dataset, each entry represents a person who applies for credit from a bank. The data consists of 1,000 rows and 20 columns. Each person is classified as a good or bad credit risk.
- This project focuses on finding the best alogorithm to predict creditworthiness, optimizing for both accuracy and AUC score.
- I have tried to get the best results using feature engineering and random search for hyperparameters.

## My project following this step
1. Clean data
- Identify and handle missing values:  Check for missing values in each column 
- Explore the distribution of numerical features and identify outliers
- recode some value (A1-A33) into in meaning
  
2. Explore and feature selection
- Explore data
- use chi-square test to see what feature is effect to credit risk

3. Modeling
- Train-Test Split: Divide data into training and testing sets
- Hyperparameter Tuning: Use techniques like RandomizedSearchCV to search for optimal hyperparameter values for your chosen models
- Evaluation with Confusion metric and auc curve
