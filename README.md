# Credit Risk German Classification 
In this dataset, each entry represents a person who takes a credit by a bank with 1000 rows and 20 columns. Each person is classified as good or bad credit risks.

In this project, I try to classify good or bad credit risks with models that can deal with both numerical variables and categorical variables like CatBoost and XGBoost.

My project following this step
1. Clean data
- Identify and handle missing values:  Check for missing values in each column and decide how to handle them
- Explore the distribution of numerical features and identify outliers
- recode some value (A1-A33) into in meaning
  
2. Explore and feature selection
- Explore data
- use chi-square test to see what feature is effect to credit risk

3. Modeling
- Train-Test Split: Divide data into training and testing sets
- Hyperparameter Tuning: Use techniques like RandomizedSearchCV to search for optimal hyperparameter values for your chosen models
- Evaluation with Confusion metric and auc curve
