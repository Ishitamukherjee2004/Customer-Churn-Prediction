# 📊 Customer Churn Prediction App

A Machine Learning web application built using **Streamlit** that predicts whether a customer is likely to churn based on customer information.

## 🚀 Features

- Predict customer churn instantly
- Simple and interactive Streamlit interface
- Uses a trained Machine Learning model
- Automatic data preprocessing using StandardScaler
- Displays prediction as **Yes** or **No**

---

## 🛠️ Technologies Used

- Python
- Streamlit
- NumPy
- Pandas
- Scikit-learn
- Joblib

---

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── app.py
├── notebook.ipynb
├── model.pkl
├── scaler.pkl
├── customer_churn.csv
├── requirements.txt
└── README.md
```

---

## 📋 Input Features

The application takes the following inputs:

- Age
- Gender
- Tenure (Months)
- Monthly Charges

---

## 🎯 Output

The model predicts whether the customer is likely to churn.

- **Yes** → Customer is likely to leave.
- **No** → Customer is likely to stay.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

Go to the project folder:

```bash
cd customer-churn-prediction
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 🧠 Machine Learning Workflow

1. Load Dataset
2. Data Preprocessing
3. Feature Scaling using StandardScaler
4. Train-Test Split
5. Train Logistic Regression Model
6. Save Model using Joblib
7. Deploy using Streamlit

---

## 📦 Model Files

- **model.pkl** → Trained Logistic Regression model
- **scaler.pkl** → StandardScaler used during training

---

## 📸 Application Preview

The application contains:

- Input fields for customer information
- Predict button
- Churn prediction result
- Interactive Streamlit interface

---



## 📜 License

This project is created for educational and learning purposes.
