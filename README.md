# Linear Regression: Medical Charges Prediction

## Overview
This notebook is a comprehensive walkthrough of building a Linear Regression model from scratch using Python and Scikit-learn. It covers the complete ML pipeline, from exploratory data analysis to model evaluation.

## Dataset
The dataset (`medical.csv`) contains information about 1,338 medical insurance customers, including age, sex, BMI, number of children, smoking status, region, and individual medical charges.

**Goal:** Predict the medical charges for new customers based on their features.

## What's Covered in This Notebook:
- **Exploratory Data Analysis (EDA):** Visualizing distributions and using correlation matrices.
- **Feature Engineering:** Handling categorical data (binary and one-hot encoding).
- **Feature Scaling:** Standardizing numeric variables to compare feature importance.
- **Modeling:** Training a Linear Regression model using Scikit-learn.
- **Evaluation:** Using Root Mean Squared Error (RMSE) and understanding the difference between training and test loss.

## Key Learnings & Takeaways
- **The Golden Rule:** Never evaluate a model on the data it was trained on (memorization vs. generalization).
- **The ML Pipeline:** Data exploration → Encoding/Scaling → Train/Test Split → Training → Evaluation.
- **Feature Importance:** Smoking status has a disproportionately massive impact on medical charges compared to age or BMI.

## Technologies Used
- Python
- Pandas & NumPy (Data Manipulation)
- Matplotlib, Seaborn & Plotly (Data Visualization)
- Scikit-learn (Machine Learning)
