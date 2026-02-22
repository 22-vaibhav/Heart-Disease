# ❤️ Heart Disease Prediction App

## 📌 Overview
This project is a **Machine Learning web application** that predicts the likelihood of heart disease based on user input.  
The application is built using **Python, scikit-learn, and Streamlit**, and provides an interactive interface for users to get predictions.

---

## 🚀 Features
- Predicts heart disease based on medical parameters
- User-friendly UI using Streamlit
- Uses a trained Machine Learning model (KNN)
- Includes preprocessing (scaling) for accurate predictions

---

## 🧠 Machine Learning Model
- Algorithm Used: **K-Nearest Neighbors (KNN)**
- Data Preprocessing:
  - Feature scaling using StandardScaler
- Model and preprocessing objects saved using **joblib**

Saved files:
- `KNN_heart.pkl` → trained model  
- `scaler.pkl` → scaling object  
- `columns.pkl` → feature columns  

---

## 🛠️ Tech Stack
- Python  
- scikit-learn  
- pandas  
- numpy  
- joblib  
- Streamlit  

---

## 📂 Project Structure
```markdown
```bash
Heart Disease Finder/
│
├── app.py
├── KNN_heart.pkl
├── scaler.pkl
├── columns.pkl
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository
- git clone https://github.com/22-vaibhav/Heart-Disease.git
- cd Heart-Disease

### 2. Create virtual environment
- python -m venv venv
- venv\Scripts\activate   # On Windows

### 3. Install dependencies
pip install -r requirements.txt

### 4. Run the application
python -m streamlit run app.py

---

## 📊 How it Works

1. User inputs medical details in the UI
2. Data is scaled using the saved scaler
3. Model predicts whether heart disease is present
4. Result is displayed on the screen

---

## 💡 Learning Outcomes

- Built an end-to-end ML pipeline
- Learned model serialization using joblib
- Understood importance of consistent environments
- Developed a web app using Streamlit
- Managed project using Git and GitHub