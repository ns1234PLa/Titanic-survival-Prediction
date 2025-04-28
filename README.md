
# Titanic Dataset - Machine Learning Project

## Overview
This project leverages machine learning to predict the survival of passengers aboard the RMS Titanic, based on various passenger attributes such as age, class, sex, family size, and fare. The Titanic dataset, available on [Kaggle](https://www.kaggle.com/competitions/titanic), is a classic machine learning problem and is widely used for classification tasks. By applying various feature engineering techniques and models, the goal is to develop a predictive model that accurately classifies whether a passenger survived or not.

The dataset includes both numerical and categorical data, and the project demonstrates preprocessing steps such as handling missing values, encoding categorical features, and creating new features to enhance model performance. Different machine learning algorithms, including XGBoost, are used to build the final model.

## Dataset

## Dataset
Features:
- **PassengerId**: Unique identifier
- **Pclass**: Passenger class
- **Sex**: Gender
- **Age**: Age of passenger
- **SibSp**: Number of siblings/spouses
- **Parch**: Number of parents/children
- **Fare**: Ticket fare
- **Embarked**: Port of embarkation
- **Survived**: Survival status (0 = No, 1 = Yes)

## Features Engineering
- Extracted titles from names.
- Created family size and alone indicators.
- Binned age and fare.
  
## Models Used
- Logistic Regression
- Random Forest
- XGBoost

Final predictions were made using **XGBoost**.

## How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/titanic-dataset.git
