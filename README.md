**Course:** Computer Technology  
**Registration Number:** SCT212-0476/2023  
**Name:** Samuel Kuria
**Year:** 3
**UNIT:** ICS2308 Aritficial Intelligence

# ASSIGNMENT 2 & CAT

# Machine Learning: Regression & Optimization Lab

This repository contains implementations of fundamental Machine Learning concepts and optimization algorithms, transitioning from basic regression models to advanced adaptive optimizers.

## 📌 Overview
The project explores how models learn by minimizing loss functions using various gradient-based methods. We started with simple linear relationships and moved toward complex optimization landscapes.

## 🚀 Implemented Features

### 1. Regression Models
* **Linear Regression:** Implemented the standard $y = \phi_0 + \phi_1 x$ model.
* **Logistic Regression:** Developed models for classification using the sigmoid activation function.
* **Loss Functions:** Built Sum of Squared Errors (SSE) for regression and cross-entropy for classification.

### 2. Optimization Algorithms
I implemented and compared several ways to update model parameters ($\phi$):
* **Gradient Descent:** Both fixed learning rate and line-search methods.
* **Stochastic Gradient Descent (SGD):** Training on mini-batches to improve computational efficiency.
* **Momentum & Nesterov Accelerated Gradient:** Using velocity to smooth out updates and avoid local minima.
* **Normalized Gradients:** Scaling updates to handle differing parameter magnitudes.
* **Adam Optimizer:** The final implementation combining adaptive learning rates with momentum for robust convergence.

##  How to Run
1. Open the `.ipynb` notebooks in Jupyter or Google Colab.
2. Ensure `numpy` and `matplotlib` are installed.
3. Run the cells sequentially to visualize the loss surface trajectories and model fits.

---
