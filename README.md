# Titanic Survival Prediction

## Overview

This project uses Machine Learning to predict whether a passenger survived the Titanic disaster.

A Logistic Regression classification model was trained using passenger class, gender, age, and fare.

## Objective

The main objective of this project is to understand and implement a complete Machine Learning classification workflow using a real-world dataset.

## Dataset

The Titanic dataset contains information about 891 passengers.

### Features Used

- 'pclass' — Passenger class
- sex' — Passenger gender
- 'age' — Passenger age
- 'fare' — Ticket fare

### Target

- `survived`
  - `0` → Did not survive
  - `1` → Survived

## Data Preprocessing

The following preprocessing steps were performed:

- Checked the dataset structure and missing values
- Filled missing age values using the median age
- Converted gender into numerical values
  - Male → 0
  - Female → 1
- Selected relevant features for the model
- Split the dataset into training and testing sets

## Exploratory Data Analysis

A survival count plot was created to understand the distribution of survived and non-survived passengers.

## Machine Learning Model

### Logistic Regression

Logistic Regression was used because this is a binary classification problem.

The dataset was divided into:

- 80% training data
- 20% testing data

## Model Performance

| Metric | Score |
|---|---:|
| Accuracy | 80.45% |
| Precision | 78.26% |
| Recall | 72.97% |
| F1 Score | 75.52% |

### Confusion Matrix

```text
[[90 15]
 [20 54]]
