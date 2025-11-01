

# Project Title❤️ Heart Disease Prediction using Gradient Boosting and XGBoost
## 📘 Introduction

This project demonstrates how Gradient Boosting (GB) and XGBoost (Extreme Gradient Boosting) can be applied to predict whether a person has heart disease based on various medical attributes.
It showcases model training, evaluation, and optimization for robust predictive performance.

A brief description of what this project does and who it's for

## 🔍 Project Overview

-- This notebook (GB_XGB_Boosting.ipynb) explores the concepts of ensemble learning, focusing on Boosting — a technique that combines weak learners sequentially to reduce bias and variance.

The project compares:

Gradient Boosting (GBM) – Sequentially improves model performance using gradient descent on residuals.

XGBoost – An optimized, parallelized, and regularized version of gradient boosting designed for performance and scalability.

## ⚙️ Installation
* Prerequisites

* Ensure you have Python 3.8+ installed.

--  Install the required dependencies:

* pip install numpy pandas seaborn matplotlib scikit-learn xgboost


Or use:

* pip install -r requirements.txt

## 🚀 Usage

 -Clone or download the project:

git clone https://github.com/yourusername/heart-disease-xgboost.git
cd heart-disease-xgboost


* Place the dataset (heart.csv) in the same directory as the notebook.

* Open and run the notebook:

* jupyter notebook "GB_XGB_Boosting.ipynb"


-- The notebook will:

* Load and explore the dataset

* Train models using Gradient Boosting and XGBoost

* Evaluate accuracy, confusion matrix, and feature importance

## 🧾 Dataset

--- File: heart.csv
Description: Contains medical and demographic features to predict heart disease presence.

--- Example columns:

## Feature	Description
age	Age of the individual
sex	Gender (1 = male, 0 = female)
cp	Chest pain type
trestbps	Resting blood pressure
chol	Serum cholesterol level
fbs	Fasting blood sugar > 120 mg/dl
restecg	Resting electrocardiographic results
thalach	Maximum heart rate achieved
exang	Exercise-induced angina
oldpeak	ST depression induced by exercise
ca	Number of major vessels colored by fluoroscopy
thal	Thalassemia (blood disorder)
target	Presence of heart disease (1 = yes, 0 = no)
🌲 Modeling
Algorithms Implemented

* Gradient Boosting (GBM)

* XGBoost

-- Techniques Used

* Data preprocessing and normalization

_- Model training and tuning (hyperparameters like n_estimators, learning_rate, max_depth)

## Feature importance visualization

* Evaluation using:

* Accuracy

* Confusion matrix

* Classification report

* Why XGBoost Performs Well

* Regularization to prevent overfitting

* Inbuilt cross-validation

* Automatic handling of missing values

* Parallel computation for faster training

* Optimized memory usage for large datasets

## 📊 Results

-- Both models perform well, but XGBoost typically outperforms GBM in:

* Accuracy

* Computation speed

* Generalization on unseen data

* Example results (values are illustrative):

### Model	Accuracy	Precision	Recall
 ### Gradient Boosting	0.86	0.84	0.85
### XGBoost	0.90	0.89	0.88

## Visualizations include:

* Confusion matrix heatmaps

* Feature importance plots

## ✨ Features

- End-to-end boosting implementation for classification

- Comparison of GBM vs. XGBoost

 - Handles missing data and performs regularization

- Easy customization for other datasets

## 🧩 Troubleshooting
Issue	Possible Cause	Solution
FileNotFoundError: heart.csv	Dataset missing	Place heart.csv in the notebook directory
Low accuracy	Improper parameter tuning	Adjust learning rate or n_estimators
Plots not displayed	Matplotlib not installed	Run pip install matplotlib