# Bayesian Inference for Breast Cancer Diagnosis

An exploration of Bayesian Neural Networks (BNNs) and probabilistic modeling to classify tumor malignancy, with a strong emphasis on uncertainty quantification for high-stakes medical diagnostics.

## 📌 Overview
In critical domains like healthcare, point estimates from traditional neural networks are often insufficient. This project implements Bayesian inference techniques to evaluate the Wisconsin Breast Cancer dataset, providing not just malignancy classifications, but the mathematical confidence behind each prediction. 

By comparing Bayesian (Maximum a Posteriori) and Frequentist (Maximum Likelihood Estimation) approaches, this repository demonstrates how informative priors can regularize models and prevent overfitting on constrained clinical datasets.

## 🔬 Key Features
* **Bayesian Neural Networks (BNNs):** Custom PyTorch implementation for malignancy classification.
* **Uncertainty Quantification:** Rigorous probabilistic evaluation to improve diagnostic reliability.
* **Comparative Statistical Analysis:** Direct evaluation of MAP vs. MLE estimation for model regularization.
* **Posterior Distribution Analysis:** Visualization pipelines to extract interpretable clinical insights, identifying key predictors such as mean concave points and radius error.

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning:** PyTorch
* **Data Processing & Math:** NumPy, Pandas
* **Statistical Visualization:** Seaborn, Matplotlib

## 📊 Methodology & Results
1. **Exploratory Data Analysis (EDA):** Identified highly correlated features (`concave points`, `radius error`) using correlation heatmaps.
2. **Model Training:** Implemented BNNs and Bayesian Logistic Regression.
3. **Evaluation:** Mapped posterior distributions of model weights to determine feature importance and clinical confidence intervals.

### Exploratory Data Analysis
![Feature Correlation Heatmap](heatmap.png)

### Model Performance Comparison
![Bayesian vs Frequentist Performance](comp.png)
