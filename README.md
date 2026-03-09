# Black Friday Purchase Prediction

This project predicts customer purchase amounts using machine learning.

**Technologies Used:**
- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest Regressor

**Pipeline:**
1. Data Cleaning
2. Encode Categorical Columns
3. Train/Test Split
4. Handle Missing Values
5. Feature Scaling
6. Model Training
7. Prediction & Evaluation


Client Requirement: Predict how much customers will spend on Black Friday
└─> Data Collection
      └─ CSV: train.csv (Customer & Purchase info)
           |
           v
┌─────────────────────────────┐
│  Data Cleaning & Exploration│
│  - Check missing values     │
│  - Check column types       │
│  - Understand distributions │
└─────────────────────────────┘
           |
           v
┌─────────────────────────────┐
│  Feature Engineering        │
│  - Encode categorical data  │
│  - Drop unnecessary columns │
│  - Create new features      │
└─────────────────────────────┘
           |
           v
┌─────────────────────────────┐
│  Train/Test Split           │
│  - X_train, X_test          │
│  - y_train, y_test          │
└─────────────────────────────┘
           |
           v
┌─────────────────────────────┐
│  Handle Missing Values      │
│  - Imputer (replace NaN)    │
└─────────────────────────────┘
           |
           v
┌─────────────────────────────┐
│  Feature Scaling            │
│  - StandardScaler (mean=0,  │
│    std=1)                   │
└─────────────────────────────┘
           |
           v
┌─────────────────────────────┐
│  Model Training             │
│  - Random Forest Regressor  │
└─────────────────────────────┘
           |
           v
┌─────────────────────────────┐
│  Prediction                 │
│  - Predict Purchase amount  │
└─────────────────────────────┘
           |
           v
┌─────────────────────────────┐
│  Evaluation                 │
│  - MAE, RMSE, R²            │
│  - Check first predictions  │
└─────────────────────────────┘
           |
           v
Client sees accurate predicted purchases → Adjust marketing & inventory
