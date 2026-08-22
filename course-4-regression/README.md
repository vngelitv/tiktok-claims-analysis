# Course 4 – Logistic Regression

This folder contains the regression modeling phase of the TikTok claims classification project completed as part of the Google Advanced Data Analytics Professional Certificate.

## Objective

The objective of this phase was to build and evaluate a logistic regression model to predict whether a TikTok user is verified based on video and account characteristics.

Understanding the characteristics associated with verified users may also provide useful information for the broader goal of predicting whether videos contain claims or opinions.

## Work Completed

- Performed exploratory data analysis before modeling
- Checked for missing values and duplicate records
- Examined and handled outliers
- Evaluated class balance in verified status
- Engineered video transcription text length as a potential feature
- Examined correlations between numerical variables
- Checked for potential multicollinearity
- Selected features for logistic regression
- Split the dataset into training and testing sets
- One-hot encoded categorical variables
- Built and trained a logistic regression model
- Generated predictions on the test dataset
- Evaluated the model using a confusion matrix
- Evaluated precision, recall, F1-score, and accuracy
- Interpreted logistic regression coefficients

## Key Findings

- The verified-status target variable was highly imbalanced, with approximately 94.2% of videos associated with unverified accounts and 5.8% with verified accounts before balancing.
- Exploratory analysis identified relationships between video and account characteristics that could be useful for predicting verification status.
- Highly correlated engagement variables required consideration when selecting features because logistic regression assumes no severe multicollinearity.
- Logistic regression provided an interpretable method for examining how individual features were associated with the probability that an account was verified.

## Files

- `tiktok_course4_logistic_regression.ipynb` — completed logistic regression analysis notebook

## Note

This is an educational project using synthetic data created for the Google Advanced Data Analytics Professional Certificate.
