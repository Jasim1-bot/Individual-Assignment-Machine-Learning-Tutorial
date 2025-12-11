# Individual-Assignment-Machine-Learning-Tutorial
### Support Vector Machines With Kernels (SVM)  
**Student ID:** 24096581  
**Course:** Advanced Machine Learning / Neural Networks  
**University of Hertfordshire**  

---

## 📌 Overview

This repository contains my full coursework submission for the Individual Machine Learning Tutorial assignment.  
The topic I selected is:

### **“Support Vector Machines With Kernels: Understanding Linear, Polynomial, and RBF Kernels Using the make\_moons Dataset.”**

The objective of the tutorial is to **teach** how kernel choice affects:
- Decision boundaries  
- Classification performance  
- Model flexibility and generalisation  

The tutorial includes a **formal academic-style PDF**, a **Jupyter Notebook**, and all **figures**, following the assignment specification.

---

## 📁 Repository Contents

| File / Folder | Description |
|---------------|-------------|
| `tutorial_svm_kernels_24096581.pdf` | **Main tutorial** (<2000 words). Includes theory, figures, methodology, results, ethics section, and references. |
| `svm_kernels.ipynb` | Fully reproducible notebook used to generate all plots and results. |
| `figures/` | PNG files for decision boundaries and accuracy comparison (linear, polynomial, RBF). |
| `requirements.txt` | Python dependencies required to run the notebook. |
| `LICENSE` | MIT License for public sharing. |
| `README.md` | About this project (this file). |

---

## 🎯 Tutorial Summary

The tutorial demonstrates:

### ✔️ What an SVM is  
A margin-based classifier.

### ✔️ Why kernels are useful  
They enable SVMs to learn **non-linear** boundaries through the **kernel trick**.

### ✔️ Kernels covered
- **Linear**  
- **Polynomial (degree=3)**  
- **RBF (Gaussian)**  

### ✔️ Dataset used  
`make_moons` (500 samples, noise=0.25).

### ✔️ Outputs produced  
- Decision boundary visualisations  
- Accuracy comparison  
- Confusion matrices  
- Discussion of model behaviour  
- Ethical considerations of ML systems  

---

## ▶️ Running the Notebook

### **1. Install dependencies**
```bash
pip install -r requirements.txt
