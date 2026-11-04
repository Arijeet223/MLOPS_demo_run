# 🎓 Student Risk Prediction | MLOps

A hands-on MLOps learning project where I built an end-to-end machine learning pipeline to predict student academic outcomes.

The model classifies students into three categories:

* 🔴 Dropout
* 🟡 Enrolled
* 🟢 Graduate

The goal was to understand how a machine learning model moves from experimentation to deployment.

## ⚙️ What I Built & Learned

| Stage               | What I Did                                                    |
| ------------------- | ------------------------------------------------------------- |
| Data Preprocessing  | Cleaned data and prepared numerical and categorical features. |
| Model Training      | Trained a classification model using student data.            |
| Model Evaluation    | Evaluated model performance using classification metrics.     |
| Model Serialization | Saved the trained model for later use.                        |
| API Development     | Built a prediction API using FastAPI.                         |
| Containerization    | Packaged the application using Docker.                        |
| Testing             | Added automated tests to validate functionality.              |
| CI Pipeline         | Used GitHub Actions to automate testing.                      |

## 🔄 Workflow

```text
       Student Dataset
              │
              ▼
      Data Preprocessing
              │
              ▼
       Model Training
              │
              ▼
       Model Evaluation
              │
              ▼
       Saved ML Model
              │
              ▼
        FastAPI API
              │
              ▼
       Docker Container
              │
              ▼
      Automated Tests
              │
              ▼
       GitHub Actions
```

## 🛠️ Tech Stack

* **Language:** Python
* **Machine Learning:** Scikit-learn
* **API:** FastAPI
* **Containerization:** Docker
* **Testing:** Pytest
* **CI/CD:** GitHub Actions

## 📂 Project Structure

```text
MLOPS/
│
├── .github/
│   └── workflows/
│
├── app/              # API application
├── config/           # Configuration
├── data/             # Dataset
├── mlruns/           # Experiment tracking
├── models/           # Saved ML models
├── src/              # ML pipeline scripts
├── tests/            # Automated tests
│
├── Dockerfile
├── .dockerignore
├── requirements.txt
└── README.md
```

## 🎯 What I Wanted to Understand

This project helped me explore:

* How to structure an ML project beyond a Jupyter Notebook.
* How to separate preprocessing, training and prediction.
* How to serve ML models through REST APIs.
* Why Docker is useful for consistent environments.
* How automated testing fits into ML development.
* How GitHub Actions can automate parts of the development workflow.

## 🚀 Project Status

Built as part of my hands-on journey into Machine Learning Engineering and MLOps.

**Learning by building, experimenting, and improving.**
