# MLOps with Project Development – ML Project

## 📌 Overview

This project was developed as part of the **"MLOps with Project Development"** workshop organized by the **Department of Computer Engineering** for third-year students on **30th and 31st May 2025**.

The objective of the project was to integrate **Machine Learning (ML)** practices with **DevOps** principles (MLOps), covering the full pipeline from data preprocessing to model deployment.

---

## 🛠 Tech Stack

- **Python** (ML implementation)
- **VS Code** (IDE)
- **Git & GitHub** (Version control)
- **Jupyter Notebook** / Python Scripts
- **ML Libraries**: `scikit-learn`, `pandas`, `matplotlib`
- **MLOps Tools** (Optional/If used): `DVC`, `MLflow`, `Docker`

---


## 📂 Project Structure
ML_Proj3-main/
├── artifacts/ # Stored intermediate files (models, scalers)
├── catboost_info/ # CatBoost specific data (if used)
├── logs/ # Log files for monitoring
├── notebook/ # Jupyter notebooks for EDA & training
│ └── data/
│ ├── stud.csv
│ ├── 1. EDA STUDENT.ipynb
│ └── 2. MODEL TRAINING.ipynb
├── src/ # Core source code
│ ├── components/ # Model training, evaluation modules
│ ├── pipeline/ # Data pipeline code
│ ├── exception.py # Custom exception handling
│ ├── logger.py # Logging setup
│ └── utils.py # Utility functions
├── templates/ # Web interface (HTML templates)
├── app.py # Flask app for deployment
├── setup.py # Project setup script
├── requirements.txt # Python dependencies
└── README.md # Project documentation

---



## 📊 Notebooks

1. `1. EDA STUDENT.ipynb` - Exploratory Data Analysis
2. `2. MODEL TRAINING.ipynb` - Model training and testing


## 🔧 Setup Instructions

```bash
git clone https://github.com/your-username/ML_Proj3.git
cd ML_Proj3-main
python -m venv venv
source venv/bin/activate    # Or `venv\Scripts\activate` on Windows
pip install -r requirements.txt


To run the Flask app:
python app.py

