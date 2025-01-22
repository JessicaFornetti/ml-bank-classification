# ml-bank-classification

This project involves a classification task to predict the outcome of a bank marketing campaign using Python.

This project was completed as part of the course Master of Science in Computer Science (Data Science) at TU Dublin, Ireland.

The main steps of the project are outlined below:

- **Data Cleaning and Exploration** : Inspection of each feature's distribution and outliers, correlation matrix for quantitative variables 
- **Model Training and Hyperparameter Tunning** : Exploration of different resampling methods (oversampling with SMOTE, under sampling with Random Undersampling), Logistic Regression, Random Forest, Gradient Boosting and SVM models trained in a pipeline consisting of encoding, feature selection using both filter and wrapper methods (information gain and forward sequential search) and a grid search to find the best hyperparameters for each model
- **Training The Best Model and Evaluation** : The best Random Forest model obtained was retrained and evaluated on precision, recall, f1-score, accuracy and AUC
- **Predictions on Queries Dataset** : Predictions were made on the queries dataset using the optimal model and saved in a txt file

# Repository Overview
This repository contains 1 Jupyter notebook: [ML - Bank Marketing Campaign Outcome Classification](ML%20-%20Bank%20Marketing%20Campaign%20Outcome%20Classification.ipynb).
