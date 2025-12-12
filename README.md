# assihnment
# Breast Cancer Classification using KNN and K-Means

## Project Overview
This project classifies breast cancer diagnoses into **Malignant (M)** and **Benign (B)** using:

1. **K-Nearest Neighbors (KNN)** for supervised classification.
2. **K-Means clustering** for unsupervised grouping.

---

## Dataset
- File: `Dataset.csv`
- Preprocessing steps:
  1. Dropped `id` and `Unnamed: 32`.
  2. Encoded `diagnosis`: `M → 1`, `B → 0`.
  3. Features scaled with **Min-Max normalization**.
  4. Split: 80% training / 20% testing.

---

## Methodology

### K-Means Clustering
- Applied `k=2` clusters.
- Observed distribution of benign and malignant instances.

### K-Nearest Neighbors (KNN)
- `k=5` neighbors.
- Evaluation metrics: Accuracy, Precision, Recall, F1-score.
- Confusion matrix visualizes classification performance.

---

## Results
After running the notebook, you will see:

- **Accuracy:** `0.XXXX`  
- **Precision:** `0.XXXX`  
- **Recall:** `0.XXXX`  
- **F1-score:** `0.XXXX`  

> Replace `0.XXXX` with actual results.

Confusion matrix shows the distribution of predicted vs actual labels.

---

## How to Run
1. Open `Breast_Cancer_Classification.ipynb` in **Google Colab**.
2. Upload `Dataset.csv`.
3. Run all cells.
4. Evaluation metrics and confusion matrix will be displayed.

---

## Folder Structure
