# Banking-Fraud-Ditection-
Developed an end-to-end banking fraud detection project using Python, Random Forest machine learning, and Power BI to analyze transaction patterns, detect fraudulent activities, evaluate model performance with confusion matrix analysis, and visualize fraud insights through an interactive analytics dashboard.
Banking Fraud Detection – Machine Learning & Power BI Project
📌 Project Overview

This project focuses on detecting fraudulent banking transactions using machine learning and interactive data visualization techniques. The analysis was performed using Python for data processing, exploratory data analysis (EDA), and predictive modelling, while Power BI was used to create an interactive fraud analytics dashboard.

The objective of this project was to identify fraudulent transactions, analyze transaction patterns, and evaluate the performance of a fraud detection model.

🎯 Project Objectives
Analyze banking transaction behaviour and fraud patterns
Perform exploratory data analysis on fraud data
Build a machine learning classification model for fraud detection
Evaluate model performance using classification metrics
Visualize fraud insights through Power BI dashboards
📂 Dataset Information
Column	Description
Amount	Transaction amount
V1–V28	Anonymized transaction features
Class	Fraud (1) or Normal (0)
🛠️ Technologies Used
Tool	Purpose
Python	Data analysis & machine learning
Pandas	Data cleaning
Matplotlib & Seaborn	Data visualization
Scikit-learn	Machine learning
Random Forest	Fraud prediction model
Power BI	Dashboard visualization
Jupyter Notebook	Development environment
📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

Fraud vs non-fraud transaction distribution
Transaction amount analysis
Correlation heatmap
Box plot analysis
Feature importance analysis
Confusion matrix evaluation
🤖 Machine Learning Model
Model Used
Random Forest Classifier
Workflow
Data preprocessing
Feature selection
Train-test split
Model training
Fraud prediction
Performance evaluation
📈 Model Evaluation Metrics

The model was evaluated using:

Precision
Recall
F1-score
Accuracy
Confusion Matrix

The Random Forest model achieved very high fraud detection performance with minimal classification errors.

📊 Power BI Dashboard Features
KPI Cards
Total Transactions
Fraud Transactions
Fraud Rate %
Total Fraud Amount
Visualizations
Fraud Distribution Chart
Transaction Amount Histogram
Prediction Summary
Feature Importance Plot
Confusion Matrix
Filters
Fraud Class
Transaction Amount
📷 Dashboard Preview
<img width="800" alt="Dashboard Preview" src="YOUR_IMAGE_LINK_HERE">
📁 Project Structure
Banking-Fraud-Detection/
│
├── data/
│   └── creditcard.csv
│
├── notebooks/
│   └── fraud_detection.ipynb
│
├── visuals/
│   ├── heatmap.png
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   └── dashboard.png
│
├── dashboard/
│   └── fraud_dashboard.pbix
│
├── report/
│   └── Banking_Fraud_Detection_Project_Report.docx
│
└── README.md
🚀 How to Run the Project
1. Install Required Libraries
pip install pandas numpy matplotlib seaborn scikit-learn
2. Run the Notebook

Open Jupyter Notebook and run:

fraud_detection.ipynb
📤 Export Predictions
results = pd.DataFrame({
    'Actual': y_test,
    'Predicted': y_pred
})

results.to_csv("fraud_predictions.csv", index=False)
💡 Key Insights
Fraudulent transactions represented a small portion of the dataset
Certain anonymized features had strong predictive importance
The Random Forest model effectively classified fraudulent transactions
Data visualization improved understanding of fraud behaviour patterns
📌 Future Improvements
Implement XGBoost and LightGBM models
Deploy the model using Flask or Streamlit
Add real-time fraud detection
Improve handling of imbalanced datasets
👨‍💻 Author

Vaheeson Vasanthakumar
MSc Data Science – University of East London
BSc Software Engineering – University of Plymouth

⭐ Project Highlights

✔ End-to-end machine learning workflow
✔ Fraud analytics and prediction
✔ Interactive Power BI dashboard
✔ Professional reporting and visualization
✔ Real-world banking analytics use case
