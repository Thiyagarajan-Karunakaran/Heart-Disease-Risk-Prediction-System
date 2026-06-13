# Heart Disease Risk Prediction System

## 📖 Introduction
An AI-powered healthcare application designed to predict the likelihood of heart disease based on patient medical parameters. By combining machine learning with explainable AI (XAI) techniques, the system provides accurate risk predictions alongside human-readable explanations, highlighting the key contributing factors behind every diagnosis.

## 🛠️ Technologies Used
*   **Languages:** Python, JavaScript (React.js)
*   **AI & Machine Learning:** Scikit-learn, Pandas, NumPy, Joblib
*   **Explainable AI & LLMs:** SHAP, OpenAI API
*   **Backend Framework:** FastAPI
*   **Database:** SQLite / PostgreSQL
*   **Deployment & Tools:** Docker, Git, GitHub, Matplotlib

## ⚙️ How It Works
1.  **Data Input:** The user inputs medical parameters (e.g., age, cholesterol, blood pressure, chest pain type) into an interactive React frontend.
2.  **API Communication:** The input data is sent to a FastAPI backend via REST API endpoints.
3.  **Prediction:** The backend preprocesses the data and feeds it into a trained machine learning model to calculate a heart disease probability and confidence score.
4.  **Explainability Analysis:** SHAP (SHapley Additive Explanations) analyzes the prediction to identify the most influential clinical features.
5.  **Natural Language Generation:** An AI explanation layer uses the OpenAI API to translate the SHAP data into a human-readable, medical-style interpretation of the risk factors.
6.  **Results Display:** The user receives a comprehensive report including the predicted risk level, confidence score, feature importance visualizations, and the AI-generated explanation.

## ✨ Features
*   **Accurate Diagnostics:** Heart disease risk prediction using robust machine learning models with confidence score estimation.
*   **Transparent AI:** Integration of SHAP for explainable AI and feature importance visualization.
*   **Human-Readable Reports:** AI-generated, medical-style text explanations of the prediction.
*   **Modern Stack:** REST API built with FastAPI and a responsive React user interface.
*   **Scalable Architecture:** Modular, containerized deployment using Docker.
*   **Data Persistence:** Database support for storing and managing prediction history.

## Video

https://github.com/user-attachments/assets/f6f782b5-bfeb-4413-b1b6-7ac0ded86bbf

