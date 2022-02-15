# Stroke-Prediction
ML model for stroke prediction
This project is aimed at developing a model that could predict the state of suscepibility to Stroke disease.
The classes for the output variable are "0 & 1", both denoting the presence of stroke and safe-state respectively.
Matplotlib and Seaborn Python language visualization libraries were used in Exploratory Data Analysis.
A pipeline was created for Feature engineering, handling the column transformation of the numerical and categorical columns and an instantiated Logistic Regression model.
The Pipeline and Logistic regression model were passed through cross validation along with dataset in evaluation of F-1, Recall, Precision, ROC_AU_AUC and accuracy scores. The outcome suggested a heavily imbalanced dataset as the accuracy was biased towards the "0" class as many samples in the datset were of no stroke potency.
In handling of this biased report, Synthetic Minority Oversampling Technique (SMOTE) model was deployed on the dataset to create a synthetic balance between both classes of output. 
The SMOTE dataset was fitted into a Random Forest model that yield an Accuracy score of 97%, Recall score of 97%, Precision score of 97% and AUC score of 97%.
Dataset used for the purpose of this project was sourced from Kaggle.com
