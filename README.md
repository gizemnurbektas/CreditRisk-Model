# Credit Risk Classification

This Google Colab notebook builds and evaluates a binary loan-risk classification workflow using applicant and loan attributes. The main model is XGBoost, with Logistic Regression also explored as a comparison.

## Workflow

- Upload and inspect `credit_risk_dataset.csv`.
- Use `loan_status` as the target and the remaining columns as input features.
- Prepare features and scale them with `StandardScaler`.
- Create a stratified 80/20 train/test split.
- Fit an `XGBClassifier` and evaluate predictions with a classification report, confusion matrix, and ROC/AUC curve.
- Explore a Logistic Regression model in a later notebook section.

## Data

Expected file: `credit_risk_dataset.csv`, containing a `loan_status` column. The notebook requests this file from the user and does not include the dataset in the repository. It also contains an optional CSV export/upload step for a processed dataset.

## Run in Google Colab

1. Open `Datascienceproject.ipynb` in Google Colab.
2. Upload `credit_risk_dataset.csv` when requested.
3. Run the notebook cells in order and review the evaluation plots and reports.

Install `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, and `shap` in the runtime if needed. Model performance depends on the input data and selected configuration; use the notebook output for the actual run.

## Repository contents

- `Datascienceproject.ipynb` — data preparation, model training, and evaluation.
- `README.md` — project overview and Colab instructions.

## Author

Gizem Bektaş
