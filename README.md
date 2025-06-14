# ✈️ Flight Delay Prediction and Root Cause Analysis

This project applies data science and machine learning to predict flight delays and uncover key operational bottlenecks in U.S. domestic airline operations. It combines classification, regression, and explainable AI (XAI) techniques to not only forecast delays but also reveal actionable insights using SHAP and a custom Operational Adjustability Index (OAI).

---

## 🔍 Problem Statement

Flight delays are a major challenge in the aviation industry, affecting both customer satisfaction and airline operations. The goal of this project is to:
- Predict whether a flight will be delayed (Yes/No).
- Estimate the expected delay duration in minutes.
- Identify root causes and controllable delay factors.
- Provide actionable recommendations to airlines.

---

## 🛠️ Tools & Technologies

- **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **scikit-learn** (Random Forest Classifier & Regressor)
- **SHAP (SHapley Additive Explanations)**
- **Google Colab / Jupyter Notebook**

---

## 📊 Approach & Methodology

1. **Exploratory Data Analysis (EDA):**
   - Visualized delay patterns across months, carriers, and airports.
   - Analyzed delay causes using correlation matrices and pie charts.

2. **Predictive Modeling:**
   - Trained a Random Forest Classifier for binary delay prediction (Accuracy = 100%).
   - Trained a Random Forest Regressor to predict delay duration (MAE ≈ 687 mins, RMSE ≈ 2271 mins).

3. **Model Explainability:**
   - Used SHAP summary plots and force plots to interpret feature impact.
   - Applied a custom **Operational Adjustability Index (OAI)** to emphasize controllable delays (carrier, late aircraft).

4. **Strategic Recommendations:**
   - Suggested delay mitigation strategies for airlines including ground ops optimization, proactive scheduling, and targeted interventions.

---

## 📈 Key Results

| Task                    | Metric          | Value        |
|-------------------------|-----------------|--------------|
| Delay Classification    | Accuracy         | 100%         |
| Delay Duration Prediction | MAE / RMSE     | 687 / 2271 mins |
| Top Delay Causes        | Carrier, Late Aircraft |
| SHAP + OAI Insight      | Controllable delays prioritized for mitigation |

---

## 🧠 Insights & Impact

- Over **75% of delays** were found to be caused by controllable factors.
- SHAP + OAI highlighted **carrier delays** and **late aircraft turnaround** as critical intervention points.
- Provided **data-backed strategies** to improve operational efficiency and reduce delay frequency.

---
