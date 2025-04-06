
# 📉 Customer Churn Prediction

This project uses machine learning to predict whether a customer will churn (i.e., stop using the service) based on their account details, services used, and payment history.

---

## 📂 Dataset

- **Source**: [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Size**: 7,043 rows × 21 columns
- **Goal**: Predict the `Churn` column (Yes/No)

---

## 🔍 Steps Covered

1. **Data Cleaning**
   - Converted `TotalCharges` to numeric
   - Handled missing values
   - Dropped `customerID`

2. **Exploratory Data Analysis (EDA)**
   - Churn distribution
   - Churn vs contract, tenure, charges
   - Visualized with Seaborn & Matplotlib

3. **Data Preprocessing**
   - Label encoding for binary columns
   - One-hot encoding for other categoricals
   - Feature scaling (StandardScaler)

4. **Modeling**
   - Logistic Regression
   - Random Forest Classifier
   - Evaluated using Accuracy, F1, Confusion Matrix, and ROC-AUC

5. **Business Insights**
   - Higher churn in month-to-month contracts
   - Long-term contracts reduce churn
   - Customers with high monthly charges & short tenure churn more

---

## 📊 Results

| Model              | Accuracy | ROC-AUC |
|-------------------|----------|---------|
| Logistic Regression | ~80%     | ~84%    |
| Random Forest       | ~83%     | ~86%    |

---

## 🛠️ Tools Used

- Python
- Google Colab
- Pandas, Numpy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🚀 Future Work

- Try XGBoost or LightGBM
- Add Streamlit dashboard for predictions
- Deploy using Flask or FastAPI
- Connect to a real-time database

---

## 📌 How to Run

1. Clone the repo or open notebook in Google Colab
2. Install requirements:
   ```bash
   pip install -r requirements.txt







---Made by **Challa Jaipal Reddy**

Let me know if you'd like me to:
- Customize this with **your name and GitHub link**
- Add a **Streamlit UI** for churn prediction
- Help build a **project portfolio website**  
- Or generate a **PPT or PDF summary** for interviews

You're building something solid — let’s make it shine on your resume 🌟
