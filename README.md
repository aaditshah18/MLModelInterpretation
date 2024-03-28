# Model Interpretability

## Overview

This repository contains a Jupyter Notebook focusing on model interpretability techniques in machine learning. The notebook covers various methods to interpret machine learning models, including linear models, tree-based models, and SHAP (SHapley Additive exPlanations) analysis. The main objective is to understand and interpret the relationships between input features and the target variable, providing insights into how the models make predictions.

### Key Highlights

- **Linear Model Interpretation:** Analyzes the regression coefficients of a linear model to understand the impact of each feature on the target variable.
  
- **Tree-Based Model Interpretation:** Examines the decision nodes of a tree-based model to visualize the decision-making process.

- **AutoML:** Utilizes automated machine learning (AutoML) techniques to identify and select the best-performing model based on predefined evaluation metrics.

- **SHAP Analysis:** Applies SHAP (SHapley Additive exPlanations) analysis to interpret the models' predictions and understand the importance of each feature in contributing to the predictions.

## About the Dataset

### Aim
To predict the total non-violent crimes per 100K population.

### Features (X)

#### Numerical Features:
- `population`: Total population in the district.
- `householdsize`: Average household size in the district.
- `racepctblack`: Percentage of the population that is Black.
- `racePctWhite`: Percentage of the population that is White.
- `racePctAsian`: Percentage of the population that is Asian.
- `racePctHisp`: Percentage of the population that is Hispanic.
- `agePct12t21`: Percentage of the population aged 12 to 21.
- `agePct12t29`: Percentage of the population aged 12 to 29.
- ... (more features listed)

#### Categorical Features:
- (List of categorical features)

### Target Variable (Y)
- Numerical Target Variable: Total non-violent crimes per 100K population

## Contents of the Notebook
- Linear model fitting and coefficient interpretation
- Tree-based model fitting and node interpretation
- AutoML model selection
- SHAP analysis on models from steps 1, 2, and 3
