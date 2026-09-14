# Machine-Learning-Course-at-AUT

# Machine Learning Course — Amirkabir University of Technology (AUT)

[![Course](https://img.shields.io/badge/Course-ML--501-blue.svg)](https://github.com/your-username/ml-course-aut)
[![Institution](https://img.shields.io/badge/Institution-AUT-red.svg)](https://aut.ac.ir)
[![Semester](https://img.shields.io/badge/Semester-Fall%202026-green.svg)]()
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-EE4C2C.svg)](https://pytorch.org/)

> **Course:** Machine Learning (ML-501)
> **Instructor:** Mostafa Abbaszadeh
> **Institution:** Amirkabir University of Technology (AUT)
> **Semester:** Fall 2026
> **Credits:** 3 (2 lecture + 1 lab)

---

## 📖 Table of Contents

- [About the Course](#-about-the-course)
- [Course Objectives](#-course-objectives)
- [Prerequisites](#-prerequisites)
- [Repository Structure](#-repository-structure)
- [Course Schedule](#-course-schedule)
- [Slide Decks](#-slide-decks)
- [Labs and Assignments](#-labs-and-assignments)
- [Course Project](#-course-project)
- [Setup and Installation](#-setup-and-installation)
- [Tools and Libraries](#-tools-and-libraries)
- [Textbooks and References](#-textbooks-and-references)
- [Assessment and Grading](#-assessment-and-grading)
- [How to Use This Repository](#-how-to-use-this-repository)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎯 About the Course

This course provides a comprehensive introduction to **machine learning**, spanning:

- **Mathematical foundations** — linear algebra, optimization, probability estimation
- **Classical machine learning** — regression, classification, kNN, decision trees, clustering, dimensionality reduction
- **Modern deep learning** — artificial neural networks, autoencoders, CNNs, RNNs
- **Advanced research topics** — explainable AI, active learning, physics-informed neural networks

The course emphasizes both **theoretical understanding** and **hands-on implementation** using Python, NumPy, PyTorch, and modern ML libraries. Students complete a semester-long project applying course concepts to a real dataset.

---

## 🎓 Course Objectives

By the end of this course, students will be able to:

1. **Formulate** machine learning problems using linear algebra, optimization, and probability.
2. **Implement** core ML algorithms (regression, classification, kNN, decision trees, k-means, PCA, neural networks) from scratch.
3. **Estimate** probabilistic models using MLE, MAP, and Bayesian data fusion.
4. **Build** deep learning models (ANN, autoencoder, CNN, RNN) using PyTorch/TensorFlow.
5. **Explain** model predictions using XAI techniques (SHAP, LIME, Grad-CAM, CAM).
6. **Design** active learning pipelines and physics-informed neural networks.
7. **Communicate** technical results through written reports and oral presentations.

---

## 📋 Prerequisites

| Subject | Required Knowledge |
|---|---|
| **Linear Algebra** | Matrix operations, eigenvalues, SVD |
| **Calculus** | Partial derivatives, chain rule, gradients |
| **Probability & Statistics** | Distributions, Bayes' theorem, MLE, MAP |
| **Programming** | Python (NumPy, Matplotlib); basic PyTorch helpful |

---

## 📂 Repository Structure


---

## 📅 Course Schedule

| Week | Topic | Module |
|:---:|---|---|
| 1 | Linear Algebra I & II | M1 |
| 2 | Eigenvalues, Eigenvectors, SVD | M1 |
| 3 | Optimization Basics & Gradient Descent | M2 |
| 4 | Convex Problems in Practice | M2 |
| 5 | Datasets & Data Preprocessing | M3 |
| 6 | Probability Estimation & Data Fusion (MLE, MAP) | M3 |
| 7 | Linear & $L_1$/$L_2$ Regression | M4 |
| 8 | Nonlinear Regression & Regularization | M4 |
| 9 | Perceptron & SVM | M5 |
| 10 | Logistic Regression & Multiclass | M5 |
| **11** | **Midterm Exam** | — |
| 12 | kNN & Decision Trees | M6 |
| 13 | K-Means Clustering | M7 |
| 14 | PCA, SVD, POD, FDA/LDA | M8 |
| 15 | ANN: Perceptron to MLP | M9 |
| 16 | Autoencoders | M10 |
| 17 | CNN: Convolution & Architecture | M11 |
| 18 | CNN in Practice & XAI Fundamentals | M11–M12 |
| 19 | XAI Methods & Grad-CAM / CAM | M12 |
| 20 | RNN: Sequence Modeling & Training | M13 |
| 21 | RNN in Practice (LSTM, GRU) | M13 |
| 22 | Active Learning Basics & Sampling | M14 |
| 23 | Bayesian Optimization & PINN Fundamentals | M14–M15 |
| 24 | PINN Architecture & Applications | M15 |
| 25 | MLE & MAP / Kalman Filter | M16 |
| 26 | Probabilistic ML & Project Presentations | M16 |
| **27** | **Final Exam** | — |

---

## 📚 Slide Decks

All lecture slides are available in the [`slides/`](slides/) directory. Each deck corresponds to one or more modules in the course.

| # | Slide Deck | Module | Description |
|:---:|---|---|---|
| 01 | Linear Algebra | M1 | Systems of equations, matrices as linear maps, eigenvalues, SVD |
| 02 | Optimization | M2 | Convexity, gradient descent, CVXPY, LP & QP |
| 03 | Regression | M4 | Linear, $L_1$/$L_2$, polynomial, ridge, LASSO |
| 04 | Classification | M5 | Perceptron, SVM, logistic regression, multiclass |
| 05 | kNN & Decision Trees | M6 | KNN regression/classification, entropy, information gain, random forest |
| 06 | Clustering | M7 | K-means, elbow method, limitations |
| 07 | Dimensionality Reduction | M8 | PCA, SVD, POD, Eigenfaces, FDA/LDA |
| 08 | Artificial Neural Networks | M9 | Perceptron to MLP, backprop, activation functions, TensorFlow |
| 09 | Autoencoders | M10 | Encoder–decoder, latent space, VAE, generative models |
| 10 | Convolutional Neural Networks | M11 | 1D/2D convolution, pooling, CNN architectures, transfer learning |
| 11 | Explainable AI | M12 | SHAP, LIME, saliency maps, Grad-CAM, CAM |
| 12 | Recurrent Neural Networks | M13 | RNN, BPTT, LSTM, GRU, seq2seq, attention |
| 13 | Active Learning | M14 | Uncertainty sampling, QBC, core-set, Bayesian optimization |
| 15 | Physics-Informed Neural Networks | M15 | PINN formulation, collocation points, inverse problems |
| 23 | Parameter Estimation | M16 | MLE, MAP, Kalman filter, Bayesian data fusion |
| — | Dataset | M3 | What is a dataset, preprocessing, feature engineering |
| — | Introduction to ML | Overview | Course overview, ML taxonomy |

---

## 🧪 Labs and Assignments

### Weekly Labs
Each lab provides hands-on coding practice for the corresponding module. Labs are in the [`labs/`](labs/) directory and include a Jupyter notebook plus a short report template.

### Homework Assignments
Six homework assignments (theory + coding) are posted in the [`assignments/`](assignments/) directory. Each assignment is due **one week** after it is posted.

| # | Topic | Due Week |
|:---:|---|---|
| HW1 | Linear Algebra + Optimization | 4 |
| HW2 | Regression + Classification | 8 |
| HW3 | kNN + Decision Trees + Clustering | 13 |
| HW4 | Dim. Reduction + ANN + Autoencoder | 17 |
| HW5 | CNN + XAI + RNN | 21 |
| HW6 | Active Learning + PINN + Parameter Estimation | 26 |

---

## 🚀 Course Project

Students work in teams of **2–3** on a semester-long project. Suggested tracks:

- Regression / Classification on a real dataset
- Clustering or dimensionality reduction for exploratory analysis
- ANN / Autoencoder / CNN / RNN for a domain-specific task
- XAI analysis of a trained model
- Active learning pipeline for a labeling-constrained problem
- PINN for a physics/engineering problem
- Parameter estimation (MLE/MAP/Kalman) for a sensor-fusion task

### Deliverables

| Deliverable | Due Week | Length |
|---|:---:|:---:|
| Proposal | 6 | 2 pages |
| Milestone Report | 15 | 4 pages |
| Final Report | 26 | 8 pages (NeurIPS format) |
| Presentation | 26 | 10 min + 5 min Q&A |

Templates are in the [`project/`](project/) directory.

---

## ⚙️ Setup and Installation

### Option 1: Using Conda (Recommended)

```bash
# Clone the repository
git clone https://github.com/your-username/ml-course-aut.git
cd ml-course-aut

# Create the environment
conda env create -f environment.yml

# Activate
conda activate ml-course-aut

# Launch Jupyter
jupyter notebook
