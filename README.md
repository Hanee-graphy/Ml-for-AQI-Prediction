# Ml-for-AQI-Prediction
🌍 Air Quality Prediction Using Machine Learning
📊 Project Overview
This project investigates the use of machine learning (ML) and deep learning (DL) algorithms to predict the Air Quality Index (AQI) in Delhi, India. Given the severe pollution crisis in Delhi, this research applies data-driven models to accurately forecast AQI, identify key pollutant contributors, and improve interpretability using Explainable AI (XAI) techniques like SHAP and LIME.

🧠 Models Implemented
Random Forest (RF) 🌲

Extreme Gradient Boosting (XGBoost) ⚡

Long Short-Term Memory (LSTM) 🧠

Transformer Networks 🤖

These models were trained on historical AQI and pollutant data (2020–2023) and evaluated using MAE, RMSE, and R² Score.

🚀 Key Results
Model	MAE	RMSE	R² Score
Random Forest	0.1155	2.6069	0.9874
Transformer	0.1231	2.8910	0.9996 ✅
XGBoost	0.1295	2.9578	0.9802
LSTM	0.1542	3.2245	0.9101
👉 Random Forest performed best in terms of MAE and RMSE, while the Transformer model achieved the highest R² score.

🧾 Explainable AI (XAI)
To enhance trust and transparency:

SHAP (Shapley Additive Explanations) identified PM2.5 and PM10 as the most influential pollutants.

LIME offered localized interpretations of model predictions.

🌐 Deployment
The best-performing model was deployed using Streamlit, enabling real-time AQI predictions and visual explanations for end-users.

📍 Case Study: Delhi, India
Delhi, one of the most polluted cities globally, served as the study area. The research focuses on:

Seasonal AQI trends

Pollutant concentration patterns

Insights for policy interventions and public health responses

📁 Project Structure
bash
Copy
Edit
📦 air-quality-ml
 ┣ 📂 data/                     # Raw and processed AQI datasets
 ┣ 📂 models/                   # Trained ML and DL models
 ┣ 📂 notebooks/                # EDA and model training notebooks
 ┣ 📂 explainability/           # SHAP & LIME scripts
 ┣ 📂 streamlit_app/            # Web app code for deployment
 ┣ 📜 requirements.txt
 ┗ 📜 README.md
📌 Technologies & Tools
Python (Pandas, NumPy, Scikit-learn, XGBoost, TensorFlow/Keras)

SHAP, LIME

Streamlit

Google Colab (for model training)

🎯 Objectives
Predict AQI using advanced ML and DL models.

Identify dominant pollutants affecting air quality.

Ensure model interpretability with XAI.

Provide an interactive, user-friendly AQI forecasting tool.

📚 Academic Contribution
This work is part of the MSc Data Science dissertation by Anifah Ayoade-Kosoko at the School of Mathematics and Computer Science, exploring how AI can support environmental sustainability and public health policy.

📌 Keywords
Air Quality, Machine Learning, AQI Forecasting, SHAP, LIME, Explainable AI, Environmental Data Science, Delhi, Public Health
