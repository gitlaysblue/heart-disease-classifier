# End-to-End Heart Disease Classification 🫀

This project is a complete pipeline for heart disease prediction using machine learning. It involves data preprocessing, exploratory data analysis (EDA), feature selection, model training, evaluation, and export of predictions.

---

## Project Structure

- **`heart-disease.csv`** - The main dataset used for analysis and prediction.
- **`exported-patient-data.csv`** - The final predictions file containing patient data and model output.
- **`End-to-End Heart Disease Classification.ipynb`** - Jupyter Notebook containing the full workflow from data loading to prediction and export.

---

##  Objective

To develop a machine learning model that can accurately predict the presence of heart disease in patients based on various health metrics.

---

##  Dataset Overview

The dataset contains several health-related attributes, such as:

- `age`
- `sex`
- `cp` (chest pain type)
- `trestbps` (resting blood pressure)
- `chol` (serum cholesterol)
- `fbs` (fasting blood sugar)
- `restecg` (resting electrocardiographic results)
- `thalach` (maximum heart rate achieved)
- `exang` (exercise-induced angina)
- `oldpeak` (ST depression)
- `slope` (slope of the peak exercise ST segment)
- `ca` (number of major vessels)
- `thal` (thalassemia)
- `target` (1: disease, 0: no disease)

---

##  Tools & Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib & Seaborn** (for visualization)
- **Scikit-learn** (for ML models and evaluation)
- **XGBoost** (for boosted model performance)
- **Joblib** (for model serialization)

---

## ML Models Trained

- Logistic Regression
- Random Forest
- K-Nearest Neighbors
- Support Vector Machine
- XGBoost Classifier

All models were evaluated using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

---

##  How to Run

1. Clone the repository or download the files.
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
