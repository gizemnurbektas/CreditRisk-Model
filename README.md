# Credit Risk Classification

This Google Colab notebook explores binary loan-risk classification using applicant and loan attributes. It trains an XGBoost classifier and also examines Logistic Regression.

## Workflow

- Load and inspect `credit_risk_dataset.csv`.
- Use `loan_status` as the target and the remaining columns as model features.
- Prepare features, scale them with `StandardScaler`, and create a stratified 80/20 train/test split.
- Fit an `XGBClassifier` and review classification metrics, a confusion matrix, and an ROC/AUC curve.
- Explore Logistic Regression in a later notebook section.

## Dataset

The notebook expects `credit_risk_dataset.csv`, which is included in the repository. It contains loan applicant and loan attributes, including the `loan_status` target column.

The dataset is from [Credit Risk Dataset by Lao Tse on Kaggle](https://www.kaggle.com/datasets/laotse/credit-risk-dataset), listed as **CC0 1.0 Public Domain**. Please consult the Kaggle page for the original dataset description and provenance.

## Run in Google Colab

1. Open `Datascienceproject.ipynb` in Google Colab.
2. Download `credit_risk_dataset.csv` from this repository and upload it when the notebook requests the file.
3. Run the notebook cells in order and review the generated reports and plots.

The notebook may export a processed CSV as an optional step. Install any missing packages reported by the Colab runtime, including pandas, NumPy, Matplotlib, Seaborn, scikit-learn, XGBoost, or SHAP as needed. Model performance depends on the data split and configuration; use the metrics from your own run.

## Repository contents

- `Datascienceproject.ipynb` — data preparation, model training, and evaluation.
- `credit_risk_dataset.csv` — CC0 credit risk dataset; source and license are linked above.
- `README.md` — project overview and Colab instructions.

## Author

Gizem Bektaş
