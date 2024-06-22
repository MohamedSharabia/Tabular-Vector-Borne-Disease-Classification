This repository contains a solution to the Playground Series S3E13 challenge. The challenge involves predicting the prognosis of patients based on a set of features.
The dataset used in this challenge is a CSV file containing 13 features and a target variable prognosis. The dataset is split into training and testing sets.
The code is organized into several sections:
Data Loading and Preprocessing: This section loads the dataset, performs data preprocessing, and splits the data into training and testing sets.
Exploratory Data Analysis: This section performs exploratory data analysis on the dataset, including summary statistics, data visualization, and correlation analysis.
Feature Engineering: This section performs feature engineering, including encoding categorical variables and scaling numerical variables.
Model Selection and Hyperparameter Tuning: This section selects and tunes several machine learning models, including NuSVC, ExtraTreesClassifier, BernoulliNB, SVC, NearestCentroid, RandomForestClassifier, LinearSVC, LGBMClassifier, and XGBClassifier.
Model Evaluation: This section evaluates the performance of each model using metrics such as accuracy, precision, recall, and F1 score.
Submission: This section generates a submission file for the challenge.
The following models are used in this solution:

NuSVC
ExtraTreesClassifier
BernoulliNB
SVC
NearestCentroid
RandomForestClassifier
LinearSVC
LGBMClassifier
XGBClassifier

Hyperparameter tuning is performed using GridSearchCV for some models.
The final submission file is generated using the best-performing model, which is XGBClassifier.
This code requires the following libraries:

pandas
numpy
scikit-learn
xgboost
lightgbm
To run the code, simply execute the Python script in a Jupyter notebook or a Python environment with the required libraries installed.
