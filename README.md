# Support Vector Machines for Binary Classification

This repository contains a Jupyter Notebook demonstrating the theory and practical implementation of **Support Vector Machines (SVMs)** for binary classification, with an application to **banknote authentication**.

The notebook combines **mathematical formulation**, **optimization-based learning**, and **real-world data analysis**.

> ⚠️ **Language note**  
> Some inline explanations and comments inside the notebook are written in **Persian (Farsi)**.  
> Nevertheless, all **mathematical formulations, code structure, variable names, figures, and results** follow standard machine learning conventions and are fully understandable for non-Persian readers.

## File
- `practical1_svm_403201483.ipynb` — main notebook

## Overview
Support Vector Machines are supervised learning models that perform classification by solving a constrained optimization problem.  
This notebook presents a **from-the-ground-up view** of SVMs, emphasizing the connection between geometry, optimization, and classification performance.

The notebook walks through:
- Binary classification fundamentals
- Linear SVMs using **primal and dual formulations**
- Quadratic optimization for margin maximization
- Kernel methods for nonlinear decision boundaries
- Evaluation using precision and sensitivity metrics

## Topics Covered
- Binary classification concepts (TP, FP, FN, TN)
- Precision and sensitivity trade-offs
- Linear SVM formulation
- Primal vs. dual optimization problems
- Quadratic programming interpretation
- Kernelized SVMs for nonlinear classification
- Real-world application: **Counterfeit banknote detection**

## Dataset
The notebook uses the **Banknote Authentication dataset**, which includes statistical features extracted from wavelet-transformed images of banknotes:
- Variance
- Skewness
- Kurtosis
- Entropy

Target variable:
- Genuine vs. counterfeit banknotes

Dataset source:
https://archive.ics.uci.edu/ml/datasets/banknote+authentication

## Tools & Libraries
- Python 3.9+
- NumPy
- Matplotlib
- (Optional) Scikit-learn
- Jupyter Notebook

Install dependencies:
```bash
pip install numpy matplotlib scikit-learn jupyter
