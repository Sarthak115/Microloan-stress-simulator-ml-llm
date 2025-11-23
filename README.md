# 🚀 Loan Stress Simulator (ML + LLM + Fintech Dashboard)

A fintech-focused loan analysis tool that simulates repayment behavior, predicts borrower default risk using Machine Learning, and generates personalized financial advisory reports using Google Gemini 2.0 LLM.  
Includes an interactive Streamlit dashboard with visual analytics and downloadable PDF reports.

---

## 📌 Features

### 🔹 Loan Simulation Engine
- EMI amortization using financial formulas  
- Month-wise loan balance tracking  
- Late fee modeling and behavior-based repayment patterns  
- Supports On-Time, Late, Minimum-Only, and Mixed repayment behaviours  

---

### 🔹 ML Default Risk Prediction
Predicts the probability of default using a Random Forest model trained on synthetic borrower data with features such as:
- Income  
- EMI-to-Income ratio  
- APR (Interest Rate)  
- Late payment frequency  

---

### 🔹 Gemini LLM Financial Advisor
Generates a clean, structured, professional advisory containing:
- Risk Assessment  
- Behavioural Insights  
- Personalized Repayment Recommendations  
- Actionable 3–4 step strategy  

LLM output is strictly text-only (PDF safe, no emojis, no markdown).

---

### 🔹 Streamlit Dashboard
- Interactive form-based input  
- Dynamic progress animations  
- EMI/income stress indicators  
- Loan balance visualization  
- ML probability display  
- Professional PDF export with:
  - User profile  
  - Simulation summary  
  - ML risk score  
  - AI advisory  
  - Balance chart  

---

## 🛠️ Tech Stack

| Component       | Technology |
|-----------------|------------|
| Frontend UI     | Streamlit  |
| ML Model        | Random Forest (scikit-learn) |
| AI Advisor      | Gemini 2.0 Flash |
| Simulation      | Python financial modelling |
| Visualization   | Matplotlib |
| PDF Report      | FPDF |
| Data Handling   | Pandas, NumPy |

---

## 📐 System Architecture
User Input Form
↓
Loan Simulation Engine
↓
Feature Engineering (EMI ratio, late freq, APR)
↓
ML Risk Model (Random Forest)
↓
Gemini LLM Financial Advisor
↓
Dashboard + Charts + PDF Report




---

## 🖥️ Running the Project

### 1️⃣ Install Dependencies
```bash
pip install streamlit google-genai scikit-learn pandas numpy matplotlib fpdf


streamlit run app.py
If running on Google Colab, use ngrok to expose the Streamlit app


👤 Author

Sarthak Kumar
Email: sarthakkumarr2003@gmail.com

