# Ensemble Learning and feature selection for Phishing Detection

## Overview
This project implements a phishing detection system leveraging machine learning techniques. The ensemble model combines the strengths of Random Forest (RF) and LightGBM classifiers, improving detection accuracy and robustness against phishing attacks. Feature selection and visualization techniques are also employed to enhance model interpretability and performance.

## Key Features
- **Data Cleaning and Preprocessing**: Removal of missing values and preparation of the dataset for analysis.
- **Feature Selection**: Identification and visualization of the most important features contributing to phishing detection.
- **Machine Learning Models**:
  - Random Forest (RF)
  - LightGBM (LGB)
  - Stacked Ensemble Model (Logistic Regression on RF + LGB predictions)
- **Visualization**:
  - Feature importance bar plots
  - Box and violin plots for feature analysis
  - Metric comparison through bar and line graphs
- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1 Score

## Dataset
The dataset contains features extracted from URLs and their associated labels (`phishing`). Ensure the file `dataset_full.csv` is present in the `data` directory.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/phishing-detection-ensemble.git
   cd phishing-detection-ensemble
