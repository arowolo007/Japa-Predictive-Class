# Japa-Predictive-Class

# Titanic Dataset - Refined and Cleaned

Welcome to the Titanic dataset repository! This dataset has been curated from the original Titanic: Machine Learning from Disaster dataset, with meticulous refinement and cleaning. Additional features have been engineered, primarily for logistic regression applications. Your feedback, comments, and suggestions are greatly appreciated, especially if you find this dataset useful for other models.

## Contents

This repository contains two main files:

1. `train_data.csv`: This file comprises a dataset with dimensions 792x16. The key target variable, "survived," represents the outcome to be predicted. Notably, the original "parch" and "sibsp" columns have been consolidated into a single "Family size" column for simplicity.

2. `test_data.csv`: This file presents a dataset of size 100x16, specifically designed for testing your models. It mirrors the arrangement of the `train_data.csv`, providing a consistent format for validation and evaluation.

## Data Preprocessing

### Encoding

Categorical data columns, such as "Embarked" and "pclass," have been re-encoded using the one-hot encoding method. This conversion enhances the compatibility of these variables with machine learning algorithms.

### Feature Engineering

Four additional columns, "Title_1" through "Title_4," have been ingeniously engineered from the "Name" column. These titles signify gender and marital status ("Mr," "Mrs," "Master," "Miss"). This engineered feature enables an insightful analysis to determine whether individuals with social responsibilities exhibit distinct survival instincts. This analysis also explores whether the observed trend is consistent across both genders.

### Missing Values

All missing values within the dataset have been imputed using the median of their respective columns. This imputation strategy ensures that the dataset remains representative and valuable for analysis and modeling.

### Normalization

Real-valued data columns have undergone normalization. This preprocessing step standardizes the scale of numerical features, ensuring that they contribute equally to the learning process.

## Feedback and Contact

I encourage you to provide feedback, suggestions, and improvements. If you find value in using this dataset for purposes beyond logistic regression, your insights are particularly valuable. Kindly reach out through the repository's communication channels.

Thank you for exploring and utilizing this refined Titanic dataset. May it contribute to the advancement of your modeling endeavors!
