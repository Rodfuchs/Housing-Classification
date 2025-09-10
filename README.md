# 🏠 House Price Classification

Predict whether a house is **Expensive** or not using a **Random Forest Classifier**.

---

## 🚀 Features

- Handles missing values and cleans data
- Encodes categorical variables:
  - Ordinal encoding for ordered categories
  - One-hot encoding for nominal categories
- Scales numerical features
- Model: **Random Forest Classifier**
- Hyperparameter tuning using **GridSearchCV**
- Evaluates with:
  - Accuracy
  - F1 Score
  - Precision
  - Recall
  - ROC AUC

---

## 📂 Repo Structure

house-price-classification/
│
├── notebooks/ # Full notebook with exploration
├── src/ # Scripts for preprocessing, training, evaluation
│ ├── preprocessing.py
│ ├── train.py
│ └── evaluate.py
├── requirements.txt # Dependencies
└── README.md



---

## 💻 Quick Start

## 1️⃣ Clone the repo:


git clone https://github.com/YOUR_USERNAME/house-price-classification.git
cd house-price-classification

## 2️⃣ (Optional) Create a virtual environment:


python -m venv venv
# Activate Linux/Mac
source venv/bin/activate
# Activate Windows
venv\Scripts\activate

## 3️⃣ Install dependencies:

pip install -r requirements.txt

## 4️⃣ Run notebook for exploration:

jupyter notebook notebooks/house-price-classification.ipynb

## 5️⃣ Train and evaluate via scripts:


python src/train.py
python src/evaluate.py

## ⚡ Example Results

Training Accuracy: 0.999
Testing Accuracy: 0.949
F1 Score: 0.795
Precision Score: 0.829
Recall Score: 0.763
ROC AUC Score: 0.981
