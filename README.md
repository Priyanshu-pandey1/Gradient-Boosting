# ⚡ Gradient Boosting: Advanced Ensemble Analysis

This repository contains a dual implementation of **Gradient Boosting** for both Regression and Classification tasks. This project demonstrates how sequentially building trees to correct the errors of previous ones leads to highly accurate and robust predictive models.

## 🚀 Project Overview

Gradient Boosting is a powerful ensemble technique that optimizes a differentiable loss function. This implementation explores hyperparameter tuning—such as learning rates and subsampling—to achieve state-of-the-art results on the provided datasets.

### Key Highlights:
* **Gradient Boosting Regressor:** Optimized using a controlled `learning_rate` and `subsample` to prevent overfitting while maximizing variance capture.
* **Gradient Boosting Classifier:** Implemented a robust classification model with 150 estimators to achieve high categorical precision.
* **Hyperparameter Strategy:** Focused on the trade-off between `n_estimators` and `learning_rate` to find the "sweet spot" for model convergence.

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy
* **Algorithms:** Gradient Boosting Regressor (GBR), Gradient Boosting Classifier (GBC)

---

## 📊 Model Performance



### 1. Gradient Boosting Regressor (GBR)
* **Parameters:** `n_estimators=200`, `learning_rate=0.05`, `max_depth=3`, `subsample=0.8`
* **R² Score:** **0.9187** (91.87%)

### 2. Gradient Boosting Classifier (GBC)
* **Parameters:** `n_estimators=150`, `learning_rate=0.1`, `max_depth=3`
* **Accuracy:** **91.33%**

---
1. Clone the repository:
   ```bash
   git clone [https://github.com/Priyanshu-pandey1/Gradient-Boosting.git](https://github.com/Priyanshu-pandey1/Gradient-Boosting.git)
