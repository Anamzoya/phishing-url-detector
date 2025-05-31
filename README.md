# 🧠 Phishing URL Detector

Detect phishing websites using machine learning. This project uses a Random Forest classifier trained on a dataset of URLs with labeled classes: `phishing` and `legitimate`.

> 🔒 Built for Nas Academy's AI Program - helping teenagers learn AI and cyber security!

---

## 🚀 Demo

![ROC Curve](images/roc_curve.png)

---

## 📁 Folder Structure
phishing-url-detector/
├── data/ # Dataset (.parquet)
├── notebook/ # Jupyter Notebook
├── images/ # Visuals
├── requirements.txt # Required Python packages
├── README.md # Project overview
└── .gitignore # Files to ignore


---

## 📊 Features Used

- Length of URL
- Presence of HTTPS
- Use of `@`, `-`, `//`, or suspicious characters
- Domain name structure
- And more...

---

## 🔍 How It Works

1. Load dataset
2. Extract features
3. Train model using RandomForestClassifier
4. Evaluate with accuracy, confusion matrix, ROC-AUC
5. Visualize feature importance

---

## 📦 Requirements

Install requirements with:

```bash
pip install -r requirements.txt
