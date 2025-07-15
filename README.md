# Diabetes Prediction Web App

A machine learning web application that predicts diabetes risk using Random Forest classifier. Built with Flask and scikit-learn.

## Features

- Random Forest ML model for diabetes prediction
- User-friendly web interface
- Real-time risk assessment
- Model persistence with pickle

##  Usage

1. Open the web interface
2. Enter health parameters:
   - Pregnancies, Glucose, Blood Pressure, Skin Thickness
   - Insulin, BMI, Diabetes Pedigree Function, Age
3. Click "Predict Risk"
4. Get result: "Diabetic" or "Non-Diabetic"

## Model Details

- **Algorithm**: Random Forest (100 trees)
- **Accuracy**: ~80% on test set
- **Dataset**: Pima Indians Diabetes Database (768 samples, 8 features)
- **Target**: Binary classification (0: Non-diabetic, 1: Diabetic)

## Requirements

Create `requirements.txt`:
```
Flask==2.3.3
scikit-learn==1.3.0
pandas==2.0.3
numpy==1.24.3
```

##  Input Parameters

- **Pregnancies**: 0-10
- **Glucose**: 0-200 mg/dL
- **Blood Pressure**: 0-122 mmHg
- **Skin Thickness**: 0-100 mm
- **Insulin**: 0-846 μU/ml
- **BMI**: 0-67.1
- **Diabetes Pedigree**: 0.078-2.42
- **Age**: 21-81 years
---

**Note**: For educational purposes only. Not for medical diagnosis.
