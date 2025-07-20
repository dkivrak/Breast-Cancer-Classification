# Breast Cancer Classification

This simple project aims to classify breast tumors as benign or malignant using the Breast Cancer Wisconsin (Diagnostic) Dataset, using the Logistic Regression model.

---

## Dataset

Dataset used: https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset

- The dataset contains 569 samples with 32 columns.
- The `diagnosis` column is the target variable, where `M` stands for malignant and `B` for benign tumors.
- The `id` column was dropped as it is not relevant for the model.
- All features are numerical and there are no missing values.

---

## Methods Used

- Data preprocessing: converting `diagnosis` to numeric (`M=1, B=0`)
- Train-test split: 80% training, 20% testing
- - Feature scaling: standardization using `StandardScaler`
- Model: Logistic Regression (`max_iter=1000`)
- Performance metrics: Accuracy, Precision, Recall, F1-score
