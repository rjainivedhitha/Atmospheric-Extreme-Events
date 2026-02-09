#Machine Learning-Based Characterization of Compound Atmospheric Extreme Events

📌 Overview

This repository contains the implementation and documentation of a machine learning framework for detecting and characterizing compound atmospheric extreme events using multivariate severity indexing, uncertainty quantification, and explainability analysis.

The project integrates statistical methods and modern machine learning techniques to analyze extreme weather patterns and identify high-risk atmospheric regimes. It supports interpretable and uncertainty-aware climate risk assessment.

This work forms the basis of a journal submission in the field of climate data analysis and environmental informatics.

🎯 Objectives

Construct a multivariate Extreme Weather Severity Index (EWSI)
Detect extreme and compound atmospheric events
Classify extreme regimes using Random Forest
Visualize climatic regimes using UMAP and t-SNE
Quantify prediction uncertainty using entropy
Interpret model predictions using SHAP analysis
Provide physically meaningful explanations of extreme events
📊 Dataset

The dataset consists of long-term meteorological observations, including:

Wind Speed
Surface Pressure
Rainfall
Data preprocessing includes:

Quality control
Missing value handling
Forward filling
Percentile-based normalization
Feature scaling
Due to data licensing and privacy policies, the raw dataset is not publicly shared in this repository.

⚙️ Methodology

1. Preprocessing

Outlier detection
Normalization
Temporal alignment
2. Severity Index (EWSI)

Percentile-based normalization
Linear aggregation of variables
Threshold-based extreme detection
3. Feature Engineering

Lagged variables
Derived physical features
Correlation filtering
4. Classification

Random Forest ensemble
Balanced class weights
Hyperparameter tuning
5. Visualization

UMAP
t-SNE
Regime clustering
6. Uncertainty Analysis

Entropy-based uncertainty
Probability distributions
7. Explainability

SHAP feature importance
SHAP interaction analysis
🛠️ Requirements

Recommended environment:

Python 3.8+
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
SHAP
UMAP-learn
Install dependencies using:

pip install -r requirements.txt
