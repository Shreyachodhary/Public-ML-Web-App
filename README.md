# Public ML Web App 🌐

A Streamlit web application that allows users to use pre-trained machine learning models for health diagnosis predictions based on user inputs.

---

## 📌 Overview

This web app provides an interactive interface for predicting health conditions like **diabetes**, **heart disease**, and **Parkinson’s disease**. Users can input relevant health metrics into the app, and the app uses trained models to output the likelihood or risk score of the condition.

---

## 🛠️ Models & Files

| File | Description |
|------|-------------|
| `diabetes_model.sav` | Trained model file for diabetes prediction. |
| `heart_disease_model.sav` | Trained model file for heart disease prediction. |
| `parkinsons_model.sav` | Trained model file for Parkinson’s disease prediction. |
| `mdps_public.py` | Main Python script for the Streamlit app. It loads models, defines user input interface, makes predictions. |
| `requirements.txt` | Lists all Python packages required to run the app. |

---

## 🚀 Live Demo

Check out the deployed app here:  
[Public ML Web App](https://public-ml-web-app-m6ahysamrqgauju9ynevrf.streamlit.app/)

---

## 🧪 How It Works (User Flow)

1. Navigate to the web app in your browser.  
2. Choose which prediction you want (Diabetes / Heart Disease / Parkinson’s disease).  
3. Enter the required input values (health metrics).  
4. Submit → The app returns a prediction.  

---

## 🔧 Setup & Usage

To run this locally:

```bash
# Clone repository
git clone https://github.com/Shreyachodhary/Public-ML-Web-App.git
cd Public-ML-Web-App

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run mdps_public.py

---

## 📊 Technologies Used

- Python  
- Streamlit  
- Scikit-learn  
- Pickle / Joblib (for model serialization)  
- Basic HTML / CSS (Streamlit built-in)  

---

## ✅ Future Work

- Add more health datasets / models (e.g. Cancer, Alzheimer’s)  
- Improve model accuracy via hyperparameter tuning  
- Add user authentication and data saving functionality  
- Deploy on a cloud platform (AWS / GCP) for better scalability  

---

## 🧑‍💻 Author

**Shreya Chaudhary**  
- [GitHub](https://github.com/Shreyachodhary)  
- [LinkedIn](https://www.linkedin.com/in/shreya-chaudhary-a80b49296)  
