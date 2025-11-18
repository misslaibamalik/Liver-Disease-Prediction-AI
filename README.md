# Early Liver Disease Prediction Using Machine Learning by Laiba Malik

## Motivation
In January 2023, my father passed away from liver cancer because Pakistan lacked affordable early diagnostic tools and timely liver transplant facilities. This project is my first practical step toward building low-cost, AI-powered screening systems that can run on basic clinic computers in developing countries exactly what I want to advance during my Master's in AI under the Global Korea Scholarship 2026.

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
