# Machine Learning Model Analysis Project
## Overview
This project consists of multiple Python scripts aimed at analyzing machine learning models, evaluating their performance using various metrics, and visualizing the results. The project includes scripts for:
- Data processing and feature enginerring
- VAR and IRF Analysis
- Modelling and Evaluation
- Price and robustness analysis
- SHAP Analysis


## Installation
### Prerequisites
Ensure you have Python 3.8 or later installed. Recommended to set up a virtual environment.
python -m venv venv
source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'

## Install Dependencies
### Run the following command to install required Python libraries:
pip install -r requirements.txt

## File Structure Created
| \
|- Models \
|- Metrics \
|- Train_{month} \
|- Val_{month} \
|- Test_{month}

## Usage
Each script serves a specific purpose in model analysis. Below is a brief description:
1. Data processing and feature enginerring
python src/Data_Processing_and_Feature_Enginerring.py
Downloads the data from Databento and create features - as well as data preprocessing and cleaning
2. VAR and IRF Analysis
python src/Vector_Autoregression_and_Impulse_Response_Analysis.py
Create the baseline to calculate the VAR price impacts and other analysis
3. Modelling
python src/Model_Training_And_Evaluation.py
Train different models - including RF, Ridge, GBT etc.
4. Price and robustness analysis
python src/Price_Impact_Model_Analysis.py
Developed different lags and see an analysis of how models respond as well as see different lags
5. SHAP Analysis
python src/SHAP_Analysis.py
Calculate feature importance for each model and check which features are important
