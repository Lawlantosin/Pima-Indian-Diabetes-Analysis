# Pima Indian Diabetes Analysis

## Introduction

This project focuses on modeling the "Pima Indians Diabetes" dataset using logistic regression. The goal is to predict which individuals are more likely to develop diabetes. The dataset originates from the National Institute of Diabetes and Digestive and Kidney Diseases and aims to predict diabetes presence in patients based on diagnostic measurements. All subjects in the dataset are females of at least 21 years of age and of Pima Indian heritage.

## Table of Contents

- [Installation](#installation)
- [Dataset Overview](#dataset-overview)
- [Usage](#usage)
- [Data Preparation](#data-preparation)
- [Model Building](#model-building)
- [Performance Evaluation](#performance-evaluation)
- [Dependencies](#dependencies)

## Installation

To run the analysis, ensure you have Python installed on your machine, then install the required libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

## Dataset Overview

The dataset includes the following features:
- Pregnancies (Preg)
- Glucose (Plas)
- Blood Pressure (Pres)
- Skin Thickness (Skin)
- Insulin (Test)
- BMI (Mass)
- Diabetes Pedigree Function (Pedi)
- Age (Age)
- Outcome (Class)

There are 768 observations in the dataset with no missing values.

## Usage

To replicate the analysis:
1. Load the dataset.
2. Perform data cleaning and preparation, including handling zeros in the dataset with median imputation for certain columns.
3. Split the data into training and testing sets.
4. Apply logistic regression and evaluate the model's performance.

## Data Preparation

Data preparation steps include:
- Replacing zeros in specific columns with the median value of each column.
- Splitting the dataset into features (X) and the target variable (y).
- Scaling the features using MinMaxScaler.

## Model Building

The logistic regression model is built with the default parameters and evaluated using the training and testing datasets.

## Performance Evaluation

Model performance is evaluated using accuracy, precision, recall, and F1-score metrics. Additionally, confusion matrices are generated to visualize the model's performance.

## Dependencies

The project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn
