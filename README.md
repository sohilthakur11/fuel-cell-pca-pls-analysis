# Fuel Cell Performance Analysis using PCA and PLS

A Process Data Analytics project focused on analyzing Hydrogen Fuel Cell Stack performance using Principal Component Analysis (PCA) and Partial Least Squares (PLS) Regression.

## Overview

This project investigates the effect of operating parameters on hydrogen fuel cell performance using multivariate statistical analysis.

The workflow includes

- Data preprocessing
- Feature scaling
- PCA
- PLS Regression
- Performance visualization

## Dataset

Source:
Hydrogen Fuel Cell Stack Dataset (Kaggle)

Observations:
26,930

Features

- Temperature
- Hydrogen Flow
- Pressure
- Voltage
- Outcome

## Methodology

1. Feature Selection
2. Data Standardization
3. Principal Component Analysis
4. Partial Least Squares Regression
5. Model Evaluation

## Results

- First two principal components captured **93.38%** of total variance.
- Temperature and Hydrogen Flow were identified as the dominant operating parameters.
- Developed a PLS regression model achieving **R² = 0.55**.

## Repository Structure

data/
src/
images/
docs/

## Technologies

Python

Pandas

NumPy



Jupyter Notebook
