# RetentionRadar 📡 (Helping detect churn risks)


📖 Overview

Customer churn is a critical issue for telecom companies. This project builds an Artificial Neural Network (ANN) to predict whether a customer will churn based on their service usage and contract details.

📂 Dataset

Source: Telco Customer Churn Dataset
Size: ~7,000 customer records
Features: 21 columns (tenure, contract type, payment method, etc.)
Target Variable: Churn (Yes/No)
🛠 Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)
TensorFlow/Keras for ANN
Scikit-learn for preprocessing & evaluation
🏗 Project Workflow

Data Preprocessing
Handling missing values
Encoding categorical variables
Scaling numerical features
Exploratory Data Analysis (EDA)
Distribution of churn vs. non-churn customers
Feature correlations
Building the ANN Model
Input layer (features)
Hidden layers (ReLU activation)
Output layer (Sigmoid activation for classification)
Model Training & Evaluation
Accuracy, Precision, Recall, F1-score
Confusion Matrix
ROC Curve & AUC
📊 Results & Key Insights

✅ Model Accuracy: XX%
✅ Key Factors Influencing Churn:

Month-to-month contracts
High monthly charges
No tech support
🔥 Visualizations

📌 Confusion Matrix
📌 Training Loss & Accuracy Curves
📌 Feature Importance using SHAP
