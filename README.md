# 🤖 Machine Learning Projects & Air Quality Index (AQI) Prediction

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-111?style=for-the-badge&logo=xgboost&logoColor=white)](https://xgboost.readthedocs.io/)
[![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logo=yandex&logoColor=black)](https://catboost.ai/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

A comprehensive collection of Machine Learning projects developed during the **NTI (National Telecommunication Institute)** Machine Learning program, featuring end-to-end data analysis, model training, evaluation, hyperparameter tuning, and web app deployment.

---

## 📂 Projects Overview

### 1. 🌍 Air Quality Index (AQI) Prediction (Capstone Project)
- **Directory:** `air qulity/`
- **Objective:** Predict and classify Air Quality Index levels based on environmental factors, weather data, and pollutant concentrations.
- **Model:** **XGBoost Classifier / Regressor** (`xgboost_model.pkl`) & CatBoost.
- **Interactive App:** Includes a Streamlit / Flask web interface (`app.py`) for real-time predictions.
- **Documentation:** Full feature glossary available in `AQI_Project_Glossary_EN.pdf`.

---

### 2. 🏥 Medical Insurance Cost Prediction (Regression)
- **Directory:** `1_ml_project/`
- **Objective:** Predict individual medical insurance charges based on age, BMI, smoking status, and region.
- **Techniques:** Exploratory Data Analysis (EDA), feature encoding, CatBoost Regressor, and Scikit-Learn evaluation metrics (RMSE, $R^2$).

---

### 3. 💼 Adult Census Income Prediction (Classification)
- **Directory:** `2_ml_project/`
- **Objective:** Classify whether an individual earns above or below \$50K/year based on demographic and employment attributes.
- **Techniques:** Handling imbalanced data, categorical feature engineering, CatBoost Classifier, ROC-AUC evaluation.

---

### 4. 🧠 Alzheimer's Disease Risk Assessment (Medical ML)
- **Directory:** `3_ml_project/`
- **Objective:** Predict early risk and diagnosis indicators for Alzheimer's disease using clinical patient metrics.
- **Techniques:** Medical data preprocessing, feature importance analysis, model interpretability.

---

## 🛠️ Tech Stack & Libraries

- **Languages:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn`, `xgboost`, `catboost`
- **Model Serialization:** `pickle`, `joblib`

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/naserashraf-alt/air-quality-prediction-ml.git
cd air-quality-prediction-ml
```

### 2. Set Up Virtual Environment & Install Dependencies
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

pip install numpy pandas scikit-learn xgboost catboost matplotlib seaborn streamlit
```

### 3. Run the AQI Web App
```bash
cd "air qulity"
python app.py
```

---

## 👤 Author

**Naser Ashraf**
- 🌐 [Portfolio Website](https://naserashraf-alt.github.io/portfolio/)
- 💼 [LinkedIn Profile](https://www.linkedin.com/in/naser-ashraf-742106358)
- 📧 [Email](mailto:naserashraf248@gmail.com)
