# Privilege Escalation Attack Detection in Cloud using Machine Learning

## Overview

Privilege escalation attacks are among the most critical cybersecurity threats in cloud environments. Attackers exploit vulnerabilities or misuse privileges to gain unauthorized access to sensitive resources.

This project presents a Machine Learning-based detection framework that identifies potential privilege escalation activities using behavioral analytics and anomaly detection techniques. Multiple ensemble learning algorithms were evaluated to improve threat detection accuracy and reduce false positives.

---

## Problem Statement

Cloud infrastructures generate large volumes of user activity logs. Traditional rule-based security systems often struggle to detect sophisticated insider threats and privilege escalation attempts.

The objective of this project is to build an intelligent detection system capable of:

* Identifying suspicious user activities
* Detecting insider threats
* Recognizing privilege escalation attempts
* Improving security monitoring through machine learning

---

## Dataset

### CERT Insider Threat Dataset

The project utilizes behavioral security data inspired by the CERT Insider Threat Dataset.

Features include:

* User login activities
* Device access records
* File access events
* Network activities
* Email communication patterns
* System usage logs

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Data Normalization
5. Model Training
6. Model Evaluation
7. Threat Classification
8. Performance Analysis

---

## Machine Learning Models Used

### Random Forest

Used for baseline classification and feature importance analysis.

### XGBoost

Gradient boosting model for high-performance classification.

### AdaBoost

Adaptive boosting model for improved classification performance.

### LightGBM

Achieved the highest accuracy among all evaluated models.

### CatBoost

Implemented for categorical feature handling and robust performance.

---

## Results

| Model         | Accuracy |
| ------------- | -------- |
| Random Forest | 94%      |
| XGBoost       | 96%      |
| AdaBoost      | 95%      |
| CatBoost      | 96%      |
| LightGBM      | 97%      |

Best Performing Model:

LightGBM – 97% Accuracy

---

## Technologies Used

### Programming

* Python

### Libraries

* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* LightGBM
* CatBoost
* Matplotlib

### Machine Learning

* Ensemble Learning
* Classification Models
* Anomaly Detection
* Feature Engineering

---

## Key Features

* Insider Threat Detection
* Privilege Escalation Detection
* Behavioral Analytics
* Ensemble Learning Models
* Security Event Classification
* Performance Evaluation Dashboard

---

## Future Enhancements

* Real-time Threat Monitoring
* SIEM Integration
* Explainable AI for Security Analytics
* Cloud-native Deployment
* Deep Learning Based Threat Detection

---

## Project Structure

project/

├── data/

├── notebooks/

├── models/

├── reports/

├── README.md

---

## Author

Khushal Viswas Bheemavarapu

B.Tech CSE (AI & ML)

CMR College of Engineering & Technology

LinkedIn:
https://www.linkedin.com/in/khushal-viswas-bheemavarapu

GitHub:
https://github.com/khushalviswas

---

## Keywords

Cybersecurity, Privilege Escalation Detection, Insider Threat Detection, Machine Learning, Cloud Security, LightGBM, XGBoost, Random Forest, Security Analytics, Anomaly Detection

