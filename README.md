# 🧠 Eigenfaces using PCA — CS 584 Homework 2

This project implements a **Principal Component Analysis (PCA)** pipeline to compute **Eigenfaces** for image compression and reconstruction. It is based on grayscale face images and evaluates the effect of dimensionality (K) on reconstruction quality.

👩‍💻 Author: Aishwarya Bhethanabotla  
🎓 Course: CS 584 — Deep Learning  
🗓️ Homework 2 — Spring 2025

---

## 🎯 Learning Objectives (Rubric-Aligned)

### ✅ Question 1: SVM Initialization and Margin Boundaries
- 🔧 **Initialization** — Vector setup, separating hyperplane
- 🔄 **Update Steps** — Manual iterative updates to optimize margin
- 📐 **Final Boundary Explanation** — Calculation and graphical representation of decision boundary

### ✅ Question 2: Eigenfaces and PCA (Image Compression)

| Subpart | Task | Status |
|---------|------|--------|
| **2.1** | Data Preprocessing | ✅ Loaded and flattened grayscale images |
| **2.1** | Computation of Eigenfaces | ✅ SVD used to extract top-K principal components |
| **2.1** | Visualization | ✅ Plotted top 10 eigenfaces |
| **2.2** | Reconstruction | ✅ Reconstructed test images using K eigenfaces |
| **2.2** | Presentation | ✅ Side-by-side: Original vs Reconstructed |
| **2.3** | Experimentation | ✅ Evaluated reconstruction error at various K values |
| **2.3** | Visualization | ✅ MSE plotted against K to show compression trade-offs |

---

## 🖼 Key Features

- 🧾 Extracts grayscale image data from a `.zip` archive
- 📉 Implements PCA via NumPy’s SVD
- 🧬 Reconstructs face images with varying compression levels
- 📊 Plots:
  - Top-K Eigenfaces
  - Reconstruction Error vs Number of Eigenfaces (K)
  - Original vs Reconstructed image comparison

---

## 📂 Structure

