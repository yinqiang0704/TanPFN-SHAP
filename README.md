# TanPFN-SHAP
1. Install Dependencies
bash
pip install -r requirements.txt
2. Data Preparation
Place the ed38976-edd.csv file in the project root directory.

3. Execution Order
Run the Jupyter notebooks strictly in the following order:

01_data_preprocessing.ipynb - Data preprocessing and feature engineering

02_regression_model.ipynb - Regression model training and evaluation

03_shap_analysis.ipynb - SHAP feature importance analysis

File Structure
📁 Core Analysis Files
File	Description	Input	Output
01_data_preprocessing.ipynb	Data cleaning, missing value handling, feature encoding, and normalization	ed38976-edd.csv	Preprocessed dataset
02_regression_model.ipynb	Regression model training, hyperparameter optimization, performance evaluation	Preprocessed data	Trained model, prediction results
03_shap_analysis.ipynb	SHAP value calculation, feature importance analysis, result visualization	Trained model and data	SHAP values, feature importance plots

📁 Configuration & Documentation
LICENSE - Apache License 2.0

README.md - This documentation file

requirements.txt - Python package dependencies

Data Description
📊 Dataset Overview
This study uses the EDD dataset (ed38976-edd.csv). Key variables include:

Target variable: disengagement_score → transformed to engagement_score (1 - disengagement_score)

Feature variables: Learning style, experience level, topic category, difficulty level, etc.


🔒 Data Access
Complete dataset included: ed38976-edd.csv

Data anonymized: No personally identifiable information

PLOS-compliant: Available under CC-BY license
