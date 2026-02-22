# Explainable-AI-(XAI)-for-Telecom-:-Quantifying-Behavioral-Drivers-of-Churn

**Project Overview**
Customer churn is one of the most vital metrics for telecom companies. This project moves 
beyond simple "black-box" predictions by utilizing Explainable AI (XAI). By combining 
XGBoost for high-accuracy forecasting and SHAP (Shapley Additive Explanations) for model 
transparency, we identify exactly why customers are leaving. 
 
**Data Source:** IBM Sample Data / Kaggle Telco Churn 
 
**Key Features**
• Predictive Modeling: Uses XGBoost, a high-performance gradient boosting algorithm. 
• Interpretability:  Implements SHAP values to provide global and local explanations of 
feature importance. 
• Data Insights: Comprehensive EDA focusing on customer tenure, contract types, and 
monthly charges. 
• Behavioral Analysis: Quantifies how specific behaviors (e.g., lack of tech support, fiber 
optic usage) contribute to churn risk. 
 
**Visualizing Results**
**Global Feature Importance**
The SHAP summary plot illustrates the top drivers of churn. Features like Tenure, Contract Type, 
and Monthly Charges play a significant role. 
 
**Performance Metrics**
**Metric : Score**
Accuracy : 78.39% 
Precision (Churn) : 61.82% 
Recall (Churn) : 48.93% 
F1-Score : 54.63% 
 
**Tech Stack**
• Platform: Jupyter Notebook   
• Language: Python 3.8 
• Machine Learning: XGBoost, Scikit-learn 
• XAI: SHAP 
• Visualization: Matplotlib, Seaborn 
• Data Handling: Pandas, NumPy
