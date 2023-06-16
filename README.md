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


## DATA
Source: https://www.kaggle.com/datasets/wenruliu/adult-income-dataset

Brief Description of Data

'Adult Income' is a binary classification dataset which will experimented with models. We will use this dataset to demonstrate how to evaluate a classification model on a binary classification problem. Each record in this dataset correlates to adult income and each feature represents a demographic of an individual.

Our task will be to create a model that classifies income level based on an individual's personal information.

## METHODS

Exploratory Data Analysis

![pie](https://github.com/MayBornWitIt/Machine_Learning/assets/126980733/be7b05d0-f692-4dfd-b51e-cb737f7d55c2)

Based on the pie graph above, it displays the majority of adults in the dataset as making less than $50k.


![image](https://github.com/MayBornWitIt/Machine_Learning/assets/126980733/33c898e2-50d3-44bc-a289-d2d9d241b2a9)

Based on the bar graph above it displays Male Asian-Pacific Islanders having the highest capital gains in the dataset. Second being White Males.


![heatmap](https://github.com/MayBornWitIt/Machine_Learning/assets/126980733/5537775f-f996-4d64-b83e-072bb275d66d)

Visualization of Education Level, Gender and Weekly Hours

Based on the heatmap displayed above one can see a high correlation of male & females with a Doctorate and Professional School education pull the most weekly hours.


![BARPLOT](https://github.com/MayBornWitIt/Machine_Learning/assets/126980733/c6f0c6f9-cf85-409f-b747-ec52e012fb64)

Based on the barplot above, majority of older adults whom are self employed make over 50K income.
Whereas, majority of young adults in the private sector make less than 50k income.

![CM ENGINEERED](https://github.com/MayBornWitIt/Machine_Learning/assets/126980733/56d72de8-0d21-4cfd-b843-ec68ffa5ed9f)

ENGINEERED CONFUSION MATRIX 

![CM PCA](https://github.com/MayBornWitIt/Machine_Learning/assets/126980733/4fb7b1cf-99a0-49e2-b73e-6bfa6fa74383)

ENGINEERED WITH PCA CONFUSION MATRIX

Based on the engineered models above, they have tested closely together for accuracy. One being tuned and tested KNN Model at 83% accuracy rate with less False Positives. Whereas, the other model tested with Principal Component Analysis (PCA) at 82% accuracy rate with higher False Positives. Although, KNN model with PCA definitely is a shorter process in obtaining results.

Based on the data exploration, suggest stakeholders utilize tuned and tested engineered KNN Model with higher accuracy rate. Would suggest analyzing further into Asian Pacific Islander Males to see the correlation between Capital Gains and Income influences as they seem to rank high in this dataset.
