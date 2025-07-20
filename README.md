# PROJECT7 : 💳 Credit Card Fraud Detection Project

>✅ Level 2- Task 3

A comprehensive machine learning project to detect fraudulent credit card transactions using anomaly detection and supervised classification models.


### 🚀 Project Overview

This project explores a real-world credit card dataset and applies both **unsupervised** and **supervised** machine learning techniques to detect fraud. It covers key concepts including anomaly detection, real-time monitoring, and system scalability.



### 🧠 Key Concepts Implemented

- 🔍 **Anomaly Detection**: Isolation Forest for unsupervised outlier detection.
- 🤖 **Machine Learning Models**: Random Forest classifier for supervised prediction.
- ⚙️ **Feature Engineering**: Scaling and transformation of time and amount features.
- 🛰️ **Real-time Monitoring**: Simulated fraud prediction in real-time.
- 📈 **Scalability Planning**: Strategy for handling large-scale production systems.


### 📂 Dataset

-`creditcard.csv`: Contains 284,807 European credit card transactions with anonymized features and labels indicating fraud (1) or legitimate (0)


### 📊 Model Performance

- **Anomaly Detection (Isolation Forest)**:
  - Precision & Recall compared against true labels
- **Supervised ML (Random Forest)**:
  - Confusion matrix, classification report
  - ROC-AUC: ~0.99



### 🧪 Tech Stack

- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib & Seaborn for Visualization
- Jupyter Notebook


### 📈 Future Enhancements

- Add XGBoost / Neural Networks for comparison
- Save and deploy model via Flask API
- Stream data using Kafka for true real-time scoring
- Set up dashboard for live fraud alerts



