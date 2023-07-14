# Hospital Mortality Prediction

This repository contains code for predicting hospital mortality using classification techniques. The code performs data preparation, feature encoding, missing data imputation, normalization, data analysis, and training various machine learning models.

## Table of Contents

- [Introduction](#introduction)
- [Data Preparation](#data-preparation)
- [Feature Encoding](#feature-encoding)
- [Missing Data Imputation](#missing-data-imputation)
- [Normalization](#normalization)
- [Data Analysis](#data-analysis)
- [Training Models](#training-models)
    - [K-Nearest Neighbors](#k-nearest-neighbors)
    - [Tree-based Models](#tree-based-models)
    - [Logistic Regression](#logistic-regression)
    - [Naive Bayes](#naive-bayes)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Hospital mortality prediction is an essential task in healthcare.

## Data Preparation

To prepare the data, follow these steps:

1. Download the dataset from [link-to-dataset]([https://example.com/dataset](https://www.kaggle.com/code/sadiaanzum/patient-survival-prediction)).
2. Run the `data_preparation.py` script:

   ```bash
   python data_preparation.py --input_path <path_to_input_data> --output_path <path_to_save_processed_data>
Replace <path_to_input_data> with the path to the input data file and <path_to_save_processed_data> with the desired path to save the processed data.

##Feature Encoding
To perform feature encoding, use the following commands:

Install the required dependencies:

##Feature Encoding
To perform feature encoding, follow these steps:
1. Run the feature_encoding.py script.
python feature_encoding.py

##Missing Data Imputation
To impute missing data, follow these steps:
2. Run the missing_data_imputation.py script.
python missing_data_imputation.py

##Normalization
To normalize the data, follow these steps:
3. Run the normalization.py script.
python normalization.py

##Data Analysis
To perform data analysis, follow these steps:
4.Run the data_analysis.py script.
python data_analysis.py

###Training Models
##K-Nearest Neighbors
To train the K-Nearest Neighbors model, follow these steps:
Run the knn_model.py script.
python knn_model.py

##Tree-based Models
To train tree-based models, follow these steps:
Run the tree_models.py script.
python tree_models.py

##Logistic Regression
To train the Logistic Regression model, follow these steps:
Run the logistic_regression.py script.
python logistic_regression.py

##Naive Bayes
To train the Naive Bayes model, follow these steps:
Run the naive_bayes.py script.
python naive_bayes.py

