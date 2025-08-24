BULLDOZER-PRICE-PREDICTION
Forecasts that Drive Smarter Bulldozer Sales Decisions

<br>

<a href="[your_github_link]"><img alt="Last Commit" src="https://www.google.com/search?q=https://img.shields.io/github/last-commit/Mubashir-Rao/Bulldozer-Price-Prediction"></a>
<img alt="Jupyter Notebook" src="https://www.google.com/search?q=https://img.shields.io/badge/Notebook-Jupyter-orange">
<img alt="Python Language" src="https://www.google.com/search?q=https://img.shields.io/badge/Language-Python-blue">

Built with the tools and technologies:

Python

NumPy

Pandas

Matplotlib

Scikit-Learn

Jupyter Notebook

Table of Contents
Overview

Getting Started

Prerequisites

Installation

Usage

Data Exploration & Preprocessing

Modeling & Evaluation

Model Deployment

License

Contact

Overview
This project is an entry for the Kaggle competition, "Blue Book for Bulldozers". The objective is to predict the sale price of bulldozers sold at auction based on historical sales data.

The solution is an end-to-end machine learning pipeline that:

Handles time-series data.

Cleans and preprocesses data using scikit-learn pipelines.

Explores and visualizes data to uncover insights. * Trains and evaluates a variety of regression models.

Tunes model hyperparameters using RandomizedSearchCV.

Exports the trained model for future use.

<br>

Exploratory Data Analysis
The initial data exploration revealed several key insights:

Data Distribution: The SalePrice is highly skewed to the right, indicating most sales are at lower prices.

Missing Data: Several columns contain a significant number of missing values that require imputation.

Time-based Relationships:

A plot of SalePrice vs. SaleDate showed no clear linear correlation, suggesting other features are more influential.

The median SalePrice by SaleMonth shows some seasonality, with prices being higher in the early part of the year.

State-by-State Analysis: The median sale price varies significantly across different states, with some states having consistently higher or lower prices than the national median.

Getting Started
Prerequisites
To run this notebook, you will need the following libraries installed:

pandas

numpy

matplotlib

scikit-learn

joblib

pyarrow (or fastparquet)

Installation
You can install all necessary libraries using pip:

Bash

pip install pandas numpy matplotlib scikit-learn joblib pyarrow
Usage
Clone the repository: git clone https://github.com/Mubashir-Rao/Bulldozer-Price-Prediction.git

Navigate to the project directory: cd Bulldozer-Price-Prediction

Open the Jupyter Notebook: jupyter notebook

Run the cells in the notebook to reproduce the analysis and model.

Modeling & Evaluation
A scikit-learn Pipeline was used to streamline the workflow, combining data preprocessing with model training. The models were evaluated using Mean Absolute Error (MAE) and the R-squared (R 
2
 ) score.

Model Deployment
The final trained model is saved using joblib for future use. This allows the model to be loaded and used for new predictions without the need for retraining.

License
This project is licensed under the MIT License. See the LICENSE.md file for details.

Contact
If you have any questions or feedback, feel free to reach out to me via my [LinkedIn Profile]([Your LinkedIn Profile Link]).
