# MACHINE_LEARNING
Regression and Classification Models

Author: Maybelline Monge

## DATA
Source: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset?resource=download

Brief Description of Data

'Stroke Prediction Dataset' is a binary classification dataset which will be experimented with models. We will use this dataset to demonstrate how to evaluate a classification model on a binary classification problem. Each record in this dataset correlates to patients risk of strokes and each feature represents health factors of an individual.

Our task will be to create a model that predicts an individual's risk of stroke based on the their personal health factors.

Some challenges one may foresee while cleaning, exploring and modeling this dataset can be the following:
- Data Leakage
- Duplicated, Inconsistent, and/or Missing values
- Class Imbalances
- False Predictions and Sampling Errors


## METHODS

- Logistic Regression Modeling

Confusion Matrices

![download (2)](https://github.com/MayBornWitIt/Machine_Learning/assets/126980733/be55292a-f8e9-4548-9678-fce43ec9d87f)

![download (3)](https://github.com/MayBornWitIt/Machine_Learning/assets/126980733/827f3bbc-5e60-4c6e-832d-b4231ec6d2b8)

Based on the tested and tuned logistic regression model above, there are way too many false negatives and zero positives. This translates into many faulty predictions of individuals at risk of stroke based on the various selected health factors. I suggest utilizing a different model such as Random Forest to test out multiple predictions.



- K-Nearest Neighbors Modeling
