# sm-AI-task3-titanicML

## Overview

This task involves predicting survival on the Titanic using machine learning techniques. The model is built using logistic regression, and the performance is evaluated using accuracy as the primary metric.

## Dataset Features

- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Target variable indicating survival (1) or not (0).
- **Pclass**: Passenger class (1, 2, or 3).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings or spouses aboard.
- **Parch**: Number of parents or children aboard.
- **Ticket**: Ticket number.
- **Fare**: Fare paid by the passenger.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Steps

1. **Data Preprocessing**
   - Handle missing values.
   - Encode categorical variables.
   - Remove irrelevant features like `Ticket` and `Cabin`.

2. **Model Training**
   - Train a Logistic Regression model on the processed data.

3. **Model Evaluation**
   - Evaluate the model using accuracy score.
  
## Accuracy

The achieved accuracy of the model is **0.8013**.

<img width="660" alt="Screen Shot 1446-01-26 at 1 46 24 AM" src="https://github.com/user-attachments/assets/5213b43f-f80b-4691-a7b5-3c6f4dbeff4f">

