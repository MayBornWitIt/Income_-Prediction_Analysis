# Machine_Learning
Regression and Classification Models

Author: Maybelline Monge

## Data
Source: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset?resource=download

Brief Description of Data

'Stroke Prediction Dataset' is a binary classification dataset which will be experimented with models. We will use this dataset to demonstrate how to evaluate a classification model on a binary classification problem. Each record in this dataset correlates to patients risk of strokes and each feature represents health factors of an individual.

Our task will be to create a model that predicts an individual's risk of stroke based on the their personal health factors.

## Classification Report
Train Report
              precision    recall  f1-score   support

           0       0.95      1.00      0.97      3645
           1       0.00      0.00      0.00       187

    accuracy                           0.95      3832
    
   macro avg       0.48      0.50      0.49      3832
   
weighted avg       0.90      0.95      0.93      3832

Test Report
              precision    recall  f1-score   support

           0       0.95      1.00      0.98      1216
           1       1.00      0.03      0.06        62

    accuracy                           0.95      1278
    
   macro avg       0.98      0.52      0.52      1278
   
weighted avg       0.96      0.95      0.93      1278
