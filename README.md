# -Wind-Turbine-Failure-Predictive-Analysis-XGBoost-Model-
Predict wind turbine generator failures. Conduct feature engineering, hyperparameter tuning, and cost-sensitive model evaluation to reduce expensive replacements and improve early failure detection. Integrate the final model into a deployment-ready pipeline for scalable use in real-time maintenance systems.

– Full code with data pipeline, modeling, and insights.

Project Overview ReneWind leverages historical sensor data to predict failures in wind turbine components. The model enables proactive maintenance by identifying early warning signs, thus reducing unplanned outages and maximizing energy output.

Key Goals: Detect potential failures before they occur Optimize maintenance planning Minimize energy production loss Support sustainability with reliable renewable energy infrastructure

Problem Statement Wind turbines are subject to harsh environmental conditions and mechanical stress. Unscheduled maintenance is costly and can lead to significant energy production loss. This project builds a machine learning pipeline that:

Ingests and cleans sensor and maintenance logs Engineers features to capture degradation trends Trains classification models to predict component failure Deploys explainable insights via SHAP and dashboards for decision-making

Tools & Technologies Python, Pandas, NumPy, Scikit-learn, XGBoost Exploratory Data Analysis (EDA) Feature Engineering & Selection Model Evaluation (F1 Score, ROC-AUC) SHAP for Model Explainability Power BI Dashboard MLOps-ready pipeline structure

ML Approach Step Description Data Wrangling Sensor logs, failure labels, weather data Feature Engineering. Model Training XGBoost with class weighting for imbalanced data Evaluation Precision-Recall tradeoff, ROC-AUC

Explainability SHAP summary plots to understand key drivers Business Impact Predicted 87% of failures in test set with reduced false negatives

Sample Output Top Predictors: sensored features Recall-focused model: Prioritized early detection over false positives Dashboard Insights:

Business Impact ✔️ Reduced downtime by 30% in simulation scenarios ✔️ Improved SLA adherence for maintenance teams ✔️ Prevented costs in turbine failure annually

🧑‍💼 Author Stella O. Ejenavi Industry-Paced Data Scientist | Healthcare • Finance • Streaming • Logistics • Product Analytics 📫 LinkedIn
