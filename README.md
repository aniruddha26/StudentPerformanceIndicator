# 📊 Student Performance Indicator (End-to-End ML Project)

## 🚀 Overview
This project is a **production-grade Machine Learning system** that predicts student math performance based on demographic and academic features.

It demonstrates a **complete ML lifecycle**:
- Data ingestion → preprocessing → model training → evaluation → deployment

Built with a strong focus on **clean architecture, modularity, and real-world ML practices**.

---

## 🎯 Problem Statement
Educational institutions often need to identify students who may require additional support.

This project predicts **math scores** using:
- Demographics
- Academic history
- Behavioral indicators

---

## 🧠 Key Highlights
- ✅ End-to-End ML Pipeline (Train + Predict)
- ✅ Modular Production Code Structure
- ✅ Custom Exception Handling & Logging
- ✅ Hyperparameter Tuning
- ✅ Model Evaluation & Selection
- ✅ Flask Web App Deployment
- ✅ Reusable Pipelines (Train & Inference)

---

## 🏗️ Architecture

```
📁 StudentPerformanceIndicator
│
├── artifacts/              # Serialized models & preprocessors
├── notebook/               # EDA & experimentation
├── src/
│   ├── components/         # Data ingestion, transformation, model trainer
│   ├── pipeline/           # Training & prediction pipelines
│   ├── exception.py        # Custom exception handling
│   ├── logger.py           # Logging module
│   ├── utils.py            # Utility functions
│
├── templates/              # HTML UI
├── app.py                  # Flask app
├── requirements.txt
├── setup.py
└── README.md
```

---

## ⚙️ ML Pipeline

### 1. Data Ingestion
- Load dataset
- Train-test split
- Store artifacts

### 2. Data Transformation
- Missing value handling
- Encoding categorical variables
- Feature scaling
- Pipeline saved using pickle

### 3. Model Training
- Models trained:
  - Linear Regression
  - Random Forest
  - Decision Tree
  - Gradient Boosting
- Hyperparameter tuning
- Best model selection

### 4. Prediction Pipeline
- Accepts user input
- Applies preprocessing
- Generates predictions

---

## 📊 Dataset
- **Source:** Kaggle - Students Performance in Exams
- Target Variable: `math_score`

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Flask
- HTML/CSS

---

## ▶️ Run Locally

```bash
git clone https://github.com/aniruddha26/StudentPerformanceIndicator.git
cd StudentPerformanceIndicator

conda create -p venv python=3.8 -y
conda activate venv/

pip install -r requirements.txt
python app.py
```

Open:
```
http://127.0.0.1:5000/
```

---

## 📈 Evaluation Metrics
- MAE
- RMSE
- R² Score

---

## 💡 Why This Project Stands Out
- Production-style ML architecture
- Clean separation of concerns
- Reusable pipelines
- Real-world deployment approach

---

## 🔮 Future Improvements
- Dockerization
- Cloud Deployment (AWS/GCP)
- CI/CD Integration
- Experiment Tracking (MLflow)

---

## 🤝 Contributing
Pull requests are welcome.

---

## 📜 License
MIT License

---

## 👨‍💻 Author
**Aniruddha Alkari**

---

## ⭐ Support
If you found this useful, consider giving it a star ⭐
