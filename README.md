# Car Price Prediction – End-to-End Machine Learning Project

This project builds and evaluates multiple machine learning models to predict **used car prices** based on vehicle characteristics.  
It follows a **proper ML workflow**: EDA → cleaning → splitting → encoding & scaling → model selection with cross-validation → evaluation → interpretability with SHAP.

##  Project Structure

├── car_prices_dataset.csv # Raw dataset
├── project_notebook.ipynb # Full analysis and modeling notebook
├── README.md # Project documentation
├── pyproject.toml # Dependencies & environment
├── uv.lock # Dependency lock file
├── .python-version # Python version
├── .gitignore

## Objective

Predict the **market price of used cars** using structured tabular data while:
- comparing multiple regression models fairly
- handling missing values correctly
- avoiding data leakage
- interpreting the final model using SHAP