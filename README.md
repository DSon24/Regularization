# Regularization Techniques – COMP 3800 (Agentic AI)

**Instructor:** Professor Armen Pischdotchian | **Author:** Son Nguyen

---

## Overview

A short presentation and hands-on lab to help students understand **overfitting** and how to fight it using L1 and L2 regularization.

- **`Final_Presentation.pptx`** — Covers what overfitting is, and how Lasso (L1) and Ridge (L2) regularization work, with a side-by-side MSE comparison.
- **`Regularization_techniques.ipynb`** — A ~30 min lab from **IBM Cognitive Class AI** where students implement L1 and L2 regularization in Keras on real-world data.

---

## Results

| Model  | MSE    |
|--------|--------|
| Normal | 1.9096 |
| Ridge  | 1.6803 |
| Lasso  | 1.8229 |

---

## Setup

```bash
pip install tensorflow numpy matplotlib scikit-learn
```

Open `Regularization_techniques.ipynb` in Jupyter and run top-to-bottom.