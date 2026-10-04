
# 🛡️ Upi_Fraud_Shield_ML_
### Intelligent UPI Fraud Detection System Using Machine Learning

UPI Fraud Shield ML is an end-to-end Machine Learning-powered web application designed to identify potentially fraudulent UPI transactions using behavioral, transactional, authentication, and account-level features.

The system leverages multiple Machine Learning algorithms, Explainable AI (SHAP), interactive dashboards, and model evaluation techniques to provide real-time fraud risk assessment and transparent predictions.

---

## 🚀 Project Overview

With the rapid growth of digital payments, fraudulent transactions have become a major concern for users and financial institutions. Traditional rule-based fraud detection systems struggle to identify sophisticated and evolving fraud patterns.

UPI Fraud Shield ML addresses this challenge by:

- Detecting suspicious transactions using Machine Learning
- Calculating fraud probability scores
- Providing explainable predictions using SHAP
- Comparing multiple machine learning models
- Visualizing model performance and insights
- Maintaining prediction history for analysis

---

## ✨ Features

### 🔐 User Authentication
- User Registration
- Secure Login System
- Session Management

### 🤖 Fraud Prediction
- Real-time Fraud Risk Assessment
- Fraud Probability Calculation
- Approved/Blocked Transaction Classification

### 📊 Analytics Dashboard
- ROC Curve Comparison
- Model Performance Analysis
- Feature Importance Visualization
- Confusion Matrix Analysis

### 🧠 Explainable AI
- SHAP Feature Contribution Analysis
- Transparent Model Predictions
- Explainable Fraud Detection

### 📝 Prediction History
- Store Previous Predictions
- View Transaction Records
- Track Prediction Timestamps

---

## 🏗️ System Architecture

```text
User
   ↓
Streamlit Web Application
   ↓
Feature Engineering Module
   ↓
Machine Learning Models
   ↓
Fraud Prediction Engine
   ↓
SHAP Explainability
   ↓
Analytics Dashboard
   ↓
Prediction History Storage
```

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Web Framework
- Streamlit

### Machine Learning Libraries
- Scikit-Learn
- SHAP
- Pandas
- NumPy

### Visualization Libraries
- Matplotlib
- Plotly

### Model Serialization
- Joblib

---

## 🤖 Machine Learning Models Evaluated

The following machine learning algorithms were trained and evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting
5. Neural Network (MLP)

The best-performing model was selected and deployed for fraud prediction.

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## 📂 Project Structure

```text
upi-fraud-ml/
│
├── src/
│   ├── app.py
│   ├── auth.py
│   ├── history.py
│   ├── models.py
│   ├── feature_engineering.py
│   ├── evaluator.py
│   ├── shap_explainer.py
│   └── data_generator.py
│
├── models/
│   ├── best_model.pkl
│   ├── scaler.pkl
│   ├── feature_cols.pkl
│   ├── label_encoders.pkl
│   ├── roc_curves.png
│   ├── confusion_matrices.png
│   ├── feature_importance.png
│   └── model_comparison.png
│
├── dataset/
│
├── notebooks/
│
├── users.json
├── predictions.json
├── requirements.txt
└── README.md
```

---

## 📊 Features Used

The fraud detection model utilizes transaction, behavioral, authentication, and account-level features such as:

- Transaction Amount
- Transaction Type
- Authentication Attempts
- Session Source
- Transaction Velocity
- OTP Request Frequency
- Receiver Account Age
- Receiver Transaction History
- Handle Similarity Score
- Business Name Match
- Background Data Usage
- Request Frequency
- Geographic Features
- Device Behavioral Features

---

## 📷 Application Modules

### Login Page
Secure authentication for registered users.

### Registration Page
New user account creation.

### Fraud Prediction Dashboard
Transaction input and fraud probability prediction.

### Analytics Dashboard
Interactive visualizations and model comparison.

### SHAP Dashboard
Explainable AI and feature contribution analysis.

### Prediction History
Storage and review of previous predictions.

---

## 📌 Installation




### Move into Project Directory

```bash

## Run it from the VS Code terminal

1. Open the terminal with **Terminal → New Terminal**. Make sure it is PowerShell.

2. Go to the project root:

   ```powershell
   cd "D:\UPI Fraud Detection Using ML & AI"
   ```

3. Activate the virtual environment:

   ```powershell
   & ".\.venv\Scripts\Activate.ps1"
   ```

   If PowerShell blocks activation, run this once in the same terminal, then activate again:

   ```powershell
   Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned
   ```


yaha se bhi direct start kar sakte hai
by Aditya Raj
 terminal --> then new terminal  --> select down arrow and select command promt after that run the program 


4. Go to the folder containing the app:

   ```powershell
   cd ".\upi-fraud-ml-fixed\upi-fraud-ml-fixed\upi-fraud-ml\artifacts\ml-fraud-detection"
   ```

5. Start the app:

   ```powershell
   python -m streamlit run app.py
   ```

6. When Streamlit prints a URL such as `http://localhost:8501`, open it in your browser. **Keep the terminal open while using the app**; closing it stops the app.

To stop the app, return to the terminal and press **Ctrl+C**.

If you see a “port already in use” message, run it on port 8502 instead:

```powershell
python -m streamlit run app.py --server.port 8502
```

Then open `http://localhost:8502`.   


1 ye yaha se alag hai

cd upi-fraud-ml-fixed
cd upi-fraud-ml
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python -m streamlit run artifacts\ml-fraud-detection\app.py```

---

## 🌐 Live Demo

Coming Soon...

(After deployment, add your Streamlit deployment link here.)

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Machine Learning Workflow
- Data Preprocessing
- Feature Engineering
- Fraud Detection Systems
- Explainable AI (XAI)
- Model Evaluation
- Streamlit Application Development
- Data Visualization
- Model Deployment

---

## 🔮 Future Enhancements

- Real-Time Banking API Integration
- Cloud Deployment using AWS
- Mobile Application Support
- Deep Learning-Based Fraud Detection
- Continuous Model Retraining
- Fraud Alert Notification System
- Graph Neural Network Integration

---

## 👨‍💻 Author

**Aditya Raj**

BCA (Hons. with Research) Specilization in Data Analysis  
Galgotias University

📧 Email: adityarajpandit2003@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/aditya-raj-091630422/ 

💻 GitHub: https://github.com/AdityaRaj25052003 

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
