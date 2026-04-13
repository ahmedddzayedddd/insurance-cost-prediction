# 🏥 Medical Insurance Cost Prediction

Predict medical insurance charges using Machine Learning based on patient details.
## Problem
Insurance companies need accurate cost estimates. This model predicts charges based on age, BMI, smoking status, and more.

## Dataset
- Source: Medical Cost Personal Dataset (Kaggle)
- 1,338 patients | 7 features

## Models Compared
| Model | R² Score |
|-------|----------|
| Linear Regression | 0.7836 |
| Ridge Regression | 0.7836 |
| XGBoost | 0.8554 |
| Random Forest | 0.8634 |
| *Gradient Boosting* | *0.8793* ✅ |

## Best Model Results
| Metric | Value |
|--------|-------|
| R² Score | 0.8793 |
| MAE | $2,404.90 |
| RMSE | $4,328.15 |

## Key Findings
- Smokers pay ~4x more than non-smokers
- BMI and age are the strongest cost predictors

## Interactive Demo
Built with Gradio - enter patient details and get instant cost prediction

## Tools
Python | Pandas | Scikit-learn | XGBoost | Matplotlib | Seaborn | Gradio
