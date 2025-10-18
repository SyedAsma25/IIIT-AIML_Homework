# 📘 IIIT Homework Repository 

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Google Colab](https://img.shields.io/badge/Colab-Open_in_Colab-orange?logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org/)

Welcome to my **IIIT Homework Repository**, where I’ve uploaded key Google Colab notebooks from my AI/ML coursework.  
These notebooks combine **concept explanations**, **Python code**, and **visual learning** to connect mathematical foundations with real-world AI applications.

---

## 📂 Repository Overview

This repository currently contains **five main modules**:

### 1. AIML_Course_Probability_Primer.ipynb
- Covers **core concepts in probability theory** used in AI/ML.
- Includes worked-out examples using **NumPy, SciPy, Matplotlib, and Pandas**.
- Explains key **definitions, theorems, and visualizations** for deeper understanding.

### 2. STP_Linear_Algebra.ipynb
- Focuses on **essential linear algebra topics** such as:
  - Matrices and matrix operations  
  - `numpy.array`, `multi_dot()`, and matrix multiplication examples  
- Each section includes **code snippets**, **concept notes**, and **reference video links**.
- Serves as both a **learning resource** and a **quick revision guide**.

### 3. Module_01_Lab_01_Feature_Extraction.ipynb
- Introduces the concept of **feature extraction from data**, the foundation of all AI/ML models.
- Demonstrates how to understand and visualize **features in images and text data**.
- Covers examples like:
  - Extracting numerical features (e.g., pixel intensities, edges, histograms)
  - Analyzing written numbers and how features distinguish classes (e.g., digits 0 vs 1)
  - Building visualizations with **Plotly** and **Matplotlib**
- Encourages exploration and experimentation with real data.

### 4. Module_01_Lab_02_KNN_Classifier.ipynb
- Implements **Nearest Neighbour (1-NN and 3-NN) classifiers** on datasets like **California Housing**.
- Demonstrates effects of **train/validation splits**, **dataset size**, and **random classifiers** on accuracy.
- Includes **visualizations** of accuracy vs. training set size.
- Helps understand **model evaluation, validation strategies, and overfitting**.

### 5. Module_01_Lab_03_Data_Augmentation.ipynb
- Explores **data augmentation techniques** to improve ML model performance.
- Uses **MNIST dataset** to demonstrate:
  - **Rotation augmentation**
  - **Shear augmentation**
  - **Combined rotation + shear**
- Includes **grid search for hyperparameter tuning** (angle and shear constraints).
- Shows how augmentations increase dataset size and improve accuracy.
- Provides **visual demonstrations** of augmented images to reinforce learning.

---

## 🧠 Learning Goals

- Strengthen understanding of **mathematical foundations** behind AI and ML.
- Bridge the gap between **theory and practical coding**.
- Develop the ability to **analyze, extract, and visualize meaningful features** from raw data.
- Learn **classification techniques, validation strategies, and data augmentation**.
- Build a reusable, easy-to-follow reference for **revision and project preparation**.

---

## 🛠️ Tools & Libraries Used

All notebooks are built and tested on **Google Colab** using **Python 3.x**.

**Commonly Used Libraries:**
```python
numpy          # Numerical computations and array operations
pandas         # Data manipulation and analysis
matplotlib     # Static visualizations
plotly         # Interactive charts and dashboards
scipy          # Scientific computing and statistics
scikit-learn   # Machine learning algorithms and preprocessing
keras          # Deep learning and datasets (MNIST)
skimage        # Image processing and augmentation
