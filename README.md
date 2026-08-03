# Mathematics for Data Science Project

> A complete end-to-end Data Science project developed as part of the **Mathematics for Data Science (3-0-0-6)** course.

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20App-green)
![License](https://img.shields.io/badge/License-MIT-orange)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

---

## 📖 Project Overview

This project demonstrates the complete workflow of a data science application:

- Creation of a custom dataset
- Data preprocessing and cleaning
- Mathematical analysis of the data
- Statistical visualization
- Machine Learning model implementation
- Interactive web application for predictions and analysis

The project emphasizes the mathematical foundations behind modern Machine Learning algorithms rather than treating them as black boxes.

---

## 🎯 Objectives

- Design and collect an original dataset.
- Apply concepts from Linear Algebra, Calculus and Optimization.
- Implement Machine Learning algorithms from scratch (where possible).
- Compare mathematical optimization techniques.
- Visualize and interpret results.
- Deploy everything through an interactive website.

---

## 📚 Course Concepts Covered

The project is designed around the topics taught in the course:

- Linear Algebra
  - Vector Spaces
  - Matrix Operations
  - Rank
  - Matrix Decomposition
  - Norms

- Calculus
  - Derivatives
  - Partial Derivatives
  - Gradients
  - Chain Rule

- Optimization
  - Convex Functions
  - Gradient Descent
  - Stochastic Gradient Descent
  - Momentum
  - Adam Optimizer

- Statistics
  - Probability
  - Mean
  - Variance
  - Correlation
  - Covariance

- Machine Learning
  - Linear Regression
  - Logistic Regression
  - Model Evaluation

---

## 📊 Dataset

The dataset used in this project will be **created by our team**.

### Information

| Property | Description |
|----------|-------------|
| Source | Self-generated |
| Samples | TBD |
| Features | TBD |
| Target Variable | TBD |
| Missing Values | TBD |
| Format | TBD |

Example:

| Feature 1 | Feature 2 | Feature 3 | Target |
|-----------|-----------|-----------|--------|
| ... | ... | ... | ... |

---

## 🧮 Mathematical Foundations

The algorithms implemented in this project rely on several mathematical concepts:

# Mathematical Background

## Linear Regression

Prediction

```text
ŷ = Xw + b
```

Loss Function (Mean Squared Error)

```text
J(w) = (1 / 2m) Σ (yi − ŷi)²
```

Gradient

```text
∇J(w) = (1 / m) Xᵀ(Xw − y)
```

---

## Logistic Regression

Sigmoid Function

```text
σ(z) = 1 / (1 + e^(−z))
```

Binary Cross Entropy

```text
L = −y log(ŷ) − (1 − y) log(1 − ŷ)
```

---

### Optimization

Algorithms implemented include:

- Batch Gradient Descent
- Mini-batch Gradient Descent
- Stochastic Gradient Descent
- Adam Optimizer
- RMSProp *(if implemented)*

---

## 📈 Exploratory Data Analysis

The website includes:

- Distribution plots
- Correlation heatmaps
- Pair plots
- Feature importance
- Missing value analysis
- Summary statistics

---

## 🧠 Machine Learning Pipeline

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Train/Test Split
      │
      ▼
Model Training
      │
      ▼
Optimization
      │
      ▼
Evaluation
      │
      ▼
Web Deployment
```

---

## 🖥️ Website Features

- Interactive Dashboard
- Dataset Explorer
- Data Visualizations
- Model Training
- Prediction Interface
- Performance Metrics
- Download Results

---

## 📂 Project Structure

```
 To Be Decided

```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/cyberaionics/CS407T_Submission.git
```

Move into the project

```bash
cd CS407T_Submission
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate it

### Linux

```bash
source .venv/bin/activate
```

### Windows

```bash
.venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## 📊 Evaluation Metrics

Depending on the model used:

Regression

- MAE
- MSE
- RMSE
- R² Score

Classification

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Flask / Streamlit
- HTML
- CSS
- JavaScript

---

## 📅 Development Roadmap

- [ ] Dataset Collection
- [ ] Data Cleaning
- [ ] Exploratory Data Analysis
- [ ] Feature Engineering
- [ ] Mathematical Modeling
- [ ] Machine Learning
- [ ] Model Evaluation
- [ ] Website Development
- [ ] Final Deployment

---

## 👨‍💻 Team
 _______________________________________
|        Name       |       Role        |
|-------------------|-------------------|
| Ankush Tarafdar   |                   |
|-------------------|-------------------|
| Manish Patil      |                   |
|-------------------|-------------------|
| Placeholder       |                   |
|-------------------|-------------------|
| Placeholder       |                   |
|-------------------|-------------------|
| Placeholder       |                   |
|___________________|___________________|
---

## 📚 References

- Christopher M. Bishop — *Pattern Recognition and Machine Learning*
- Kevin P. Murphy — *Machine Learning: A Probabilistic Perspective*
- Boyd & Vandenberghe — *Convex Optimization*
- Scikit-Learn Documentation
- NumPy Documentation

---

## 📜 License

This project is developed for academic purposes as part of the **Mathematics for Data Science** course at IIT Dharwad.

