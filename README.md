# Customer Churn Prediction using ANN

## Project Overview
Customer churn prediction is an important problem in the banking and telecom industries. This project uses an Artificial Neural Network (ANN) to predict whether a customer will leave the bank or stay.

The model is trained on customer demographic and account information to classify churn.

---

## Dataset
The dataset used is **Churn_Modelling.csv** which contains customer details such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

Target Variable:
- **Exited (1 = Customer left, 0 = Customer stayed)**

---

## Technologies Used

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Scikit-learn  
TensorFlow / Keras  

---

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Encoding
5. Train-Test Split
6. Feature Scaling
7. ANN Model Building
8. Model Training
9. Prediction
10. Model Evaluation

---

## Model Architecture

Input Layer: 11 features  
Hidden Layer: 3 neurons (Sigmoid activation)  
Output Layer: 1 neuron (Sigmoid activation)

Loss Function: Binary Crossentropy  
Optimizer: Adam  

---

## Evaluation Metric

Accuracy Score - 0.7925

---

## Future Improvements

- Hyperparameter tuning
- Add more hidden layers
- Use advanced models like XGBoost
- Deploy the model using Flask or Streamlit

---

## Author

Himanshu Bho

