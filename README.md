# Real-Time Fraud Detection System

## 📌 Project Overview
This project detects fraudulent transactions in real-time using:
- Apache Kafka for real-time data streaming
- Apache Spark for processing transactions
- Machine Learning (XGBoost, Autoencoder)
- FastAPI for serving ML models
- MLOps tools (MLflow, Docker, Kubernetes)

## 🚀 Steps
1️⃣ **Setup Environment** (Kafka, Spark, Python)  
2️⃣ **Ingest Real-Time Transactions** using Kafka  
3️⃣ **Feature Engineering & Data Processing** with Spark  
4️⃣ **Train ML Models** for Fraud Detection  
5️⃣ **Deploy Model & API** with FastAPI  
6️⃣ **Build Web Dashboard** for monitoring  

## 📁 Project Structure
│── data/                # Raw and processed data  
│── notebooks/           # Jupyter notebooks for exploration  
│── src/                 # Source code for the fraud detection system  
│── models/              # Saved models and versions  
│── deployment/          # Scripts for deploying the model  
│── tests/               # Unit tests and validation scripts  
│── README.md            # Project documentation  

## 📈 How to Use
1. Clone this repository:
 ```sh
    git clone https://github.com/MiladEbrahimiAbyzandi/real_time_fraud_detection.git
```
2. Install dependencies:
```sh
    pip install -r requirements.txt
```

3. Run the application:
