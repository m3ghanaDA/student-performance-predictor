# 🎓 End-to-End Data Science Project: Student Performance Prediction

## 📌 Project Overview

This project demonstrates the complete implementation of an End-to-End Data Science and Machine Learning pipeline using Python, following industry-standard MLOps practices.

The objective is to predict student performance based on demographic, educational, and behavioral factors. The project covers every stage of the machine learning lifecycle, including data ingestion, data transformation, exploratory data analysis (EDA), model training, evaluation, packaging, and deployment.

---

## 🚀 Key Features

- End-to-End Machine Learning Pipeline
- Modular Project Structure
- Object-Oriented Programming (OOP)
- Data Ingestion Pipeline
- Data Transformation Pipeline
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Model Training & Evaluation
- Exception Handling & Logging
- Python Packaging with `setup.py`
- Git & GitHub Integration
- Virtual Environment Management
- Deployment-Ready Architecture

---

## 🏗️ Project Architecture

```text
project/
│
├── artifacts/
│
├── notebooks/
│   ├── EDA.ipynb
│   └── Model_Training.ipynb
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/
│   │   ├── train_pipeline.py
│   │   └── predict_pipeline.py
│   │
│   ├── logger.py
│   ├── exception.py
│   └── utils.py
│
├── requirements.txt
├── setup.py
├── README.md
└── .gitignore
```

---

## 📊 Dataset Information

The project uses the **Student Performance Indicator Dataset**.

### Features

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

### Target Variable

- Math Score

---

## 🔍 Exploratory Data Analysis (EDA)

The EDA process includes:

- Data Quality Checks
- Missing Value Analysis
- Duplicate Detection
- Statistical Summary
- Feature Distribution Analysis
- Correlation Analysis
- Categorical Feature Analysis
- Performance Comparison Visualizations
- Feature Engineering

### Engineered Features

- Total Score
- Average Score

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

### Numerical Features

- StandardScaler

### Categorical Features

- OneHotEncoder

### Pipeline Components

- ColumnTransformer
- Pipeline API
- Feature Scaling
- Encoding

---

## 🤖 Machine Learning Models

The following regression models are trained and evaluated:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- AdaBoost Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- CatBoost Regressor

---

## 📈 Evaluation Metrics

Models are evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

The best-performing model is selected based on evaluation performance.

---

## 📝 Logging & Exception Handling

The project implements:

### Custom Logging

- Timestamped Log Files
- Error Tracking
- Execution Monitoring

### Custom Exception Handling

- Detailed Error Messages
- File Name Tracking
- Line Number Tracking
- Improved Debugging

---

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/m3ghanaDA/student-performance-prediction.git

cd student-performance-prediction
```

### Create Virtual Environment

```bash
conda create -p venv python=3.8 -y

conda activate venv/
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Training Pipeline

```bash
python src/pipeline/train_pipeline.py
```

---

## 🔮 Running Predictions

```bash
python src/pipeline/predict_pipeline.py
```

---

## 🛠️ Technologies Used

### Programming

- Python

### Data Analysis

- NumPy
- Pandas

### Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-Learn
- XGBoost
- CatBoost

### Development Tools

- Git
- GitHub
- VS Code
- Anaconda

### MLOps Concepts

- Modular Pipelines
- Packaging
- Logging
- Exception Handling
- Deployment-Ready Structure

---

## 📚 Learning Outcomes

This project demonstrates:

- End-to-End Data Science Workflow
- Machine Learning Pipeline Development
- Production-Level Project Structure
- Feature Engineering Techniques
- Model Selection & Evaluation
- Software Engineering Best Practices
- MLOps Fundamentals

---

## 📸 Project Workflow

```text
Data Collection
       ↓
Data Ingestion
       ↓
Data Validation
       ↓
EDA
       ↓
Feature Engineering
       ↓
Data Transformation
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Model Selection
       ↓
Prediction Pipeline
       ↓
Deployment
```

---


## 📄 License

This project is intended for educational and learning purposes.

---

## 👤 Author

**Meghana D A**

- MSc Data Science (Distinction)
- Data Scientist | Machine Learning Enthusiast
- Python | SQL | Machine Learning | Deep Learning | MLOps

⭐ If you found this project useful, consider giving it a star on GitHub.
