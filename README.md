🧬 Breast Cancer Prediction using Machine Learning

This project demonstrates the application of classical Machine Learning algorithms to predict breast cancer malignancy using the Breast Cancer Wisconsin (Diagnostic) Dataset. The objective is to build a robust binary classification model that distinguishes between benign and malignant tumors based on real-world clinical features.

🧠 Project Highlights

🔍 Exploratory Data Analysis (EDA):

Visualization of class distribution and feature correlations.

Pair plots and heatmaps to understand relationships between features.

🧹 Data Preprocessing:

Handling missing/null values.

Feature selection and standardization.

🧪 Model Training:

Trained and compared multiple models: Logistic Regression, SVM, KNN, Decision Tree, Random Forest, and XGBoost.

Hyperparameter tuning using GridSearchCV for optimal performance.

📊 Model Evaluation:

Used metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

Visualizations: Confusion Matrix and ROC Curves.

💡 Interpretability:

Feature importance plots from tree-based models for clinical insight.

📁 Dataset
Source: UCI ML Repository - Breast Cancer Wisconsin (Diagnostic) Data Set

Features: 30 numeric features derived from digitized images of fine needle aspirates of breast mass.

Target: Diagnosis (M = Malignant, B = Benign)

🛠️ Technologies Used
Language: Python

Libraries:

pandas, numpy, matplotlib, seaborn – Data processing and visualization

scikit-learn – ML models and evaluation

xgboost – Advanced gradient boosting classifier

🧪 Model Performance
Model	Accuracy	Precision	Recall	F1 Score	ROC-AUC
Logistic Regression	98.2%	98.0%	98.0%	98.0%	99.3%
SVM	98.2%	98.0%	98.0%	98.0%	99.1%
Random Forest	98.2%	98.0%	98.0%	98.0%	98.9%
XGBoost	97.4%	97.5%	97.5%	97.5%	98.9%

(These values are based on test set performance and may vary slightly due to random state.)
