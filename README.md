# ml-building-energy-predictor
A Machine Learning application that predicts the Heating Load of residential buildings based on architectural and energy-related parameters.

The project uses a trained Random Forest Regression model with SelectKBest feature selection to estimate building energy efficiency from user inputs such as:

Relative Compactness
Building Type
Surface Area
Wall Area
Roof Area
Overall Height
Glazing Area Ratio

The web interface is developed using Django and allows users to enter building parameters through an interactive form and instantly receive:

Predicted Heating Load (kWh/m²)
Energy Efficiency Rating
Technologies Used
Python
Django
Scikit-learn
Pandas
NumPy
Pickle
Machine Learning Workflow
Data Preprocessing
Feature Selection using SelectKBest
Model Comparison
Random Forest Regression
Model Serialization using Pickle
Features
Real-time Prediction
Energy Rating Classification
Output

The system predicts the building heating demand and classifies the building into an efficiency category such as:

A — Very Efficient
B — Efficient
C — Moderate
D — High Energy Use

This project demonstrates the integration of Machine Learning models for sustainable building analysis and energy prediction.
