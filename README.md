<div align="center">
  <h1>🚜 BULLDOZER-PRICE-PREDICTION</h1>
  <p><i>Forecasts that Drive Smarter Bulldozer Sales Decisions</i></p>
</div>

<br>

<div align="center">
  <a href="YOUR_GITHUB_LINK">
    <img alt="Last Commit" src="https://img.shields.io/github/last-commit/brej-29/bulldozer-price-prediction">
  </a>
  <img alt="Jupyter Notebook" src="https://img.shields.io/badge/Notebook-Jupyter-orange">
  <img alt="Python Language" src="https://img.shields.io/badge/Language-Python-blue">
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-1.24+-blueviolet">
  <img alt="Pandas" src="https://img.shields.io/badge/Pandas-2.0+-teal">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-1.3+-yellowgreen">
</div>

<div align="center">
  <br>
  <b>Built with the tools and technologies:</b>
  <br>
  <br>
  <code>Python</code> | <code>NumPy</code> | <code>Pandas</code> | <code>Matplotlib</code> | <code>Scikit-Learn</code> | <code>Jupyter Notebook</code>
</div>

---

## **Table of Contents**
* [Overview](#overview)
* [Getting Started](#getting-started)
    * [Prerequisites](#prerequisites)
    * [Installation](#installation)
    * [Usage](#usage)
* [Data Exploration & Preprocessing](#data-exploration--preprocessing)
* [Modeling & Evaluation](#modeling--evaluation)
* [Model Deployment](#model-deployment)
* [License](#license)
* [Contact](#contact)

---

## **Overview**

This project is an entry for the <b>Kaggle competition, "Blue Book for Bulldozers"</b>. The core objective is to predict the auction sale price of bulldozers using a comprehensive dataset of historical sales records and equipment specifications.

The solution implements an <b>end-to-end machine learning pipeline</b> encompassing:
* <b>Handling of time-series data</b>.
* <b>Robust data cleaning and preprocessing</b> utilizing <code>scikit-learn</code> Pipelines.
* In-depth <b>exploratory data analysis</b> with insightful visualizations.
* Training and evaluation of diverse <b>regression models</b>.
* Efficient <b>hyperparameter tuning</b> using <code>RandomizedSearchCV</code>.
* Persistence of the optimal trained model for seamless future use.

<br>

### **Exploratory Data Analysis Highlights**

- **Sale Price Distribution:** The `SalePrice` exhibits a significant <b>right skew</b>, indicating a higher frequency of lower-priced sales. - **Missing Data Handling:** Strategic imputation techniques were applied to address missing values across various features.
- **Time-Based Analysis:**
    - No strong linear correlation was observed between `SaleDate` and `SalePrice`, suggesting other features are more influential.     - Median `SalePrice` by `SaleMonth` analysis suggests potential <b>seasonal influences</b>.     - <b>State-by-State Analysis</b>: The median sale price varies significantly across different states, with some states having consistently higher or lower prices than the national median. 
---

## **Getting Started**

### **Prerequisites**
To run this notebook, you will need the following libraries installed:
* `pandas`
* `numpy`
* `matplotlib`
* `scikit-learn`
* `joblib`
* `pyarrow` (or `fastparquet`)

### **Installation**
You can install all necessary libraries using `pip`:
pip install pandas numpy matplotlib scikit-learn joblib pyarrow

### **Usage**
1. Clone the repository: `git clone https://github.com/brej-29/bulldozer-price-prediction.git`
2. Navigate to the project directory: `cd bulldozer-price-prediction`
3. Open the Jupyter Notebook: `jupyter notebook`
4. Run the cells in the notebook to reproduce the analysis and model.

---

## **Modeling & Evaluation**
A <b>`scikit-learn` Pipeline</b> was constructed to seamlessly integrate data preprocessing with various regression models. Model performance was rigorously evaluated using key metrics such as <b>Mean Absolute Error (MAE)</b> and the <b>R-squared (R²) score</b>.

---

## **Model Deployment**
The final, fine-tuned model is persisted using `joblib`, enabling easy loading and utilization for future price predictions on new bulldozer data.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## **Contact**
If you have any questions or feedback, feel free to reach out to me via my [LinkedIn Profile](https://www.linkedin.com/in/brejesh-balakrishnan-7855051b9/).
