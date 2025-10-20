# Graduate Admission Prediction (UCLA Dataset)

This project predicts the probability of graduate school admission using the **UCLA Admission dataset**.  
The dataset contains applicant features such as GRE, TOEFL, SOP, LOR, GPA, and Research experience, and the target variable is the **Chance of Admit** (0–1).  
The project explores both **regression** and **classification** approaches using Python and scikit-learn.

---

## 📊 Dataset
- **Source:** UCLA admission dataset (commonly used in ML regression tasks).  
- **Features:**
  - GRE Score (out of 340)
  - TOEFL Score (out of 120)
  - University Rating (1–5)
  - Statement of Purpose (SOP) Strength (1–5)
  - Letter of Recommendation (LOR) Strength (1–5)
  - CGPA (out of 10)
  - Research Experience (0 = No, 1 = Yes)
- **Target:** Chance of Admit (0–1)

---

## 🚀 Features of the Project
- **Exploratory Data Analysis (EDA):**
  - Distribution of features and target.
  - Correlation heatmap to identify feature importance.
- **Regression Models:**
  - Linear Regression
  - Multi-Layer Perceptron (MLP) Regressor
  - Evaluation with **R² Score** and error metrics.
- **Classification Models:**
  - Converted admission probability into binary labels (Admitted vs Not Admitted).
  - Applied Logistic Regression, Decision Trees, and Neural Networks.
  - Evaluation with Accuracy, Precision, Recall, F1-score.
- **Model Selection & Tuning:**
  - Hyperparameter tuning (hidden layers, learning rate, batch size).
  - Regularization with Dropout, Early Stopping, and Learning Rate Schedulers.
- **Visualization:**
  - Training/validation curves for neural networks.
  - Comparison of predicted vs actual admission probabilities.
  - Confusion Matrix for classification results.

---
