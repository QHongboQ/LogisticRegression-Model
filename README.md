# Logistic Regression Model Selection

This project demonstrates how to perform logistic regression with feature selection and model persistence using Python.

## 📁 Files Included

- `ModelSelectionForLogisticRegression.ipynb` — Main Jupyter notebook for training and evaluation.
- `data_LR/` — Folder containing the dataset used for training and testing.
- `model_best.pkl` — Trained logistic regression model saved using `pickle`.

## 🧪 What This Project Does

- Performs logistic regression using a selected number of features
- Evaluates model performance using AUC
- Saves the best model with `pickle` and reloads it for future use

## 🛠 How to Run

1. Clone the repo
2. Open `ModelSelectionForLogisticRegression.ipynb` in Jupyter
3. Run the cells to train and evaluate the model
4. Use `model_best.pkl` to make future predictions on new data

## 📦 Requirements

You need the following Python packages:

- pandas
- numpy
- scikit-learn

Install with:

```bash
pip install pandas numpy scikit-learn
