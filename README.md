# TSP_asterisc_technocrat
# Titanic Survival Prediction

This repository contains my solution for the Titanic Survival Prediction task as part of the internship with [Company Name]. The goal of this project is to predict the survival of passengers on the Titanic using machine learning techniques.

## Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Data Preprocessing](#data-preprocessing)
- [Model Selection and Training](#model-selection-and-training)
- [Model Evaluation](#model-evaluation)
- [Making Predictions](#making-predictions)

## Introduction

The sinking of the Titanic is one of the most infamous wrecks in history. This project aims to build a predictive model that can determine which types of passengers were more likely to survive based on passenger data like age, gender, and socio-economic class.

## Getting Started

1. Clone this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Download the dataset files (`train.csv` and `test.csv`) and place them in the appropriate directory.

## Data Preprocessing

- Combine and preprocess the training and test datasets.
- Handle missing values and perform feature engineering.
- Convert categorical variables to numerical using one-hot encoding.
- Split the data into training and validation sets.

## Model Selection and Training

- Choose a Random Forest Classifier as the model.
- Scale the features using StandardScaler.
- Train the model on the training data.

## Model Evaluation

- Evaluate the trained model using accuracy, classification report, and confusion matrix.
- Identify areas of improvement and explore strategies to enhance the model's performance.

## Making Predictions

- Use the trained model to predict survival on the test dataset.
- Create a submission file for the predictions.

For more detailed information, refer to the Jupyter Notebook (`titanic_survival_prediction.ipynb`) in this repository.

