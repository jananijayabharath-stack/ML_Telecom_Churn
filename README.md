# ML_Prj
Telecom Churn
📘 Overview
Customer churn is a major challenge in the telecommunications sector, where retaining an existing customer is significantly more cost‑effective than acquiring a new one. This project builds a predictive machine learning pipeline to identify customers at high risk of leaving, using a diverse dataset that includes:
* Demographic information
* Usage and service data
* Contract and tenure details
The goal is to develop a generalizable, explainable, and business‑friendly churn prediction model that telecom operators can use to design targeted retention strategies.

🧠 Project Objectives
* Predict potential churners using supervised machine learning models
* Identify key churn drivers through feature selection
* Compare model performance across multiple algorithms
* Provide interpretable insights for business decision‑making
* Demonstrate the practical value of ML in solving real‑world telecom problems

🗂️ Dataset
The dataset includes:
* Customer demographics
* Account information (contract type, tenure)
Note: Dataset source and preprocessing steps are documented in the notebook.


🤖 Machine Learning Models
The following supervised learning algorithms were trained and evaluated:
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machines (SVM)
* ANN

Model performance was compared using:
* Accuracy
* Precision, Recall, F1‑Score
* ROC‑AUC
* Confusion Matrix

🔍 Feature Selection & Explainability
Feature importance and selection techniques were applied to identify key churn predictors such as:
* support calls frequency
* total amount spent
* payment delays
* age
* Service usage patterns(Subscription_Contract)
* The SHAP analysis for capturing feature importance, gave valuable information regarding what factors affect churn most.

The dataset showed a significant imbalance between churn and non‑churn classes. To address this, SMOTE (Synthetic Minority Over-sampling Technique) was used to generate synthetic samples for the minority class. This improved model performance by providing a more balanced training set and reducing bias toward the majority class.

📈 Results
* Random Forest and ANN delivered the strongest predictive performance.
* Contract type, tenure, and billing patterns emerged as the most influential churn indicators.
* The final model provides a reliable foundation for proactive customer retention strategies.
