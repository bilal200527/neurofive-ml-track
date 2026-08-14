# Titanic Survival Prediction using Logistic Regression

## Project Overview

This project uses Machine Learning to predict whether a Titanic passenger
survived or did not survive. Logistic Regression was used as the
classification algorithm.

## Dataset

The Titanic dataset contains passenger information such as:

- Passenger class
- Sex
- Age
- Number of siblings/spouses
- Number of parents/children
- Fare
- Port of embarkation
- Survival status

## Data Preprocessing

The dataset was cleaned during the EDA stage. Categorical variables such
as Sex and Embarked were converted into numerical features using one-hot
encoding.

## Features Used

- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

## Train-Test Split

The dataset was divided into:

- 80% training data
- 20% testing data

The split was performed using `train_test_split` from scikit-learn.

## Machine Learning Model

Logistic Regression was used because the target variable is binary:

- 0 = Did not survive
- 1 = Survived

## Model Evaluation

The model was evaluated using `accuracy_score` and a confusion matrix.

### Final Accuracy

**80.45%**

### Confusion Matrix

```text
[[98 12]
 [23 46]]
