# ml-project-credit-risk-model


````markdown
# Credit Risk Prediction Model 💳📊

This machine learning project predicts the credit risk of an individual based on their profile using classification models. It was developed as part of my data science bootcamp and demonstrates the full ML pipeline—from data preprocessing and model training to deployment using Streamlit.

---

## 🚀 Project Overview

**Goal:** Predict whether a customer is likely to default or not based on features such as income level, medical history, age, employment status, and more.

**Key Features:**
- Binary classification model (Logistic Regression / XGBoost)
- Cleaned and encoded raw data
- Saved trained model using `joblib`
- Interactive frontend built with **Streamlit**
- Deployed live: [🌐 App Demo](https://ml-health-premium.streamlit.app/) *(update this link)*

---

## 🧠 ML Pipeline

1. **Data Preprocessing**
   - Handled missing values, encoded categorical data
   - Feature scaling
2. **Model Building**
   - Tried multiple models (Logistic Regression, XGBoost)
   - Hyperparameter tuning with Optuna/GridSearch
3. **Evaluation**
   - ROC-AUC Score, KS Statistic, Confusion Matrix
4. **Deployment**
   - Streamlit UI for user input & predictions
   - Model loaded via `joblib`

---

## 📁 Project Structure

```bash
ml-project-credit-risk-model/
│
├── main.py                      # Streamlit app
├── prediction_helper.py        # Preprocessing and prediction logic
├── artifacts/                  # Saved trained models
├── requirements.txt            # Python dependencies
├── .gitignore                  # Ignored files
└── README.md                   # Project description
````

---

---

## 📦 Setup Instructions

1. Clone the repo:

```bash
git clone https://github.com/mahima-ds/ml-project-credit-risk-model.git
cd ml-project-credit-risk-model
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the app:

```bash
streamlit run main.py
```

---

## 📚 Technologies Used

* Python
* pandas, numpy, scikit-learn, xgboost, joblib
* Streamlit for deployment
* Git & GitHub for version control

---

## 👤 Author

**Mahima Reddy Kota**
[LinkedIn](https://www.linkedin.com/in/mahima-reddy-kota-21a26436a) | [GitHub](https://github.com/mahima-ds)
---

## 📜 License

This project is licensed under the Apache2.0 License.
