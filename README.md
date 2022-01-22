# Analysis_car_dataset
This repository contains analysis of car dataset (available at http://archive.ics.uci.edu/ml/datasets/Car+Evaluation) with various machine learning algorithms

This project is made by me and https://github.com/darshankapadiya19

We performed various algorithms on the dataset which includes:
1. Logistic Regression
2. K-nearest neighbors
3. Random Forest
4. eXtreme Gradient Boosting (XGBoost)

After these we found that some classes in the dataset are not having good contribution, so we oversampled data using ADASYN and SMOTE techniques and achieved a better accuracy and F1-score.

We also manually oversampled data by copying the data of the classes which were not in proper contribution and achived even better accuracy on the car dataset.
