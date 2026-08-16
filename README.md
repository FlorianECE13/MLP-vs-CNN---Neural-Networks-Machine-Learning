# Empirical Benchmark: MLP vs. CNN on CIFAR-10

A comparative study evaluating Multi-Layer Perceptrons (MLP) against Convolutional Neural Networks (CNN) on the CIFAR-10 dataset using TensorFlow/Keras.

---

## 📌 Project Overview
This project benchmarks the performance, training dynamics, and generalization capabilities of dense vs. convolutional architectures on image classification tasks:
* **MLP Baseline & Tuned Variants**: Analysis of depth, width, and parameter scaling limitations.
* **CNN Architectures**: Feature extraction, spatial hierarchies, and receptive fields.
* **Regularization & Optimization**: Impact of Dropout, Batch Normalization, Data Augmentation, and weight decay on overfitting.

---

## 📁 Repository Structure
* `1st_project.ipynb` — Complete Jupyter Notebook containing data preprocessing, model implementations, training loops, and evaluation plots.
* `1stproject_report.pdf` — Comprehensive academic report in Greek detailing experimental setup, hyperparameter tables, and analytical findings.
* `1stproject_report.tex` — LaTeX source files and build assets (`latex_pictures/`).

---

## 🛠️ Tech Stack & Requirements
* Python 3.x
* TensorFlow / Keras
* NumPy / Matplotlib / Scikit-Learn

```bash
pip install tensorflow numpy matplotlib scikit-learn jupyter
