# HeartCareAI: Cardiac Arrest Risk Predictor

This project develops an AI-powered Streamlit app using a Random Forest classifier to predict cardiac arrest risk from patient health data, empowering individuals in Pakistan with instant, accessible insights to reduce reliance on urgent medical visits and support proactive fitness monitoring.

## How It Works

**Dataset:** 'heart_data.csv' (399,994 entries, 25 columns from Kaggle's Pakistan-specific heart attack risk dataset), preprocessed to 15 key features (e.g., Age, Gender, BMI, Smoker, Diabetes, Hypertension, Cholesterol_Level, Physical_Activity, Diet, Family_History, Stress_Level, Alcohol_Consumption, Sleep_Hours, Blood_Pressure, Blood_Sugar) and a binary target (Cardiac_Arrest).

**Approach:** Performed EDA (distributions, correlations), preprocessing (handled missing values, encoded categorical features, scaled numerical ones), and trained a Random Forest model via a pipeline for robust classification, wrapped in a Streamlit app for user-friendly predictions.

**Tools:** Python, pandas, numpy, scikit-learn, joblib, Streamlit, matplotlib, seaborn.

## What I Achieved

**Results:** The Random Forest model delivers reliable predictions, enabling the app to output risk percentages (e.g., "Your heart is 11% at risk of cardiac arrest. AI Prediction: Low Risk") based on user inputs, tailored for Pakistan's demographic, achieving the accuracy of 85 percent.

**Insights:** Key features like Hypertension, Cholesterol_Level, and Stress_Level drive predictions, highlighting lifestyle factors for prevention in youth and adults—addressing Pakistan's rising cardiac risks.

## Setup

Clone the repo: git clonehttps://github.com/ZainShah6500/HeartCareAI-UraanAI.git
Install dependencies: pip install -r requirements.txt
Run the app: streamlit run heart_app.py (or open Heart_Disease_Prediction.ipynb in Jupyter for model exploration).

## 🤝Connect for Collaboration
As passionate about solving real-world problems with accessible tools, I'm open to discussions on ML, healthcare innovations, or joint projects—let's make AI work for Pakistan!

- <a href="https://www.linkedin.com/in/zain-shah-871aa532a">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="20" height="20"/> LinkedIn
  </a>

- <a href="https://x.com/zainshah_x">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/twitter/twitter-original.svg" width="20" height="20"/> Twitter (X)
  </a>

- <a href="mailto:btenmeten12345@gmail.com">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" width="20" height="20"/> Gmail
  </a>


