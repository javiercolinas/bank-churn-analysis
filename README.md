# Bank Churn Analysis

This project analyzes customer churn in a banking dataset and builds a predictive model to identify the main factors influencing customer attrition.

## Project Structure

├── Data/

│ └── Bank Customer Churn Prediction.csv

├── Scripts/

│ ├── descriptive_analysis.ipynb

│ └── predictive_model.ipynb


## Objectives

- Explore the dataset to understand customer behavior
- Identify patterns related to churn
- Build a machine learning model to predict customer churn

## Descriptive Analysis

The `descriptive_analysis.ipynb` notebook includes:

- Data cleaning and inspection
- Analysis of numerical and categorical variables
- Grouped statistics (e.g. churn rate by feature)
- Feature segmentation (age groups, balance ranges, tenure, etc.)
- Visualizations:
  - Bar plots
  - Heatmaps
  - Violin plots
  - Box Plots
  - Scatter plots

The goal is to understand how different variables relate to churn and detect meaningful patterns.

## Predictive Modeling

The `predictive_model.ipynb` notebook includes:

- Data preprocessing:
  - Encoding categorical variables
  - Feature scaling
- Train-test split
- Model training using multiple algorithms:
  - Logistic Regression
  - Random Forest
- Model evaluation using metrics such as ROC-AUC
- Feature importance analysis

The objective is to build a model capable of predicting churn and to identify which variables contribute most to the prediction.

## Requirements

Main libraries used:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

Clone the repository and run the notebooks:

```bash
git clone https://github.com/javiercolinas/bank-churn-analysis.git
