# Newspaper SoldOut Predictions - Logistic Regression and Imbalanced Data
This notebook is a study of the application of sklearn Logistic Regression model and analysis of metric quality with a focus on the impact of imbalanced data.
The problem presented is the analysis of sales of newspapers of a local stand in order to classify the probability of the newspaper being Sold Out or Not, given a set of features.

The model is applied to dataset Newspaper_SoldOut, which is supplied separately in .csv format.

Report Structure
- Data Import and Exploratory Analysis
- Model 1 - Logistic Regression with Imbalanced Data
    - Model Definition
    - Model Fitting and Predictions
    - Confusion Matrix
    - Quality Metrics
- Model 2 - Logistic Regression with Balanced Data
    - Data Balancing - Oversampling
    - Model Definition, Fitting and Predictions
    - Confusion Matrix
    - Quality Metrics

Results Observation

During the comparison of model 1 (imbalanced data) and model 2 (balanced data) it was observed that while the models Accuracy varied with an increase in percentage once the data had been balanced (from 87% in model 1 to 89% in model 2), the Area Under Curve (AUC) remained stable at 0.96 demostrating how those two different measures relate to the data and how AUC focus on the model's discriminatory ability between the classes.
