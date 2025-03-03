# Machine Learning Model Analysis Project
## Overview
This project consists of multiple Python scripts aimed at analyzing machine learning models, evaluating their performance using various metrics, and visualizing the results. The project includes scripts for:
- Model training and evaluation
- Price impact analysis using ML models
- SHAP value interpretation
- Evaluation metric table generation
- Best model analysis with visualization
- VAR (Vector AutoRegression) modeling


## Installation
### Prerequisites
Ensure you have Python 3.8 or later installed. Recommended to set up a virtual environment.
python -m venv venv
source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'

## Install Dependencies
### Run the following command to install required Python libraries:
pip install -r requirements.txt

## Usage
Each script serves a specific purpose in model analysis. Below is a brief description:
1. Training Runner
python src/training_runner_notebook.py
Automates the training of ML models using different datasets. It saves trained models for further evaluation and comparison.
2. Best Model Analysis
python src/best_model_analysis.py
Evaluates various ML models based on their performance metrics such as Mean Squared Error (MSE) and R². It selects the best-performing model among a given set.
3. Best Model Analysis Charts
python src/best_model_analysis_charts.py
Generates visualizations comparing different ML models' performance. It includes scatter plots for predictions vs. actual values and residual analysis.
4. SHAP Analysis
python src/shap_analysis.py
Uses SHAP values to explain ML model predictions by analyzing feature importance and their contributions to predictions.
5. Price Impact Analysis
python src/ml_price_impact.py
Analyzes the impact of ML models on financial price movements. It predicts price impact and compares actual vs. predicted values to assess accuracy.
6. Evaluation Metrics Table
python src/evaluation_metrics_table.py
Constructs a tabular summary of evaluation metrics for different ML models, providing a structured comparison of their performance.
7. VAR (Vector AutoRegression) Analysis
python src/var_analysis.py
Implements Vector AutoRegression (VAR) modeling to analyze the dependencies between multiple time series variables.
