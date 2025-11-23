📌 Fraud Detection Using Machine Learning
Project Overview

This capstone project focuses on detecting fraudulent transactions in real-time financial systems using machine learning techniques. The project leverages a highly imbalanced dataset with over 1 million records and aims to build a model that minimizes missed fraud cases while maintaining efficiency.

🎯 Objective

Develop a robust ML model capable of predicting fraudulent transactions with high recall to reduce financial losses and improve digital payment security.

🧠 Key Features

Extensive EDA to understand fraud indicators

Feature Engineering to improve model accuracy

Handling class imbalance using SMOTE

Model comparison & selection

Financial loss analysis using confusion matrix values

Real-time prediction using Streamlit

Power BI dashboard for business insights

🧾 Dataset
Property	Value
Total Transactions	1.05 Million
Fraud Cases	0.11%
Transaction Types	TRANSFER, CASH_OUT, PAYMENT, DEBIT, CASH_IN
⚙️ Tech Stack

Python · Pandas · NumPy · Scikit-learn · XGBoost · Matplotlib · Seaborn · SMOTE · Streamlit · Power BI · Joblib

🤖 Models Evaluated
Model	Precision	Recall	F1	ROC-AUC
Logistic Regression	Moderate	Lower	Lower	Moderate
XGBoost	High	High	High	0.99
Random Forest (Selected)	0.94	0.91	0.92	0.9967

👉 Selected Random Forest for deployment because it achieved the best Recall & ROC-AUC, reducing risk of missed fraud.

💰 Financial Impact
Type	Value
Cost per Missed Fraud (FN)	₹10,000
Cost per Wrong Alert (FP)	₹500

Model significantly reduces potential financial loss by minimizing False Negatives.

💻 Streamlit Real-Time App

User inputs values manually

Predicts Fraud / Legitimate

Displays probability score

Uses saved model (fraud_rf_model.pkl)

📊 Dashboard Insights

Fraud concentrates in CASH_OUT & TRANSFER

Fraud transactions involve high amounts

Imbalance visualization for decision justification

🧪 Project Files

Jupyter Notebook (Fraud_Detection_Project.ipynb)

Streamlit App (app.py)

Saved Model (fraud_rf_model.pkl)

PPT & Power BI Dashboard

Demo Video

🔮 Future Enhancements

Deploy with API, Docker, and Kafka streaming

Support explainability with SHAP

Explore deep learning models (Autoencoders / LSTM)

🙋‍♀️ Author

Teenu Mary John
Data Science & AI Enthusiast
Open to opportunities in ML / Data Science / Analytics

🤝 Connect

Feel free to reach out for collaboration / feedback.
