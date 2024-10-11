# Multiple-Linear-Regression -Fish
# Fish Market Regression Project

## Project Overview
In this project, we build a multiple linear regression model to predict the weight of fish based on various features using the Fish.csv dataset from Kaggle.

## Dataset Information
- Source: Kaggle Fish Market Dataset
- Features: Species, Length1, Length2, Length3, Height, Width

## Preprocessing Steps
1. Encoding categorical variables.
2. Combining highly correlated features.
3. Handling multicollinearity using VIF and PCA.

## Model Building
- Trained multiple linear regression model on the preprocessed dataset (X_1).
- Evaluated model performance using R², MAE, and RMSE.

## Results
- R²: 0.939
- MAE: 64.13
- RMSE: 88.69

## How to Run
1. Clone the repository.
2. Install required libraries (`pandas`, `seaborn`, `matplotlib`, `scikit-learn`).
3. Run the Jupyter notebook in the `notebooks/` folder.

## Conclusion
This project demonstrates the use of multiple linear regression for predicting fish weight, including data preprocessing, handling multicollinearity, and model evaluation.


