# Titanic--Machine-Learning-from-Disaster
Using supervised machine learning to predict survivavibility of Titanic passangers (from Kaggle Challenge)

The link to the challenge is linked below:\
https://www.kaggle.com/c/titanic

## Approach

**A. Data Processing**\
Based on given a dataset of titanic passengers, features were extracted such as age, gender, fare, cabin, and survival status.\

Imputation and standardization/normalization of the raw dataset were applied to extract features.

**B. Exploratory Analysis**\
Statstical Analysis was applied to find correlations between the survival status of passengers and the features.
* Spearman and Pearson correlation
* Point Bisceral Correlation
* Chi-squared test

**C. Machine Learning**\
Two (2) models were trained (XGBoost and Random Forest) with the processed dataset via hyperparameter tuning with 10-fold cross validation.

The best model (Random Forest) was chosen based on the Accuracy score of the model when the test data was used.

