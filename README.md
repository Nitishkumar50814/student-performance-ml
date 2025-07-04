<h1 align="center">📘 Exam Marks Prediction using Study Hours</h1>

<p align="center">
  <img src="https://img.shields.io/badge/ML-Type-Linear_Regression-blue" />
  <img src="https://img.shields.io/badge/Level-Beginner-green" />
  <img src="https://img.shields.io/badge/Language-Python-yellow" />
</p>

---

## 📌 Project Overview

This is a beginner-friendly Machine Learning project to predict student **exam marks** based on their **study hours** using **Linear Regression**.

It demonstrates the fundamental concept of supervised learning — ideal for those starting out in data science and ML.

---

## 🎯 Objective

> “Can we accurately predict a student's score based on the number of hours they studied?”

This project explores the linear relationship between hours studied and marks obtained.

---

## 📊 Dataset Description

A small dataset with two features:

| Feature         | Description                      |
|-----------------|----------------------------------|
| Hours           | Number of hours a student studied |
| Marks (Scores)  | Marks obtained in the exam        |

✅ The dataset is clean, numeric, and ideal for linear regression modeling.

---

## 🧠 ML Workflow

- Data Import and Visualization
- Data Preprocessing
- Splitting into Training and Testing
- Model Training with Linear Regression
- Prediction and Evaluation using:
  - 📈 Mean Absolute Error
  - 📉 R² Score
  - 🔍 Scatterplot with Regression Line

---

## 📉 Visual Output

<p align="center">
  <img src="images/study_hours_vs_marks.png" width="450" alt="Study Hours vs Marks Graph">
</p>

---

## 📦 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score, mean_absolute_error
