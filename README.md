# ❤️ Heart Failure Prediction System

## 📌 Project Overview
The Heart Failure Prediction System is a Machine Learning-based web application that predicts whether a patient is at risk of heart failure using clinical health records. The project utilizes a Logistic Regression model trained on medical data and is deployed using Flask and Render.

This application assists healthcare professionals and researchers in identifying high-risk patients based on key clinical parameters.

---
## 🌐 Live Demo
[Live Application](https://heart-failure-prediction-ka7p.onrender.com)

---
## 🎯 Objectives
* Predict heart failure risk using patient clinical data.
* Build an interactive web application using Flask.
* Deploy a machine learning model for real-time predictions.
* Demonstrate an end-to-end machine learning workflow.

---

## ✨ Features
✅ Real-Time Heart Failure Prediction
✅ User-Friendly Web Interface
✅ Logistic Regression Machine Learning Model
✅ Instant Prediction Results
✅ Responsive Design
✅ Cloud Deployment with Render

---

## 📊 Dataset Information

### Dataset Name
Heart Failure Clinical Records Dataset

### Source
Kaggle

### Features Used
| Feature                  | Description                       |
| ------------------------ | --------------------------------- |
| Age                      | Patient age                       |
| Anaemia                  | Decrease in red blood cells       |
| Creatinine Phosphokinase | Enzyme level in blood             |
| Diabetes                 | Whether patient has diabetes      |
| Ejection Fraction        | Percentage of blood leaving heart |
| High Blood Pressure      | Hypertension status               |
| Platelets                | Platelet count                    |
| Serum Creatinine         | Level of creatinine in blood      |
| Serum Sodium             | Sodium level in blood             |
| Sex                      | Male/Female                       |
| Smoking                  | Smoking status                    |
| Time                     | Follow-up period                  |

### Target Variable

**DEATH_EVENT**
* 0 → Low Risk
* 1 → High Risk
---

## 🛠 Technologies Used

### Programming Language
* Python

### Libraries
* Pandas
* NumPy
* Scikit-Learn
* Pickle
* Flask

### Machine Learning Algorithm
* Logistic Regression

### Deployment
* Render

---

## 🔄 Machine Learning Workflow

### 1. Data Collection
* Downloaded dataset from Kaggle.
* Loaded dataset using Pandas.

### 2. Data Preprocessing
* Feature selection.
* Train-Test Split.
* Data preparation for modeling.

### 3. Model Training
* Logistic Regression Classifier.
* Model fitting on training data.

### 4. Model Evaluation
* Accuracy Score calculation.
* Performance analysis.

### 5. Model Deployment
* Saved model using Pickle.
* Developed Flask web application.
* Deployed on Render.
---

## 📁 Project Structure
```text
Heart_Failure_Prediction/
├── app.py
├── LogisticRegression_pkl.pkl
├── requirements.txt
└──README.md
```
---
## 📈 Model Performance

### Evaluation Metric
* Accuracy Score
  
The Logistic Regression model achieved satisfactory performance for heart failure risk classification and can be further improved using advanced machine learning techniques.

---

## 🚀 Deployment
The application is deployed using Render.

---

## 💡 Future Enhancements
* Random Forest Classifier
* XGBoost Classifier
* Risk Probability Score
* Data Visualization Dashboard
* Patient History Tracking
* Email Notification System
* Power BI Integration
---

## 📷 Application Features

### Input Parameters
* Age
* Anaemia
* Creatinine Phosphokinase
* Diabetes
* Ejection Fraction
* High Blood Pressure
* Platelets
* Serum Creatinine
* Serum Sodium
* Sex
* Smoking
* Follow-Up Time

### Output
* ✅ Low Risk of Heart Failure
* ⚠️ High Risk of Heart Failure
---

## 👩‍💻 Author

**Pranita Mothe**

*mothepranita@gmail.com
Data Analyst | Machine Learning Enthusiast

### Skills
* Python
* SQL
* Power BI
* Tableau
* Machine Learning
* Data Analytics
* Data Visualization
---
## ⭐ Support
If you found this project useful, please consider giving it a ⭐ on GitHub.

---
## 📜 License
This project is developed for educational, internship, academic, and portfolio purposes.
