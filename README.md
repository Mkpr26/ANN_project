Link of deployment : https://mkpra26-ann.streamlit.app/

# 🧠 Artificial Neural Network for Customer Churn Prediction  

This project implements an **Artificial Neural Network (ANN)** to predict **customer churn** (whether a customer will leave the bank).  
It includes **data preprocessing, model training, evaluation, and deployment** of the model as a simple app.  

## 📂 Project Structure

ANN_project/
│── app.py # Deployment script (Streamlit/FastAPI)
│── experiments.ipynb # Data exploration & model experiments
│── prediction.ipynb # Model inference on new data
│── Churn_Modelling.csv # Dataset
│── model.h5 # Trained ANN model
│── scaler.pkl # Saved StandardScaler
│── label_encoder_gender.pkl # Encoder for Gender
│── onehot_encoder_geo.pkl # Encoder for Geography
│── requirements.txt # Python dependencies
│── README.md # Project documentation



---

## ⚙️ Tech Stack

- **Programming:** Python  
- **Libraries:** TensorFlow, Keras, Scikit-learn, Pandas, NumPy, Matplotlib  
- **Deployment:** Streamlit / FastAPI (app.py)  
- **Version Control:** Git & GitHub  

---

## 📝 Features

- Data preprocessing (scaling, label encoding, one-hot encoding)  
- ANN model for churn prediction  
- Training, validation, and performance evaluation  
- Saving model & preprocessing artifacts (`.h5` & `.pkl`)  
- Simple app for predictions on new data  

---

## 📊 Model Performance

- **Loss function:** Binary Crossentropy  
- **Optimizer:** Adam

 🔮 Future Improvements

--> Hyperparameter tuning with GridSearchCV / Optuna
--> Model explainability (SHAP, LIME)
--> Add Dockerfile for containerized deployment
--> Deploy via FastAPI with REST endpoints
