# 🔁 Loan Default Risk Analysis Project

[![Python Version](https://img.shields.io/badge/python-3.11%2B-blue.svg)](https://www.python.org/)
[![Stars](https://img.shields.io/github/stars/zufran123/loan-default-analysis.svg?style=social)](https://github.com/zufran123/loan-default-analysis/stargazers)
[![Forks](https://img.shields.io/github/forks/zufran123/loan-default-analysis.svg?style=social)](https://github.com/zufran123/loan-default-analysis/network/members)
[![Last Commit](https://img.shields.io/github/last-commit/zufran123/loan-default-analysis.svg)](https://github.com/zufran123/loan-default-analysis/commits/main)
[![View on Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://zufran123-loan-default-analysis.streamlit.app)

---

This Loan Default Risk Analysis project is an end-to-end machine learning solution designed to predict whether a loan applicant is likely to default, using key financial indicators such as age, income, credit score, and loan terms.

Using Python and popular ML libraries such as Scikit-learn and Pandas, this project handles data loading, model training, Streamlit-based deployment, and dynamic PDF report generation.

---

## 📋 Project Management

This project was developed with a structured approach involving:

- Python scripts for modularization
- Streamlit for real-time prediction interface
- GitHub for source control and collaboration
- PDF reports to capture individual predictions

---

## 📊 Project Overview

- **Objective:** Predict loan default risk from applicant data
- **Domain:** Finance / Lending
- **Problem Type:** Binary Classification
- **Target Variable:** `Default` (0 = No Default, 1 = Default)
- **Model Used:** Random Forest Classifier

---

## 🧰 Tools & Technologies

- **Language:** Python 3.11+
- **Libraries Used:**
  - pandas
  - numpy
  - scikit-learn
  - streamlit
  - fpdf
  - joblib

---

---

## 📁 Project Structure

```

loan-default-analysis/
├── app/
│ └── streamlit_app.py # Streamlit UI
├── data/
│ └── loan_data.csv # Input dataset
├── model/
│ └── loan_default_model.pkl # Trained model
├── reports/
│ └── loan_risk_report_*.pdf # Auto-generated PDF reports
├── visuals/
│ └── *.png # Plots (optional)
├── main.py # Model training script
├── generate_dummy_data.py # Script to generate synthetic data
├── generate_report.py # PDF report generator
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── .gitignore
```


---

## 🔍 Key Features

- 📊 Synthetic dataset of 500 loan applicants
- ✅ Random Forest classifier for robust binary classification
- 📄 Automatic PDF report generation using FPDF
- 🧠 Real-time prediction through a responsive Streamlit UI
- 💾 Modularized codebase for flexibility and maintenance

---

## 📈 Visualizations Included

- Feature importance (from the model)
- Correlation heatmaps
- Input value analysis (through Streamlit)

---

## 🚀 How to Run the Project

### 1. Clone the Repository:

```bash
git clone https://github.com/zufran123/loan-default-analysis.git
cd loan-default-analysis
```
### 2. Create Virtual Environment (optional but recommended):

```bash
python -m venv venv
venv\Scripts\activate # Windows
```
### 3. Install Dependencies:

```bash
pip install -r requirements.txt
streamlit run app/streamlit_app.py
```
### 4. Train the Model:

```bash
python main.py
```
### 5. Run the App:

```bash
streamlit run app/streamlit_app.py
```

---

## 📂 Dataset Information

- **Format:** CSV
- **Synthetic Fields Used:**
  - `Age`, `AnnualIncome`, `LoanAmount`
  - `CreditScore`, `LoanTerm`
  - `Default` (0 = No, 1 = Yes)

> Dataset is synthetically generated for demonstration purposes.

---

## 📈 Future Improvements

- Add model explainability (SHAP/LIME)
- Expand dataset with real-world features
- Add authentication to the Streamlit app
- Auto-email PDF reports to users

---

## 🙌 Acknowledgements

- Built for academic and demonstration purposes
- Inspired by financial loan risk modeling used in lending platforms and fintech

---

## 👨‍💻 Author

**Mohd Zufran**  
🔗 https://linkedin.com/in/mohdzufran

---

## 📄 License

This Open Source Software is licensed under the **MIT License**.  
Please give proper credit by including the license and attributing the original author.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[MIT License](LICENSE)

