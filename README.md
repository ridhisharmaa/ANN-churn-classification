# 📊 Customer Churn Prediction (ANN)

A machine learning web app that predicts whether a customer is likely to churn and estimates salary using an Artificial Neural Network (ANN).

---

🚀 Live Apps
🔸 Customer Churn Prediction

🔗 https://ann-churn-classification-ygk86vidcuukae2upvzta6.streamlit.app/

🔸 Salary Estimation

🔗 https://ann-salary-estimation-6gc5rjwjpwa4tfvxcekerj.streamlit.app/

---

🧠 About the Projects
📌 1. Customer Churn Prediction

Predicts whether a customer is likely to leave a bank based on features like:

Credit Score
Geography
Gender
Age
Balance
Number of Products
Active Status

👉 Output: Churn Probability (0 or 1)

📌 2. Salary Estimation

Predicts the estimated salary of a customer using similar features.

👉 Output: Predicted Salary Value

---

## ⚙️ Tech Stack

- **Python**
- **Streamlit** (for web app)
- **NumPy, Pandas**
- **Scikit-learn** (preprocessing)
- **TensorFlow / Keras** (ANN model)

---

## 🧩 Model

🔹 Churn Model
Type: ANN (Binary Classification)
Activation: Sigmoid
Loss: Binary Crossentropy
🔹 Salary Model
Type: ANN (Regression)
Activation: Linear Output
Loss: Mean Absolute Error (MAE)
---

## 📂 Project Structure
├── app.py # Churn prediction app 
├── streamlit_regression.py # Salary estimation app 
├── model.h5 # Churn model 
├── regression_model.h5 # Salary model 
├── scaler.pkl 
├── label_encoder_gender.pkl 
├── ohe.pkl 
├── experiments.ipynb 
├── salaryregression.ipynb 
├── hyperparametertuningann.ipynb 
├── requirements.txt 
├── runtime.txt 
└── README.md


---

## ☁️ Deployment

Both applications are deployed using **Streamlit Cloud**.

---