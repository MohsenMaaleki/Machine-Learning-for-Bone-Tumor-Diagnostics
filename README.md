# Machine Learning for Bone Tumor Diagnostics

## Overview

This project involved developing and evaluating machine learning models to classify bone tumor patient status into three categories:

- No Evidence of Disease (NED)  
- Alive with Disease (AWD)
- Deceased (D)

The models were trained and tested on a dataset from the Memorial Sloan Kettering Cancer Center with 500 samples and 9 features.

## Models

The following machine learning classification algorithms were implemented and evaluated:

- Gaussian Naive Bayes
- Decision Tree
- Random Forest 
- Logistic Regression
- Linear SVC  
- K-Nearest Neighbors (Euclidean and Manhattan distances)

## Evaluation

The models were thoroughly evaluated on classification performance metrics:

- Accuracy
- Precision  
- Recall
- F1 Score
- Execution Time

## Results

Among all the models, **Logistic Regression** achieved the highest accuracy of 81% in classifying bone tumor patient status.

Linear SVC also performed well in minimizing false negatives. In contrast, Gaussian Naive Bayes and KNN models showed limitations in distinguishing between patient statuses.

## Repository Contents

This repository contains:

- Jupyter notebooks for data preprocessing, EDA, and model implementation
- Model evaluation results

## References

The dataset is from Kaggle: https://www.kaggle.com/datasets/antimoni/bone-tumor
