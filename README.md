# Wine Quality Prediction

A supervised machine learning project that predicts wine quality ratings using physicochemical properties of wine samples.

## Overview

This project builds a classification pipeline on the Wine Quality dataset to predict a quality score (0–10) based on measurable chemical attributes. The goal is to automate quality assessment using data-driven methods rather than manual tasting alone.

## Dataset

- **Source**: UCI Machine Learning Repository — Wine Quality Dataset
- **Features**: Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol
- **Target**: Quality score (integer, 0–10)

## Approach

1. **Exploratory Data Analysis** — distribution plots, correlation heatmap, class balance check
2. **Preprocessing** — outlier removal using IQR method, feature scaling with StandardScaler, train/test split (80/20)
3. **Modelling** — trained and compared multiple classifiers (Logistic Regression, Decision Tree, Random Forest)
4. **Evaluation** — accuracy score, confusion matrix, classification report

## Results

Random Forest achieved the best performance with high classification accuracy on the test set.

## Tech Stack

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

## How to Run

1. Open the notebook in Google Colab
2. Upload `winequality.csv` when prompted
3. Run all cells in order

## Files

| File | Description |
|------|-------------|
| `wine_quality_prediction.ipynb` | Main Colab notebook |
| `winequality.csv` | Dataset |
