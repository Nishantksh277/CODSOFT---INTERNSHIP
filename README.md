# 🎬 Movie Rating Prediction System

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Machine Learning](https://img.shields.io/badge/ML-Linear%20Regression-green.svg)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

*An intelligent system that predicts movie ratings using advanced machine learning techniques*

</div>

---

## 🎯 Project Overview

This file contains a comprehensive **Movie Rating Prediction System** developed as part of **Task 1** for the **CodSoft Data Science Internship**. The project leverages machine learning algorithms to accurately predict movie ratings based on multiple feature variables.

### 🔍 Key Features
- **Multi-feature Analysis**: Utilizes genre, director, cast, and temporal data
- **Advanced Preprocessing**: Robust data cleaning and feature engineering pipeline
- **Model Flexibility**: Supports both traditional ML and deep learning approaches
- **High Accuracy**: Achieves reliable prediction performance on unseen data

---

## 🎪 Problem Statement

> **Challenge**: Can we predict a movie's success (IMDb rating) before its release using only its metadata?

In the competitive entertainment industry, predicting movie success is crucial for:
- **Production Houses**: Investment decisions and budget allocation
- **Distributors**: Marketing strategy and theater allocation
- **Streaming Platforms**: Content acquisition and recommendation systems
- **Movie Enthusiasts**: Informed viewing choices

---

## 📊 Dataset Insights

Our comprehensive dataset encompasses **thousands of movies** with rich metadata:

| Feature | Description | Type |
|---------|-------------|------|
| **Name** | Movie title | Text |
| **Genre** | Movie category/genre | Categorical |
| **Director** | Film director | Categorical |
| **Lead Cast** | Top 3 actors (Actor 1, 2, 3) | Categorical |
| **Year** | Release year | Numerical |
| **Duration** | Runtime in minutes | Numerical |
| **Votes** | Number of IMDb votes | Numerical |
| **Rating** | IMDb rating (Target) | Numerical |

### 🧹 Data Engineering Pipeline
- **Data Validation**: Comprehensive quality checks and outlier detection
- **Type Conversion**: Systematic conversion of year, duration, and votes to numeric format
- **Missing Value Treatment**: Strategic median imputation for numerical features
- **Feature Encoding**: Label encoding for categorical variables with high cardinality
- **Scaling**: StandardScaler normalization for optimal model performance

---

## 🛠️ Technology Stack

<div align="center">

| Category | Technologies |
|----------|-------------|
| **Core Language** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| **Data Processing** | ![Pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-013243?style=flat&logo=numpy&logoColor=white) |
| **Machine Learning** | ![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) |
| **Deep Learning** | ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white) |
| **Visualization** | ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat) ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat) |

</div>

---

## 🚀 Model Architecture & Performance

### 📈 Training Pipeline
```
Raw Data → Data Cleaning → Feature Engineering → Model Training → Evaluation → Deployment
```

### 🎯 Model Performance
- **Primary Model**: Linear Regression with feature scaling
- **Alternative Model**: Neural Network (TensorFlow/Keras)
- **Validation Strategy**: Train-test split with cross-validation
- **Performance Metric**: Mean Absolute Error (MAE) and R² Score

### 🏆 Results Highlight
> **Successfully achieved a prediction accuracy of 8.0 rating** for test samples, demonstrating robust model performance across diverse movie categories.

---

## 📋 Quick Start Guide

### Prerequisites
```bash
pip install pandas numpy scikit-learn tensorflow matplotlib seaborn
```

### Usage Example
```python
# Load the trained model
from movie_predictor import MovieRatingPredictor

# Initialize predictor
predictor = MovieRatingPredictor()

# Make prediction
rating = predictor.predict(
    genre="Action",
    director="Christopher Nolan",
    actor1="Leonardo DiCaprio",
    year=2023,
    duration=148,
    votes=250000
)

print(f"Predicted Rating: {rating}")
```
---

## 📊 Project Impact

This project demonstrates proficiency in:
- **End-to-end ML Pipeline**: From raw data to production-ready model
- **Real-world Problem Solving**: Addressing industry-relevant challenges
- **Technical Excellence**: Clean code, documentation, and best practices
- **Business Understanding**: Translating data insights into actionable recommendations

---

## 🏢 Professional Context

- **Developed for**: CodSoft Data Science Internship Program
- **Objective**: Demonstrate advanced data science and machine learning capabilities  
- **Industry Application**: Entertainment, Media, and Streaming Services

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **CodSoft Team** for providing this challenging and educational project opportunity
- **Open Source Community** for the incredible tools and libraries that made this project possible

---

<div align="center">

**⭐ Star this repository if you found it helpful!**

*Built for self learning and upskilling*

</div>
