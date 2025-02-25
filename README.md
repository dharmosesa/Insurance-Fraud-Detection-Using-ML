# Insurance-Claim-Prediction

A machine learning project to detect fraudulent insurance claims using various classification algorithms.

## Project Overview
This project implements multiple machine learning models to detect insurance fraud. The models analyze various features of insurance claims to predict whether a claim is fraudulent or legitimate.

## Models Implemented
- Random Forest Classifier (Best performing - 79% accuracy)
- Decision Tree Classifier (77.5% accuracy)
- Support Vector Classifier (75% accuracy)
- K-Nearest Neighbors (75% accuracy)
- Gradient Boosting Classifier (49% accuracy)

## Dataset
The dataset contains 1000 insurance claims with 40 features including:
- Customer Demographics (age, education, occupation)
- Policy Information (deductible, premium, etc.)
- Claim Details (injury claims, property claims, vehicle claims)
- Incident Information (type, severity, location)

## Key Features
- Data preprocessing and cleaning
- Feature selection and engineering
- Model comparison and evaluation
- Hyperparameter tuning using GridSearchCV
- Performance metrics analysis

## Results
- Best performing model: Random Forest Classifier
  - Training Accuracy: 100%
  - Testing Accuracy: 79%
  - Precision (N): 0.82
  - Recall (N): 0.92
  - F1-Score (N): 0.87

## Future Improvements
- Implement more advanced feature engineering
- Try ensemble methods
- Collect more data for better model training
- Add real-time prediction capabilities
