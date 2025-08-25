# premium-prediction-ml-project
🏥 Health Insurance Cost Predictor

A machine learning project to predict health insurance costs based on personal, lifestyle, and health factors.
Built with Python, scikit-learn, and Streamlit, this project demonstrates EDA-driven model improvement, feature engineering, and deployment.

🚀 Project Overview

Started with a single regression model trained on the entire dataset.

Error analysis showed that the model performed poorly for Age ≤ 25, with errors exceeding 50%.

To address this, the project was improved step by step:

Segmentation: Built two separate models → Young (≤25) and Rest (>25).

Feature Engineering: Introduced an additional feature, Genetical Risk, which significantly improved predictions for the young group.

Deployment: Built an interactive Streamlit web app where users can input details and get predicted insurance costs instantly.

📊 Features Used

Demographics: Age, Number of Dependants, Income (Lakhs), Gender, Marital Status, Region

Lifestyle: BMI Category, Smoking Status, Employment Status

Health: Medical History, Genetical Risk (for young group)

Insurance Plan: Bronze / Silver / Gold

🛠 Tech Stack

Python (pandas, scikit-learn, joblib)

Streamlit (for deployment)

EDA & Visualization (matplotlib, seaborn)
🌐 Live Demo

App Link: https://premium-prediction-ml-project-app.streamlit.app/
