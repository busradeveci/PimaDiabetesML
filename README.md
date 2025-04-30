# PimaDiabetesML
Predict diabetes using the Pima Indians Diabetes Dataset with logistic regression.

## Dataset
- Source: [Kaggle - Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Features: Glucose, BMI, Age, etc.
- Target: Outcome (0: No diabetes, 1: Diabetes)

## Methods
- Cleaned zero values with median.
- EDA: Found high correlations (Glucose: 0.49, BMI: 0.31).
- Model: Logistic regression (Accuracy: 75.32%).

## Results
- Accuracy: **75.32%**
- Confusion Matrix: [[82 17], [21 34]]

## Files
- `PimaDiabetesML.ipynb`: Kaggle Notebook with code.
