# Exoplanet Detection Using Machine Learning

## Project Overview
Developed a supervised machine learning pipeline using NASA Kepler data to classify confirmed exoplanets and false-positive observations.

## Machine Learning Models
- Logistic Regression
- Random Forest Classifier
- Histogram-Based Gradient Boosting Classifier

## Methodology
- Missing-value imputation and feature scaling
- Group-based train/test splitting to reduce data leakage
- Astrophysics-informed feature engineering using transit depth and stellar radius
- Model evaluation using accuracy, F1 score, ROC-AUC, confusion matrices and ROC curves

## Results
| Metric | Best model |
|---|---|
| Accuracy | 93.5% |
| F1 Score | 0.914 |
| ROC-AUC | 0.979 |

Best-performing model: Histogram-Based Gradient Boosting Classifier.

## Technologies
Python, scikit-learn, pandas, NumPy, Matplotlib, Google Colab.

## How to Run
Open exoplanet_detection.ipynb in Google Colab and run the notebook cells in order. The NASA Kepler dataset must be made available to the notebook before execution.
