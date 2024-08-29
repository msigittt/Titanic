# Titanic Dataset - Machine Learning Model Comparison

This repository contains an analysis of the Titanic dataset, focusing on predicting passenger survival using various machine learning models. The primary goal is to compare the performance of different models to determine the most effective one for this dataset.

## Project Overview

The Titanic dataset is a well-known dataset used for classification tasks, specifically to predict whether a passenger survived the disaster. In this project, I applied and compared the following machine learning models:

- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **KNeighbors**

## Methodology

### Data Preprocessing:

- Handled missing values and outliers.
- Feature engineering to extract meaningful features from the available data.
- Data normalization and scaling where necessary.

### Model Training:

- Implemented each model using scikit-learn.
- Used grid search for hyperparameter tuning to optimize each model.
- Cross-validation was employed to ensure the reliability of the results.

### Model Comparison:

- Evaluated each model based on accuracy, precision, recall, F1-score, and ROC-AUC.
- Compared performance metrics to identify the best model for this classification task.

## Results

- The **Random Forest** model achieved the highest accuracy and general performance metrics among the tested models.
- **KNN** and **SVM** provided competitive results, but with a trade-off in terms of computation time and complexity.
- Detailed results and performance metrics for each model are provided in the report.

## Conclusion

The **Random Forest** model proved to be the most robust in handling the Titanic dataset, outperforming KNN, SVM, and KNeighbors in this analysis. Future work could involve exploring ensemble methods or feature selection techniques to further improve model performance.
