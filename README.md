# Mobile Price Classification using SVM

## Overview
This project focuses on **multiclass classification** to predict smartphone price ranges based on technical specifications.  
The project highlights the impact of **feature scaling, kernel selection, and model complexity**.

---

## Problem
Classify smartphones into **four price categories** (`price_range`) using hardware and specification features.

---

## Dataset
- Source: Kaggle – Mobile Price Classification Dataset
- Target: `price_range`
- Features: RAM, battery power, camera specs, internal memory, screen resolution, etc.

---

## Methods
- Data validation: no missing values or duplicates
- Feature scaling using **Min-Max Normalization**
- Models evaluated:
  - SVM (Linear Kernel)
  - SVM (RBF Kernel)
- Hyperparameter tuning for `C` and `gamma`

---

## Results & Insights
- **Linear Kernel Accuracy:** 96.75%
- **RBF Kernel Accuracy:** 90.75%
- Linear kernel outperformed RBF, indicating the data is largely **linearly separable**
- More complex kernels do not always improve performance

---

## Key Takeaways
- Feature scaling is critical for SVM performance
- Kernel choice should align with data structure
- Simpler models can outperform complex ones when data is well-structured

