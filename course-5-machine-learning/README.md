# Course 5 – Machine Learning

This folder contains the machine learning phase of the TikTok claims classification project completed as part of the Google Advanced Data Analytics Professional Certificate.

## Objective

The objective of this phase was to build and compare machine learning classification models that predict whether a TikTok video contains a claim or presents an opinion.

## Work Completed

- Considered ethical implications of classification errors
- Evaluated class balance
- Handled missing values and duplicate records
- Engineered a `text_length` feature from video transcription text
- Encoded the target variable
- Dummy encoded categorical variables
- Split the data into training, validation, and test sets
- Built and tuned a Random Forest classifier
- Built and tuned an XGBoost classifier
- Used GridSearchCV and cross-validation
- Selected models based primarily on recall
- Evaluated precision to ensure the model was not over-classifying claims
- Compared model performance on the validation set
- Evaluated the champion model on the test set
- Created confusion matrices and classification reports
- Examined feature importance

## Key Findings

- The target classes were nearly balanced between claims and opinions.
- Recall was prioritized because false negatives could cause claim videos to receive lower review priority.
- The Random Forest model achieved very high recall and precision during cross-validation.
- The models were able to distinguish claims from opinions with very strong classification performance.
- Confusion matrices showed very few false positives and false negatives.
- Feature importance analysis helped identify which video and account characteristics contributed most strongly to classification.

## Tools & Skills

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- XGBoost
- Random Forest
- GridSearchCV
- Cross-validation
- Feature engineering
- Classification
- Hyperparameter tuning
- Precision
- Recall
- F1 score
- Confusion matrices
- Model evaluation
- Feature importance

## Files

- `tiktok_course5_machine_learning.ipynb` — completed Course 5 machine learning notebook

## Note

This is an educational project using synthetic data created for the Google Advanced Data Analytics Professional Certificate.
