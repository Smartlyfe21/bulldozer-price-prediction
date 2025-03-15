# 🚜 Predicting Bulldozer Sale Prices using Machine Learning  

## 📌 Overview  
This project explores how machine learning can be used to **predict the sale price of bulldozers** based on historical auction data. It is inspired by the **Kaggle Bluebook for Bulldozers** competition.  

## 🎯 Problem Definition  
How accurately can we predict the future sale price of a bulldozer given its features and past sales data?  

## 📊 Dataset  
The dataset is from the **[Kaggle Bluebook for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers/data)** competition. It consists of three main files:  

- `Train.csv` – Training data (up to the end of 2011)  
- `Valid.csv` – Validation data (Jan 1, 2012 - Apr 30, 2012)  
- `Test.csv` – Final test data (May 1, 2012 - Nov 2012)  

🔹 **Data Dictionary**: [Google Sheets Data Dictionary](https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?usp=sharing)  

## 🏆 Evaluation Metric  
The model is evaluated using **Root Mean Squared Log Error (RMSLE)** to measure how well it predicts auction prices.  

## 🚀 Features & Model  
The dataset includes various features like **machine age, product size, usage hours**, etc.  
We train different machine learning models (e.g., **Random Forest, XGBoost**) and optimize performance using **hyperparameter tuning**.  

## 📈 Results  
- Our best model (Random Forest) achieved an **RMSLE of X.XX**  
- Feature importance analysis showed that **machine age and product size** were key factors  
- Other models tested:  
  - XGBoost: **X.XX RMSLE**  
  - Linear Regression: **X.XX RMSLE**  

_(Update RMSLE values once the model is finalized)_  

## 📂 Project Structure
├── 📄 end-to-end-bulldozer-price-regression.ipynb # Main notebook
├── 📄 README.md # Project documentation
├── 📂 data/ # Folder for dataset files (optional)
│ ├── Train.csv # Training dataset (optional)
│ ├── Valid.csv # Validation dataset (optional)
│ ├── Test.csv # Test dataset (optional)
└── 📂 models/ # Folder for trained models (optional)
├── model.pkl # Saved trained model (if applicable)
├── feature_importance.png # Feature importance

## 📌 How to Use  
1️⃣ Clone the repo:  
   ```bash
   git clone https://github.com/Smartlyfe21/bulldozer-price-prediction.git
   cd bulldozer-price-prediction
