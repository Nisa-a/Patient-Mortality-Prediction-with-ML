# Mortality Prediction Using Machine Learning

This project applies supervised machine learning techniques to predict **a breast cancer patient's mortality status** based on clinical and demographic data. The analysis is conducted using Python and scikit-learn within a Jupyter Notebook environment.

## 📚 Project Overview

This notebook explores and compares the performance of three machine learning algorithms:

- **Logistic Regression**
- **K-Nearest Neighbors**
- **Gaussian Naive Bayes**

These models are trained to classify what a patient mortality status is using various medical features such as age, tumor stage, hormone status, and more.

---

## 📊 Dataset

- Source: `mortality_df.csv`
- This dataset is a refined version of the original breast_cancer_data.csv, where irrelevant or redundant variables were removed, and only the most informative features were retained for analysis.
- Features used include:
  - Age, Sex, Tumor Staging (T, N, A, 6th), Tumor Size
  - Estrogen and Progesterone Status
  - Regional Node Examination
  - Histological Grade and Differentiation

Target variable: `Mortality_Status` (Binary classification)

---

## ⚙️ Models & Techniques

- **Feature Scaling** with `StandardScaler`
- **Train/Test Split** with stratification
- **Model Training and Prediction**
- **Evaluation Metrics**:
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)
  - ROC Curve
- **GridSearchCV** used for hyperparameter tuning

---

## 📁 Files in This Repo

- `mortality_pred_ML.ipynb`: Main Jupyter Notebook containing all code and outputs
- `README.md`: This description file
- `mortality_df.csv`: Dataset file
- `breast_cancer_data.csv`: Original datatset file
