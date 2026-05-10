# ML Building Energy Predictor

A Machine Learning application that predicts the **Heating Load of residential buildings** based on architectural and energy-related parameters.

---

## Project Overview

This project uses an LLM-generated dataset to train a Random Forest Regression model with SelectKBest feature selection to estimate building energy efficiency from user inputs such as:

* Relative Compactness
* Building Type
* Surface Area
* Wall Area
* Roof Area
* Overall Height
* Glazing Area Ratio

The deployment allows users to enter building parameters and instantly receive:

* Predicted Heating Load (kWh/m²)
* Energy Efficiency Rating

---

## Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* Pickle

---

## Machine Learning Workflow

* Data Preprocessing
* Feature Selection using SelectKBest
* Model Comparison
* Random Forest Regression
* Model Serialization using Pickle

---

## Features

* Real-time Prediction
* Energy Rating Classification
* Machine Learning Model Deployment
* Sustainable Building Energy Analysis

---

## Output

The system predicts the building heating demand and classifies the building into an efficiency category such as:

* **A — Very Efficient**
* **B — Efficient**
* **C — Moderate**
* **D — High Energy Use**

---

## Objective

* This project demonstrates the integration of Machine Learning modelsfor sustainable building analysis and energy prediction.
* This project is intended for educational and demonstration purposes.

---

## Author

**Fawad Saleem**
