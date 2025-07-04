
# 🩺🔎 GlucoTrack: Web App for Predicting Diabetes Risk

## 🚀 Project Overview
**GlucoTrack** is an interactive web application built with **Streamlit** that leverages machine learning to assess the likelihood of **Type II Diabetes**. Developed in Python and trained on real medical datasets, the app enables users to enter their health information and instantly receive a risk assessment, along with tailored advice and interpretability features.

> 🎓 Created as a capstone for the Master of Data Analytics at Melbourne Institute of Technology, this project demonstrates the use of machine learning for proactive healthcare and early diabetes risk identification.

---

## 🌟 Core Features

- 🤖 **Predicts diabetes risk** using:
  - Glucose levels
  - BMI
  - Insulin
  - Age
  - Blood Pressure
  - Number of pregnancies
- 🖥️ Intuitive and clean user interface
- 🏆 Multiple ML algorithms evaluated; **Gradient Boosting** chosen for deployment
- 📝 Personalized recommendations based on risk category
- 🧩 Model interpretability with **SHAP visualizations**
- 📊 Real-time charts and graphical insights

---

## 🛠️ Technology Stack

- **Programming Language:** Python
- **Framework:** Streamlit
- **Machine Learning:** scikit-learn, pandas, numpy, shap
- **Visualization:** Plotly, Seaborn, Matplotlib
- **UI Styling:** Custom CSS (`diabetes_theme.css`)

---

## 📁 Project Structure

- `main.py`: Main application script
- `overview.py`: Dashboard and summary layout
- `predict.py`: Handles risk prediction logic
- `recommendation.py`: Generates recommendations based on risk output
- `explain.py`: SHAP-based model explanations
- `export.py`: Exporting prediction results
- `analytics.py`: Data analysis utilities
- `diabetes_charts.py`: Visualization components
- `diabetes.csv`: Pima Indians Diabetes dataset
- `gb_model_5features.pkl`: Pre-trained Gradient Boosting model
- `diabetes_theme.css`: Custom Streamlit theme
- `requirements.txt`: Python package dependencies
- `radar_profile_plot.png`: Example output visualization
- `shap_summary_plot.png`: SHAP summary interpretation
- `*.json`: Templates for risk-based recommendations

---

## ⚡ Getting Started

1. **Clone the repository:**
   ```
   git clone https://github.com/Rebecca211/BioStatsForDiabetesII.git
   cd BioStatsForDiabetesII
   ```

2. **Install the required packages:**
   ```
   pip install -r requirements.txt
   ```

3. **Start the application:**
   ```
   streamlit run main.py
   ```

---

## 📈 Model Highlights

- **Selected Model:** Gradient Boosting Classifier
- **Accuracy:** ~91%
- **ROC-AUC:** ~90%
- **Feature Importance:** SHAP plots highlight Glucose, BMI, and Age as key predictors

---

## 🎯 Significance

This application demonstrates the practical value of data science in preventive medicine by:
- 🕒 Enabling users to check their diabetes risk early
- 👩‍⚕️ Providing clinicians with an interpretable, visual tool
- 📚 Promoting evidence-based health choices

---

## 👥 Contributors

- Reebeka Joshi
- Anish Manandhar
- Shova Gurung
- Mohammad Monirul
- Abrar Alam Chowdhury

---

## 🌐 Live Demo

[biostatsfordiabetesii.streamlit.app](https://biostatsfordiabetesii.streamlit.app/)

---

## 📬 Contact

For feedback or collaboration, connect on [LinkedIn](https://www.linkedin.com/in/abrar-alam-chowdhury/)

---
```
Let me know if you want to add more emojis, badges, or further customization!

Sources
