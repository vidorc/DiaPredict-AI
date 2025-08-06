# DiaPredict-AI
# DiaPredict AI 🩺

> A machine learning model to predict the risk of developing Type 2 Diabetes, built on the "Rock vs. Prediction" principle.

This project leverages clinical data to forecast future health outcomes, clearly distinguishing between established medical facts and probabilistic risk assessment.

**Disclaimer:** This tool is for educational and research purposes only. The output is **not a medical diagnosis**. Always consult a qualified healthcare professional for medical advice.

---

## 🗿 The Rock: The Clinical Ground Truth

In the context of this project, The Rock represents the hard, objective, and verifiable clinical data from an individual. This is the ground truth upon which our model is trained and against which its accuracy is measured.

**The Rock consists of key biomarkers and patient data:**

* `Blood Glucose Levels` (Fasting & Postprandial)
* `HbA1c` Percentage
* `Body Mass Index (BMI)`
* `Blood Pressure`
* `Plasma Insulin Levels`
* `Age` & `Family History`

> The Rock is the collection of established medical facts. It is the "what is" that forms the foundation of our entire model.

## 🔮 The Prediction: The Probabilistic Risk Score

The Prediction is the output of our machine learning model. It is a calculated forecast of an individual's risk of developing diabetes within a specific timeframe (e.g., 5-10 years). It is an inference, not a certainty.

**The Prediction provides an actionable insight:**

* A **probability score** (e.g., `0.75` indicating a 75% risk).
* A **risk category** (`Low`, `Medium`, `High`).
* **Feature Importance** (e.g., indicating that `BMI` and `Glucose` were the strongest contributors to the risk score).

> The Prediction's purpose is not to diagnose, but to **empower preventative action**. It answers "what could be" so that individuals and clinicians can intervene early.

## How It Works

This model is a [e.g., `Logistic Regression`, `Gradient Boosting`, `Neural Network`] model trained on a dataset of anonymized patient records. It learns the complex patterns within the **Rock** data to generate a **Prediction** score.

**Tech Stack:** `Python`, `Scikit-learn`, `Pandas`
