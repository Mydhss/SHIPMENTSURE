## Shipment Delivery Prediction System

## Overview

A Machine Learning project that predicts whether a shipment will be delivered **on time** or **delayed** based on customer, product, and shipment-related factors. The model is deployed using **Streamlit** for real-time predictions. 

## Features

* Data cleaning and preprocessing
* Outlier handling using IQR
* Feature encoding and scaling
* Feature engineering using Cost-to-Weight Ratio
* Class balancing using SMOTE
* Multiple ML model comparison
* Streamlit-based prediction interface 

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* LightGBM
* Streamlit
* Joblib

## Models Evaluated

* Logistic Regression
* Decision Tree
* Random Forest
* KNN
* SVM
* Naive Bayes
* XGBoost
* LightGBM

XGBoost was selected as the final model due to its superior performance. 

## Project Workflow

1. Data Cleaning
2. Feature Engineering
3. Data Balancing using SMOTE
4. Model Training & Evaluation
5. Model Selection
6. Streamlit Deployment

## Run the Project

```bash
pip install -r requirements.txt
```

```bash
python Shipmentsure_final.py
```

```bash
streamlit run app.py
```

## Project Structure

```text
Shipment-Delivery-Prediction/
│
├── Train.csv
├── Shipmentsure_final.py
├── app.py
├── best_xgboost_model.pkl
├── feature_columns.pkl
├── label_encoders.pkl
└── README.md
```

## Future Improvements

* Real-time shipment tracking
* Cloud deployment
* Explainable AI integration
* Automated model retraining
