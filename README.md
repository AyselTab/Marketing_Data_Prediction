# Marketing_Data_Prediction
This case study has the purpose for analyze the dataset and build a model for prediction an impact of marketing campaign using more than a 12K observations. For each sample has the follow features:
ID;
age;
job;
marital;
education;
default; 
balance;
housing;
loan;
contact;
day;
month;
campaign;
pdays;
previous;
response;
result

# Data sources
raw data:
for building model: https://github.com/AyselTab/Marketing_Data_Prediction/blob/d8cbbf580a461f3dbd03e5430797df0dd4fede60/marketing.csv

for applying model: https://github.com/AyselTab/Marketing_Data_Prediction/blob/d8cbbf580a461f3dbd03e5430797df0dd4fede60/marketing_test.xlsx

This file contains Python code to read the dataset, preprocess the data, train machine learning model (Random Forest Classifier), optimize the model, and make predictions: https://github.com/AyselTab/Marketing_Data_Prediction/blob/d8cbbf580a461f3dbd03e5430797df0dd4fede60/Marketing_Data_Prediction.ipynb 

# Data preprocessing
imported relevant libraries in order to preprocess the data. Loaded the data and scrutinized on it. Unnecessary columns are dropped. Outliers are handled using outlier formula. One-hot encoding turned our categorical data into a binary vector representation.

# Evaluation and results
The dataset is split into training and testing sets. Random Forest Classifier is used to train the data. Base model is further optimized using Randomized Search Cross-Validation. Model accuracy is evaluated using ROC-AUC score and Gini score. Univariate analysis is done in order to reveal the proportion of accuracy for each feature.

# Deployment
the last step is used to make prediction on new data. The probability of marketing campaign success reflected in prob_of_interest column.







