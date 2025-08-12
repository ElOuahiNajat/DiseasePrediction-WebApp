# Disease Prediction WebApp

An intelligent web application for predicting diseases based on user symptoms, integrating an **AI conversational assistant** and a **machine learning** model to provide personalized medical recommendations.

---

## Problem Statement

In many cases, individuals experience symptoms but do not have immediate access to a doctor or sufficient knowledge to correctly interpret these signs. This lack of initial guidance can delay diagnosis, worsen health conditions, and cause anxiety.

---

## Objectives

- Provide a **self-health assessment tool** based on symptoms.
- Predict the most likely diseases via an **artificial intelligence model**.
- Offer an **AI conversational assistant** to help and inform users.
- Provide **personalized recommendations**: precautions, medications, diets, etc.
- Raise awareness about **prevention** and encourage **early care**.

---

## Main Features

- **Interactive symptom input**
- **Intelligent prediction of the probable disease**
- **AI conversational assistant** guiding the user
- **Personalized medical advice**:
  - Precautions to take
  - Possible medications
  - Suitable diet
  - Recommended physical activities
- 🌐 **Simple and accessible web interface**

---

## About the AI Assistant

The application includes an **AI conversational assistant** capable of:

- Guiding the user in symptom input.
- Answering basic medical questions.
- Providing explanations about diseases and treatments.
- Enhancing user experience with an interactive and human-like interface.

---

## 🛠️ Technologies Used

| Technology       | Description                  |
| ---------------- | ---------------------------- |
| Python / Flask   | Backend of the application   |
| HTML / CSS / JS  | Web frontend                |
| Scikit-learn     | Disease prediction (SVM)    |
| Pandas / NumPy   | Data manipulation           |
| Simple NLU chatbot | User interaction           |
| CSV Datasets     | Symptoms, diseases, medications, etc. |

---

## 📁 Project Structure

DiseasePrediction-WebApp/

│  
├── app.py              # Main Flask application  
├── chatbot_server.py   # AI chatbot  
├── model_predictor.py  # Disease prediction  
├── model_SVM.py        # SVM model training  
├── static/             # CSS and JS files  
├── templates/          # HTML pages  
├── data/               # CSV files: symptoms, medications, etc.  
└── .env                # Environment variables  

---

## Project Architecture
![disease_prediction_architecture](https://github.com/user-attachments/assets/20c54262-f69c-4aa7-a48e-c113cc0fd1d2)

---

## Demo  
https://youtu.be/YVXTZ06m1Zw

---

## Local Installation

1. **Clone the GitHub repository**:  
```bash
git clone https://github.com/ElOuahiNajat/DiseasePrediction-WebApp.git
cd DiseasePrediction-WebApp


2. **Create a virtual environment (optional)** :
python -m venv env
source env/bin/activate  # (Linux/macOS)
env\Scripts\activate     # (Windows)

3. **Run the Flask server** :
python app.py

4.**Access the application** :
Open your browser at: http://127.0.0.1:5000


Data Used
Predictions are based on reliable medical datasets contained in CSV files:

Symptom-severity.csv

description.csv

precautions_df.csv

medications.csv

diets.csv

workout_df.csv
```
---
## Notes
⚠️  This project is designed for educational and informational purposes only. It does not replace professional medical advice. For any health issues, please consult a healthcare professional.

