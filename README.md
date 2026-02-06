# 🚀 Linear Regression From Scratch (NumPy Only)

A complete implementation of **Linear Regression built from scratch using only NumPy**, without using scikit-learn or any ML libraries.

This project focuses on understanding the **mathematics and optimization behind machine learning algorithms**, including both **Gradient Descent** and **Ordinary Least Squares (Normal Equation)**.

---

## ✨ Features

- ✅ Linear Regression using Gradient Descent
- ✅ Linear Regression using OLS (Normal Equation)
- ✅ Fully vectorized NumPy implementation
- ✅ No sklearn or external ML libraries
- ✅ Clean and modular code
- ✅ sklearn-like API (`fit()`, `predict()`)
- ✅ Beginner-friendly and interview-ready

---

## 📚 Algorithms Implemented

### 🔹 Gradient Descent
An iterative optimization algorithm that updates weights step-by-step to minimize Mean Squared Error.

**Best for:**
- Large datasets
- Many features
- When matrix inversion is expensive

**Update rule:**
w = w - α * dJ/dw


---

### 🔹 Ordinary Least Squares (OLS) – Normal Equation
A closed-form mathematical solution using linear algebra.

**Formula:**
θ = (XᵀX)⁻¹Xᵀy
