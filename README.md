# Customer Churn Prediction Using ANN

## Project Overview

This project predicts whether a bank customer is likely to leave (churn) using a Artificial Neural Network (ANN). Customer churn prediction helps banks identify customers who may discontinue their services and enables proactive retention strategies.

The model is trained on customer demographic and account-related information to classify customers into two categories:

- Churned Customer (1)
- Retained Customer (0)

---

## Features

- Data preprocessing and feature engineering
- Handling categorical and numerical features
- Feature scaling using StandardScaler
- Artificial Neural Network (RNN) implementation using TensorFlow/Keras
- Model training and evaluation
- Churn probability prediction for new customers
- Deployment-ready prediction pipeline

---

## Dataset

The dataset contains customer information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited (Target Variable)

Target Variable:

- `Exited = 1` → Customer Churned
- `Exited = 0` → Customer Retained

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow/Keras
- Streamlit (for deployment)

---

## Project Structure

```text
customer-churn-rnn/
│
├── data/
│   └── Churn_Modelling.csv
│
├── notebooks/
│   ├── training.ipynb
│   └── prediction.ipynb
│
├── models/
│   ├── ann_model.h5
│   ├── scaler.pkl
│   ├── label_encoder_gender.pkl
│   └── onehot_encoder_geo.pkl
│
├── app.py
├── requirements.txt
├── README.md
