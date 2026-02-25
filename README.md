# K-Fold Cross Validation From Scratch

This repository implements K-Fold Cross Validation completely from scratch using NumPy.

---

## What is K-Fold Cross Validation?

Instead of splitting data once into train/test, K-Fold:

1. Splits data into K equal parts
2. Trains on K-1 folds
3. Tests on the remaining fold
4. Repeats K times
5. Averages the error

This reduces variance and gives a more reliable performance estimate.

---

## Mathematical Insight

Cross Validation Score:

CV = (1/K) * Σ Error_i

Where Error_i is the validation error on fold i.

---

## What This Repo Includes

- Manual K-Fold implementation
- Fold error visualization
- Data split visualization
- Comparison with sklearn implementation
- Average cross-validation error comparison

---

## Key Learning

- Why single train/test split is unstable
- How K-Fold reduces variance
- How performance stabilizes across folds
- Why cross-validation is critical in ML pipelines

---

## Tech Stack

- Python
- NumPy
- Matplotlib
- scikit-learn
