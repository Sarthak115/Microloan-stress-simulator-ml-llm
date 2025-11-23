📘 Loan Stress Simulator (ML + LLM + Fintech Dashboard)

A Machine Learning & Gemini-LMM powered tool for loan repayment analysis, default risk prediction, and personalized financial advisory.

🚀 Project Overview

This project simulates loan repayment behavior, predicts borrower default risk, and generates personalized AI-driven financial advice.
It combines:

Financial simulation models

Machine Learning risk scoring

Google Gemini 2.0 LLM financial advisory

Interactive Streamlit dashboard

PDF report generation

Useful for fintech analytics, risk modelling, BFSI applications, loan affordability assessment, and borrower behavior study.

🧠 Key Features
🔹 Loan Simulation Engine

EMI calculation using amortization formula

Month-wise balance tracking

Late fee modeling

Interest accumulation

Dynamic behaviour modes:

On-Time

Always Late

Minimum-Only

Mixed Behaviour

🔹 ML-Based Default Risk Prediction

Predicts probability of loan default using:

Income

EMI-to-Income ratio

Late frequency

APR

Built using Random Forest Classifier on synthetic borrower dataset.

🔹 AI Financial Advisory (Gemini LLM)

The system generates:

Risk Assessment

Behavioural Insights

Personalized Recommendations

Actionable Repayment Plan

The LLM output is clean, structured, and PDF-compatible.

🔹 Interactive Streamlit Dashboard

Dynamic progress animations

Loan balance line chart

Key financial metrics

Clean UI with sliders, inputs, and explanation sections

Behavioural insight badges

🔹 PDF Report Export

Generates a professional, multi-page financial report containing:

User profile

Simulation summary

ML risk assessment

AI advisory

Loan balance chart

📂 Tech Stack
Component	Technology
Frontend UI	Streamlit
ML Model	Random Forest (scikit-learn)
AI Advisor	Gemini 2.0 Flash
PDF Reports	FPDF
Visualizations	Matplotlib
Data Processing	NumPy, Pandas
Backend Logic	Python
🧮 How It Works (Architecture)
User Input Form
       ↓
Loan Simulation Engine
       ↓
Feature Engineering (EMI ratio, late freq, APR)
       ↓
ML Default Risk Predictor (Random Forest)
       ↓
LLM Financial Advisor (Gemini 2.0)
       ↓
Dashboard Visualizations + PDF Report

🖥️ Running the Project
1. Install Dependencies
pip install streamlit google-genai scikit-learn pandas numpy matplotlib fpdf

2. Run Streamlit App
streamlit run app.py


If running on Google Colab, use ngrok for public URL.

📊 Screenshots (Optional)

(You can add images later here)

📄 PDF Report Example

Includes:

Financial summary

EMI breakdown

ML default probability

Clean advisory text

Loan balance chart

🌟 Key Skills Demonstrated

✔ Machine Learning (Random Forest)
✔ LLM Integration (Gemini)
✔ Financial Modeling
✔ Data Visualization
✔ Streamlit Development
✔ PDF Reporting
✔ Fintech Risk Analytics
✔ Behavioral Data Simulation

🧩 Future Enhancements

Multi-loan comparison

Loan Stress Index (LSI) scoring

XGBoost / LightGBM models

Income-shock stress test

API integration with real credit products

Cloud deployment (Render / GCP / Streamlit Cloud)

🤝 Contributions

Open to issues and pull requests.

📧 Contact

Created by Sarthak Kumar
For queries: sarthakkumarr2003@gmail.com
