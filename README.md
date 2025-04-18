# Employee Attrition Analysis

This project explores a real-world employee attrition dataset using machine learning techniques. The objective is to understand key factors behind attrition and to develop a predictive model that can help in employee retention strategies.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Overview

This project focuses on analyzing and predicting employee attrition using machine learning techniques. The dataset is sourced from an HR system and includes various demographic, job-related, and compensation-related features. The goal is to identify patterns leading to employee turnover and build a model that can predict attrition risk.
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Encoding and Engineering
- Model Building with scikit-learn
- Evaluation using accuracy and classification metrics

## Dataset
```
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
```
It includes employee information such as:

- Demographics: Age, Gender, Marital Status
- Work Information: Job Role, Department, Business Travel
- Compensation: Monthly Income, Stock Option Level
- Work-life Balance and Environment Satisfaction
- Target: Attrition (Yes/No)

## Preprocessing

- Dropped irrelevant columns: `EmployeeCount`, `EmployeeNumber`, `Over18`, `StandardHours`
- Label encoding used for categorical features and target (`Attrition`)
- Feature selection based on value counts and correlation analysis

## Exploratory Data Analysis

Key insights visualized:

- Attrition rate across age groups, departments, and roles
- Heatmaps showing correlation between features
- Bar plots and distribution charts for categorical and numerical features

## Modeling

The notebook uses various classification algorithms from `scikit-learn`. At least one of the following was likely applied:

- Logistic Regression
- Random Forest

Data was split into training and test sets, and metrics like accuracy and confusion matrix were calculated.

## Results

Performance metrics include:

- Accuracy Score 
- Classification Report (Precision, Recall, F1-Score)
- Confusion Matrix

## Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn hvplot
```

You also need Jupyter Notebook or Jupyter Lab to run the notebook.

## Usage

1. Clone or download this repository.
2. Open `Employee Attrition.ipynb` using Jupyter.
3. Ensure the dataset CSV is located at the expected path, or update the `pd.read_csv` path accordingly.





