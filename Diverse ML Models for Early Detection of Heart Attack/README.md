# Diverse ML Models for Early Detection of Heart Attack

## Overview
This project aims to predict heart attacks using various machine learning models. The analysis is performed on the `heart.csv` dataset.

## Models Used
- Logistic Regression (log_clf)
- Gaussian Naive Bayes (gnb)
- Decision Tree (Tree)
- Random Forest Classifier (rf)
- Extreme Gradient Boost (xgb)

## Files in the Repository
- `heart_attack_pred.ipynb`: Jupyter notebook containing the analysis and model building.
- `heart.csv`: Dataset used for training and testing the models.
## Feature Importances

![télécharger](https://github.com/chbt-mehdi/Python/assets/124779301/ec333229-09ef-4cfd-8ae5-9e8e75c46433)

## Summary of model results

| Model                | Precision | Recall  | F1       | Accuracy | AUC      |
|----------------------|-----------|---------|----------|----------|----------|
| Logistic Regression  | 0.711111  | 0.888889| 0.790123 | 0.776316 | 0.781944 |
| Gaussian Naive Bayes | 0.794872  | 0.861111| 0.826667 | 0.828947 | 0.830556 |
| Decision Tree        | 0.742857  | 0.722222| 0.732394 | 0.750000 | 0.748611 |
| Decision Tree Test   | 0.692308  | 0.750000| 0.720000 | 0.723684 | 0.725000 |
| Random Forest Test   | 0.756098  | 0.861111| 0.805195 | 0.802632 | 0.805556 |
| XGBoost Test         | 0.767442  | 0.916667| 0.835443 | 0.828947 | 0.833333 |


## How to Run
1. Clone the repository.
2. Install the required dependencies.
3. Run the `heart_attack_pred.ipynb` notebook in Jupyter.


