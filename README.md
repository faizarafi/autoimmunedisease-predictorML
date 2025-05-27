# Predicting Autoimmune Disease from Clinical Data using Machine Learning Models

## Overview

This project explores the use of machine learning models to predict autoimmune disease status in patients using clinical data from Kaggle. The dataset includes clinical features from both healthy individuals and patients diagnosed with autoimmune disorders. The goal was to build predictive models and evaluate their performance to determine which algorithms best identify autoimmune disease cases.

## 📁 Repository Contents

- `autoimmune_ml.ipynb`: Main analysis notebook with data processing, model training, and evaluation
- `projectreport.pdf`: Final written report including methodology, analysis, and discussion of results

## Data
Data from 12,500 individuals. There are 116 classes in the target label, which include normal patients (who have no autoimmune disease) or patients with a range of 115 different autoimmune diseases. There were 2,500 normal samples and 10,000 disease samples. There are 79 features in the data. (Data retrieved from Kaggle: https://www.kaggle.com/datasets/abdullahragheb/all-autoimmune-disorder-10k/data?select=Final_Balanced_Autoimmune_Disorder_Dataset.csv)

## Methods

Data preprocessing include:
- PCA (to evaluate)
- RandomUnderSampling
- SMOTE

Models evaluated include:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

Evaluation was based on:
- Accuracy
- Precision, Recall, F1-score
- ROC AUC

## Results Summary

Random forest performs the greatest in predicting disease, closely followed by SVC. Blood panel vitals are among the top features that contribute the greatest to disease prediction

## Key packages:
- os
- pandas
- numpy
- matplotlib
- sklearn.model_selection
- sklear.preprocessing
- sklearn.metric
- sklearn.tree, sklearn.linearmodel
- sklearn.ensemble
- imblearn.over_sampling 
- imblearn.under_sampling
