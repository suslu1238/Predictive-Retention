# Predictive-Retention
An Explainable AI Framework for Subscription Forecasting and Proactive Churn Prevention

Predictive Retention: An Explainable AI Framework for Churn Prevention
📌 Project Overview
This project addresses the critical issue of customer churn in the telecommunications sector. While traditional models focus purely on accuracy, this framework bridges the "Actionability Gap" identified in recent 2025 research. By integrating Explainable AI (XAI) with a Prescriptive Recommendation Engine, we move from simply predicting who will leave to prescribing what actions to take to retain them.

🚀 Key Features
High-Accuracy Predictive Engine: Optimized XGBoost model achieving an AUC of 0.9922 and 96% accuracy.

Class Balancing: Implementation of SMOTEENN to resolve dataset imbalance (shifting from 26.6% churn to a balanced distribution).

Transparent Interpretability: Utilization of SHAP and LIME to provide global feature importance and local instance explanations.

Prescriptive Logic: A novel recommendation layer that maps XAI "Reason Codes" to specific business retention strategies (e.g., Price-Matched Discounts, Tech-Support Vouchers).

📊 Model Performance
The model was trained on the IBM Telco Customer Churn dataset (7,043 records) with the following final results:

Metric	Score
Accuracy	96%
ROC-AUC	0.9922
Precision (Churn)	0.97
Recall (Churn)	0.95
🛠️ Tech Stack
Language: Python 3.12

Environment: Google Colab

Libraries: xgboost, scikit-learn, imblearn (SMOTEENN), shap, lime, pandas, matplotlib

📂 Repository Structure
Telco-Customer-Churn.csv: The primary dataset.

Churn_Prediction_Model.ipynb: Google Colab notebook containing end-to-end code.

Predictive_Retention_Paper.pdf: The finalized IEEE conference paper.

last.drawio.png: The end-to-end system architecture diagram.

📖 References
Güllü, M., Dede, R., & Duru, İ. (2025). Telecom Customer Churn Prediction: In-Depth Analysis with Artificial Intelligence Algorithms and Explainable Artificial Intelligence.
