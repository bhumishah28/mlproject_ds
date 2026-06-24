# 🎓 Student Performance Prediction - End-to-End Machine Learning Project

##  Overview

This project is an End-to-End Machine Learning application that predicts a student's Mathematics score based on demographic and academic factors.

The project demonstrates the complete machine learning lifecycle including:

- Data Ingestion
- Data Transformation
- Feature Engineering
- Model Training
- Hyperparameter Tuning
- Model Evaluation
- Model Serialization
- Prediction Pipeline
- Flask Web Application

The objective is to build a production-ready machine learning system using software engineering best practices.

---

##  Problem Statement

Student academic performance depends on several factors such as parental education, test preparation, reading ability, and writing ability.

This project predicts a student's Mathematics score using these factors and helps analyze the relationship between various educational attributes and academic performance.

---

##  Dataset Features

### Input Features

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

### Target Variable

- Mathematics Score

---

##  Machine Learning Pipeline

The project follows a modular pipeline architecture:

1. Data Ingestion
2. Data Validation
3. Data Transformation
4. Feature Engineering
5. Model Training
6. Hyperparameter Tuning
7. Model Evaluation
8. Best Model Selection
9. Model Serialization
10. Prediction Pipeline
11. Flask Web Application

---

##  Models Evaluated

The following regression models were trained and evaluated:

- Linear Regression
- Lasso Regression
- Ridge Regression
- Decision Tree Regressor
- Random Forest Regressor
- AdaBoost Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- CatBoost Regressor

The best-performing model is automatically selected and used for prediction.

---

##  Project Structure

```text
mlproject_ds/
│
├── artifacts/
├── notebook/
├── src/
│   ├── components/
│   ├── pipeline/
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
├── app.py
├── application.py
├── requirements.txt
├── setup.py
└── README.md
```

##  Technologies Used

### Programming Language

- Python

### Machine Learning

- Scikit-Learn
- XGBoost
- CatBoost

### Data Analysis

- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn

### Web Framework

- Flask

### Version Control

- Git
- GitHub

---

##  Key Features

- Modular project architecture
- Custom exception handling
- Logging system
- Data preprocessing pipeline
- Automated model selection
- Hyperparameter tuning
- Prediction pipeline
- Flask web application
- Production-oriented code structure

---

##  Installation

### Clone Repository

```bash
git clone https://github.com/bhumishah28/mlproject_ds.git
```

### Move into Project Directory

```bash
cd mlproject_ds
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

---

##  Learning Outcomes

Through this project, I gained hands-on experience in:

- End-to-End Machine Learning Pipelines
- Feature Engineering
- Hyperparameter Tuning
- Flask Application Development
- Software Engineering for ML
- Git & GitHub Workflow
- Production-Level Project Structure

---

##  Future Improvements

- Cloud Deployment
- Docker Containerization
- CI/CD Integration
- Model Monitoring
- MLflow Experiment Tracking

---

##  Author

**Bhumi Shah**

B.Tech Computer Science & Data Science  
Dwarkadas J. Sanghvi College of Engineering

GitHub: https://github.com/bhumishah28
