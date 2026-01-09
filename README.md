# Week 4 – Deep Learning (SDAIA AI Professional Bootcamp)

This repository contains **all labs, assignments, and the final project** completed during **Week 4 (Deep Learning)** of the **SDAIA AI Professional Bootcamp**.
The work focuses on building a strong practical foundation in **PyTorch**, progressing from basic neural networks to **CNNs**, **regularization**, and **robust training pipelines**.

---

## 📌 Objectives of Week 4

By the end of this week, the following learning goals were achieved:

* Understand and implement **PyTorch tensors** and tensor operations
* Build **neural networks from scratch** using `nn.Module`
* Apply **activation functions** to model non‑linear patterns
* Train regression and classification models
* Build and evaluate **image classifiers** using MNIST & EMNIST
* Design and train **Convolutional Neural Networks (CNNs)**
* Address **overfitting** using data augmentation, dropout, and batch normalization
* Follow clean, modular, and reproducible deep learning workflows

---

## 📂 Repository Structure

```text
week4-deep-learning/
├── DAY1/
│   ├── C1_M1_Lab_1_simple_nn.ipynb
│   ├── C1_M1_Lab_2_activation_functions.ipynb
│   ├── C1_M1_Lab_3_tensors.ipynb
│   ├── C1M1_Assignment.ipynb
│   ├── data.csv
│   ├── helper_utils.py
│   ├── unittests.py
│   └── unittests_utils.py
│
├── DAY2/
│   ├── C1_M2_Lab_1_mnist_classifier.ipynb
│   ├── C1M2_Assignment.ipynb
│   ├── helper_utils.py
│   ├── unittests.py
│   └── unittests_utils.py
│
├── DAY3/
│   └── (supporting notebooks & experiments)
│
├── DAY4/
│   ├── C1_M4_Lab_1_cnn_nature_classifier.ipynb
│   ├── C1M4_Assignment.ipynb
│   └── helper_utils.py
│
├── DAY5/
│   └── Final Project & advanced experiments
│
└── README.md
```

---

## Day 1 — Neural Network Foundations

> 📁 **Note:** Each day contains its own `helper_utils.py`, `unittests.py`, and supporting files inside the same folder to ensure modularity and isolated grading.

### Labs

* **Simple Neural Network**
  Built a single‑neuron regression model to predict delivery time.

* **Activation Functions**
  Demonstrated why linear models fail and how non‑linear activations solve the problem.

* **Tensors in PyTorch**
  Covered tensor creation, reshaping, indexing, broadcasting, and common shape errors.

### Assignment: Deeper Regression, Smarter Features

* Loaded real‑world CSV data
* Applied **normalization** and **feature engineering**
* Built a multi‑layer regression network
* Trained and evaluated predictions on unseen data

---

## Day 2 — Image Classification

### Lab: MNIST Classifier

* Built a full image‑classification pipeline
* Implemented:

  * Dataset loading
  * Custom `nn.Module`
  * Training loop
  * Evaluation and visualization

### Assignment: EMNIST Letter Detection

* Extended digit classification to **26 handwritten letters**
* Preprocessed image orientation and normalization
* Built a deeper neural network
* Decoded a hidden handwritten message using the trained model

---

##  Day 3 — Data Management (Lab Only)

> 📁 **Note:** Day 3 contains **one focused lab only** (no assignment). All helper files for this lab are provided inside the `DAY3` folder.

### Lab: Data Management

This lab shifts the focus from model architecture to the **data pipeline**, highlighting how data quality and loading strategies directly impact model performance.

Key concepts covered:

* Working with **real-world, unorganized datasets**
* Understanding common data issues: access, quality, and efficiency
* Implementing a custom PyTorch **`Dataset`** class
* Applying **transformations and data augmentation** on-the-fly
* Using **`DataLoader`** for efficient batching and shuffling
* Preparing data for **train / validation / test** splits
* Introducing basic **error-handling strategies** for robust pipelines

This lab reinforces that strong models fail without reliable data handling, a critical real-world deep learning skill.

---

##  Day 4 — Convolutional Neural Networks (CNNs)

### Lab: CNN for Nature Classification

* Designed a CNN architecture from scratch
* Used convolution, pooling, and fully connected layers
* Trained on a multi‑class nature dataset
* Diagnosed training and validation performance

### Assignment: Overcoming Overfitting

* Enhanced the **data pipeline** using augmentation
* Refactored CNN architecture using reusable blocks
* Integrated:

  * **Batch Normalization**
  * **Dropout**
  * **Weight Decay**
* Improved generalization and robustness

---

## Day 5 — Final Project

The final project consolidates all Week 4 concepts into a **complete deep learning system**, including:

* Clean project structure
* Robust CNN architecture
* Professional training workflow
* Performance evaluation and analysis

---

## 🛠️ Technologies & Tools

* **Language:** Python
* **Framework:** PyTorch
* **Libraries:** Torchvision, NumPy, Matplotlib
* **Environment:** Google Colab
* **Version Control:** Git & GitHub

---

##  How to Run

1. Clone the repository:

```bash
git clone https://github.com/Amnahyb4/W4-DL.git
cd W4-DL
```

2. Open notebooks using **Google Colab** (recommended) or Jupyter Notebook

3. Run notebooks **top‑to‑bottom** to ensure proper execution

---


## 👩‍💻 Author

**Amnah Albrahim**
AI Graduate | SDAIA AI Professional Bootcamp
Deep Learning • Computer Vision • PyTorch

---

## Acknowledgments

* SDAIA – Saudi Data & AI Authority
* AI Professional Bootcamp Team
* Course instructors and mentors

---

> This repository reflects hands‑on mastery of deep learning fundamentals and best practices, with a strong emphasis on clarity, correctness, and real‑world applicability.
