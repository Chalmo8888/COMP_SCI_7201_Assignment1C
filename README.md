# COMP_SCI_7209_Assignment1

Overview

This repository contains the implementation, data, and replication materials for Assignment 1 (Parts A–D) of COMP SCI 7209. The project investigates the impact of severe weather events on U.S. crop revenues (silage corn and soybean) using integrated NOAA SWDI weather data and USDA NASS crop statistics.

The analysis follows a reproducible big-data pipeline, combining data preprocessing, feature engineering, and multiple machine learning models to evaluate predictive performance.

Repository Structure

Assignment_1_PartC.ipynb
Jupyter Notebook with full implementation:

Data preprocessing and integration

Model training (Linear Regression, Decision Tree, Random Forest, SVR, XGBoost)

Hyperparameter tuning (GridSearchCV)

Model evaluation (R², MSE, RMSE, MAE, MAPE)

final_data.csv
Consolidated dataset combining NOAA SWDI event indicators with USDA NASS crop revenue data.

README.md
Instructions for setup, dependencies, and execution.

Supporting files
Intermediate outputs and references to raw NOAA/USDA datasets for reproducibility.

Installation and Setup

Clone the repository:

git clone https://github.com/Chalmo8888/COMP_SCI_7201_Assignment1C.git
cd COMP_SCI_7201_Assignment1C


Create a Python environment (recommended: Python 3.10+).

Install dependencies:

pip install -r requirements.txt

Usage

Open the Jupyter Notebook:

jupyter notebook Assignment_1_PartC.ipynb


Run all cells to reproduce the results, including:

Data preprocessing

Model training and tuning

Performance evaluation (tables and figures)

Output tables and plots will be generated directly in the notebook.

Data Sources

NOAA SWDI – Severe Weather Data Inventory (hail, TVS, MDA, lightning)

USDA NASS – Crop yields and prices (silage corn, soybean)

U.S. Census Bureau – TIGER/Line shapefiles for geographic mapping

Results

Corn revenue: Models performed poorly (all negative R²).

Soybean revenue: Random Forest achieved the best performance (R² ≈ 0.27, MAPE ≈ 41%).

Key insight: Severe weather indicators provide limited explanatory power, highlighting the need for finer-grained data and advanced modelling.

License

This project is for academic use under COMP SCI 7209.
