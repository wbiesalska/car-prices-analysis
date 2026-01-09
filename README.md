# Analysis of factors affecting the price of cars in USA

## Project Overview

This project analyzes key factors influencing the prices of passenger cars using statistical analysis and machine learning models. The goal was to identify the most important features affecting car prices and to evaluate different classification models in terms of predictive performance and interpretability.

Source: https://www.kaggle.com/datasets/krishanukalita/vehicle-sales-cleaned

## Methodology

- Data preprocessing and exploratory data analysis (EDA)
- Training and evaluation of multiple classification models (decision tree, random forest, neural networks)
- Model comparison using ROC curves and AUC metrics

## Model Selection

Among the evaluated models, the Decision Tree classifier was selected as the final model due to:
- High and stable AUC values across training, validation, and test sets
- Strong generalization performance
- High interpretability, allowing clear identification of key price drivers

## Key Insights

The analysis identified the following features as the most influential in determining car prices:
- Mileage (odometer) – lower mileage is strongly associated with higher vehicle value
- Seller – trusted and well-known sellers tend to list cars at higher prices
- Car model – brand reputation, equipment level, and market segment significantly impact pricing
- Vehicle condition – better technical condition and service history increase market value
These factors directly influence vehicle reliability, ownership cost, and buyer confidence.

## Technologies Used

- Python (panda, NumPy, scikit-learn, matplotlib)
- SAS
