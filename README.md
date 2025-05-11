# AI Models Compilation

This repository contains a small set of AI models developed through both individual explorations and group projects. It showcases work in applied machine learning, including data preprocessing, model training, and evaluation using Jupyter notebooks.

> **Note:** Some models are still in progress or bound by academic confidentiality rules. Details below.

---

## Contents

### `ads.ipynb` — *Ad Click Prediction*  
A model initially designed for predicting user ad-click behavior.  
- **Status:** Incomplete due to lack of sufficient and clean dataset.

---

### `heartlogis.ipynb` — *Heart Disease Classification using Logistic Regression*  
A binary classification model that detects the likelihood of heart disease based on patient features.  
- **Status:** Functional and tested.
- **Model:** `LogisticRegression()` from Scikit-learn.

#### ⚠️ Warning Explanation:
While training the model, the following convergence warning is encountered:


**Explanation:**  
This warning indicates that the logistic regression solver (`lbfgs`) did not reach optimal convergence within the default number of iterations. This is a common issue and does **not** necessarily indicate a model failure. It can be addressed by:
- Increasing the `max_iter` parameter.
- Scaling the dataset using techniques such as StandardScaler.
- Trying alternative solvers like `saga` or `liblinear` depending on the dataset size and sparsity.

Despite the warning, the model is still functional and produces meaningful results.

---

### `cry_detection` — *Infant Cry Classification (Thesis Project)*  
A deep learning model developed to classify various types of infant cries (e.g., hungry, pain, discomfort).  
- **Status:** Complete, with real-time data support and audio input preprocessing.
- **Note:** Due to university academic integrity policies, the core implementation notebook (`cry_classification.ipynb`) is **not included** in this repository.  

This project reflects significant collaborative effort and was the centerpiece of our undergraduate thesis.

---

## 👥 Credits

This compilation represents a mixture of:
- **Individual Projects** — showcasing technical initiative and experimentation.
- **Group Collaborations** — reflecting teamwork, research integration, and model development for academic and practical purposes.

---


