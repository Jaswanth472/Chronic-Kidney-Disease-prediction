# 🩺 CKD Prediction Web App

A simple and user-friendly **Flask web application** that predicts **Chronic Kidney Disease (CKD)** based on 24 medical input parameters provided by the user.

---

## 🔍 Project Overview

This project leverages a trained **Support Vector Machine (SVM)** model to assess the likelihood of CKD. Users enter medical data into a web form, and the app instantly predicts whether the person is likely to have CKD or not.

---

## 🛠️ Tech Stack

- 🐍 Python  
- ⚙️ Flask  
- 📊 Scikit-learn  
- 🌐 HTML / CSS  
- 🧪 Jupyter Notebook  
- 🗃️ Git & GitHub  

---

## 📁 Project Structure

CKD_Deployment/
│
├── app.py # Flask backend application
├── svm_classifier_pipeline.pkl # Trained ML model
├── requirements.txt # Project dependencies
├── README.md # Project documentation
│
├── templates/ # HTML templates (index.html, form.html, result.html)
├── static/ # CSS and image assets (styles.css, logo.png, etc.)
├── ScreenShots/ # Screenshots of app interface
└── CKD_Model_Training.ipynb # Jupyter notebook for model training and evaluation


---

## 🚀 How to Run the Project Locally

```bash
# 1. Clone the repository
git clone https://github.com/Sriram1908/ckd-prediction-app.git
cd ckd-prediction-app

# 2. Create and activate virtual environment (Windows)
python -m venv venv
.\venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Flask application
python app.py
```
Then open your browser and navigate to:
http://127.0.0.1:5000

📸 Output Screenshots
Homepage of the web application

CKD input form with user medical parameters

Prediction result page

All screenshots are available in the /ScreenShots folder.

📚 Dataset Used
Source:https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease

Format: .csv

Total features: 24 medical attributes + 1 target label
🙋‍♂️ Author
Sriram Y
📂 GitHub: Sriram1908
📬 Email:  yvenkatasriramreddy@gmail.com

