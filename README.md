# Early Liver Disease Prediction Using Machine Learning by Laiba Malik

[![Python](https://img.shields.io/badge/Python-3.9-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)
[![Forks](https://img.shields.io/github/forks/misslaibamalik/Liver-Disease-Prediction-AI?style=social)](https://github.com/misslaibamalik/Liver-Disease-Prediction-AI/fork)
[![Stars](https://img.shields.io/github/stars/misslaibamalik/Liver-Disease-Prediction-AI?style=social)](https://github.com/misslaibamalik/Liver-Disease-Prediction-AI/stargazers)

## Motivation
My father suffered from liver cancer, and the lack of affordable early diagnostic tools in Pakistan deeply affected our family. This experience inspired me to develop low-cost, AI-powered screening systems using routine blood tests — a small step toward preventing such outcomes in developing countries.

## Dataset
Indian Liver Patient Dataset (public)  
Source: https://www.kaggle.com/datasets/uciml/indian-liver-patient-records  
583 patient records | 10 clinical features (Age, Gender, Total Bilirubin, Alkaline Phosphatase, Albumin, etc.)

## Models & Results
| Model              | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 71.8%    | 0.74      | 0.92   | 0.82     |
| Random Forest      | 76.2%    | 0.78      | 0.93   | 0.85     |
| XGBoost            | **78.4%**| **0.80**  | **0.94**| **0.86** |

SHAP explanations show which blood markers matter most → doctors can understand the model easily.

## Technologies Used
Python, Pandas, Scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebook/Liver_Disease_Prediction.ipynb
