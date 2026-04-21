# bank-marketing-predictor
End-to-end machine learning pipeline for predicting marketing take ups
## Project Overview
This repository contains an end-to-end machine learning pipeline designed to predict whether a customer targeted during a marketing campaign will take up a new product. The project includes data cleaning, feature engineering, handling imbalanced data (SMOTE), and model optimization (focusing on maximizing Class 1 Recall/Precision/F1 Score via custom thresholding). 

**The final selected model is LightGBM operating at a 0.218 decision threshold.**

## How to Reproduce the Results
1. Clone this repository to your local machine.
2. Create a virtual environment and install the dependencies:
   `pip install -r requirements.txt`
3. Run the notebooks sequentially:
   * `001_exploratory_data_analysis.ipynb` 
   * `002_feature_engineering.ipynb`
   * `003_model_development.ipynb`
  
4. The following notebook contains a short answer to address Problem Statement 2:
  * `004_Problem_2_high_level_overview.ipynb`
