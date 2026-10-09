# Heart_Disease


# ❤️ Heart Disease Prediction & Automated Clinical Decision Support System

An end-to-end Machine Learning project designed to predict cardiovascular disease risk and generate automated clinical triage reports for patients. Built using Python, Scikit-Learn, and Pandas.

---

##  Project Overview
This system processes heart disease medical records, trains a robust **Logistic Regression** classifier with proper feature scaling, and features a custom **Clinical Recommendation Engine** that classifies patients into distinct risk tiers (High, Moderate, and Low) and suggests actionable medical steps.

---

## ✨ Key Features
- **Robust Data Preprocessing:** Automatically cleans dataset anomalies, handles missing/corrupted values (`?`), manages data types, and applies median imputation.
- **Feature Scaling:** Uses `StandardScaler` to normalize numerical features for stable and accurate model convergence.
- **Predictive Modeling:** Implements `LogisticRegression` from Scikit-Learn with stratified train-test splitting.
- **Automated Clinical Triage Engine:** Evaluates patient risk probabilities and outputs tailored medical advice, lifestyle recommendations, and diagnostic action plans.
- **Patient Index Explorer:** Allows querying specific patient records from the full dataset (0–269 index range) to instantly view profiles and triage reports.

---

## 📂 Project Structure
```text
├── cleaned_heart_disease_data.csv   # Cleaned and processed dataset ready for academic submission
├── heart_disease_project.ipynb      # Main Jupyter Notebook containing EDA, training, and evaluation
└── README.md                        # Project documentation
