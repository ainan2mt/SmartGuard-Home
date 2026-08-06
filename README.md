# SmartGuard Home: AI-Based Biometric Access System for Safe Household Movement Control

## Overview

This project presents a machine learning-based fingerprint authentication module for the proposed **SmartGuard Home** framework. Fingerprint images from the SOCOFing dataset were preprocessed, features were extracted using HOG, LBP, and GLCM, and three machine learning models (Decision Tree, Random Forest, and XGBoost) were evaluated for biometric authentication.

## Dataset

* **Dataset:** SOCOFing (Sokoto Coventry Fingerprint Dataset)
* **Source:** https://www.kaggle.com/datasets/ruizgara/socofing

## Technologies Used

* Python
* Jupyter Notebook
* OpenCV
* NumPy
* Pandas
* Scikit-learn
* XGBoost
* scikit-image
* imbalanced-learn (SMOTE)

## Project Structure

```text
SmartGuard-Home/
│
├── SmartGuardFAS.ipynb
├── SmartGuard_Home__AI_Based_Biometric_Access_System Report.pdf
├── README.md
├── requirements.txt
└── images/
```

## How to Run

1. Install the required libraries:

```bash
pip install -r requirements.txt
```

2. Open `SmartGuardFAS.ipynb`.

3. Run all notebook cells sequentially.

## Results

The fingerprint authentication models were evaluated using Accuracy, Precision, Recall, F1 Score, AUC, FAR, and FRR. Decision Tree, Random Forest, and XGBoost were compared, along with additional experiments on feature selection and different numbers of authorized users.

## Authors

**Tasnia Jakia** **&** **Marjia Ainan**
(**ID-E241415,E241423**)

Department of Computer & Communication Engineering (CCE)

International Islamic University Chittagong (IIUC)
