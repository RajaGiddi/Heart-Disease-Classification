# Heart-Disease-Classification

## Overview
This project focuses on the development of machine learning models to classify stages of heart disease based on a variety of health indicators. This repo contains the Google Colab copy of my implementation of a heart disease classification program. it includes the EDA as well as model implementation with some notes.


## Exploratory Data Analysis (EDA)

Key findings from our EDA include:

- Demographics: Examined age, gender, and other factors to identify potential correlations with heart disease.
- Health Indicators: Analyzed relationships between health metrics (e.g., cholesterol, blood pressure) and heart disease.
- Major Vessels and Heart Disease:
- Positive trend between the number of detected major vessels and heart disease stages.
- Increased uncertainty with more than two detected vessels.
- Age and Cholesterol: Found a weak relationship, suggesting other factors may influence cholesterol's impact on heart disease.

## Data Preprocessing
The preprocessing phase involved several critical steps to prepare the dataset for model development:

- **Data Cleaning**:
  - Identified and removed outliers.
  - Handled missing values through imputation or exclusion.

- **Normalization/Standardization**:
  - Applied techniques to scale numerical features.

- **Categorical Data Encoding**:
  - Converted categorical variables using one-hot encoding or label encoding.

- **Feature Selection**:
  - Selected relevant features using statistical methods and domain knowledge.

- **Data Splitting**:
  - Divided the dataset into training and testing sets.

