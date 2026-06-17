# 🎓 Student Performance Prediction System

## 📌 Overview

The Student Performance Prediction System is a machine learning-based web application designed to predict student academic performance using demographic, social, and educational factors.

This project focuses on applying data analysis, preprocessing, feature engineering, and supervised machine learning techniques to identify patterns affecting student outcomes. The system helps demonstrate how predictive analytics can support academic monitoring and performance evaluation.

---

# 🚀 Features

- Student score prediction using machine learning
- Data preprocessing and feature engineering
- Interactive Flask-based web interface
- End-to-end ML pipeline
- Model training and evaluation
- REST-style prediction workflow
- Docker support for deployment
- Clean modular project structure

---

# 🛠️ Tech Stack

## Machine Learning & Data Analysis
- Pandas
- NumPy
- Scikit-learn
- CatBoost

## Data Visualization
- Matplotlib
- Seaborn

## Backend & Deployment
- Flask
- Docker
- Dill

---

# 📊 Machine Learning Workflow

The project follows a complete ML pipeline including:

- Data ingestion
- Data cleaning
- Feature transformation
- Model training
- Model evaluation
- Prediction pipeline deployment

The trained model predicts student performance based on multiple educational and behavioral attributes.

---

# 📂 Project Structure

```txt
Artifacts/
Notebook_Experiments/
src/
templates/
static/
app.py
requirements.txt
Dockerfile
setup.py
```

---

# ⚙️ Installation Guide

## 1️⃣ Clone Repository

```bash
git clone https://github.com/jisan23051365/student-performance-prediction.git
```

---

## 2️⃣ Create Virtual Environment

```bash
conda create -p venv python=3.10 -y
```

---

## 3️⃣ Activate Environment

```bash
conda activate venv/
```

---

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 5️⃣ Run Application

```bash
python app.py
```

---

# 🐳 Docker Support

## Build Docker Image

```bash
docker build -t student-performance-prediction .
```

## Run Docker Container

```bash
docker run -p 5000:5000 student-performance-prediction
```

---

# 📈 Key Functionalities

- Predicts student academic outcomes
- Performs automated preprocessing
- Uses CatBoost regression model
- Provides real-time predictions
- Supports scalable deployment workflow

---

# 🧠 Learning Outcomes

This project demonstrates practical understanding of:

- Machine Learning Engineering
- Data Preprocessing
- Feature Engineering
- Model Deployment
- Flask Application Development
- Docker-based Containerization
- End-to-End ML Pipeline Design

---

# 🔮 Future Improvements

- User authentication system
- Advanced analytics dashboard
- Multiple ML model comparison
- Cloud deployment integration
- Real-time monitoring system
- Improved UI/UX design

---

# 📌 Conclusion

The Student Performance Prediction System showcases the implementation of an end-to-end machine learning solution for educational analytics. It combines data science, backend development, and deployment concepts into a structured predictive application.
