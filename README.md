# Gradient Descent Optimization on Student Performance

This project implements and compares four gradient descent optimization techniques—**Batch Gradient Descent**, **Stochastic Gradient Descent**, **Mini-Batch Gradient Descent**, and **Momentum Gradient Descent**—to predict student performance based on various academic and lifestyle features such as study hours, previous scores, sleep duration, and more.

## 📊 Overview

The goal is to understand how different gradient descent methods perform in optimizing a linear regression model and how they converge over time. The model is trained to predict the `Performance Index` of students using the following features:

- Hours Studied
- Previous Scores
- Sleep Hours
- Sample Question Papers Practiced

## 📁 Dataset

The dataset used is [`Student Performance`](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression), which contains 10,000 rows and the following columns:

- `Hours Studied`
- `Previous Scores`
- `Extracurricular Activities`
- `Sleep Hours`
- `Sample Question Papers Practiced`
- `Performance Index` (Target)

## ⚙️ Techniques Implemented

- **Batch Gradient Descent (BGD)**
- **Stochastic Gradient Descent (SGD)**
- **Mini-Batch Gradient Descent (MBGD)**
- **Momentum Gradient Descent (MGD)**

Each method is implemented from scratch using NumPy, and performance is evaluated based on cost function convergence and RMSE (Root Mean Squared Error) on the test set.

## 📈 Results

The project includes visualizations of:

- Feature distributions and pairwise relationships
- Correlation heatmap
- Cost convergence for each gradient descent method

### 🔍 Final Test RMSE:
- **Batch GD**: 2.0735  
- **Stochastic GD**: 2.0777  
- **Mini-Batch GD**: 2.0471  
- **Momentum GD**: 2.0451  

## 🧰 Libraries Used

- `NumPy`
- `Pandas`
- `Matplotlib`
- `Seaborn`
- `Scikit-learn`

## 📌 Key Takeaways

- Gradient Descent is a fundamental concept in optimization and machine learning.
- Different methods have trade-offs in speed, accuracy, and convergence stability.
- Momentum and Mini-Batch GD showed slightly better performance in this context.
