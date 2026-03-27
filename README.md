---

# Integrated Data Analysis Project (NumPy)

## Scenario

A hospital collected health data from 10 patients. Each patient has the following measurements:

* **Age**
* **Weight (kg)**
* **Systolic Blood Pressure**
* **Cholesterol Level**

This project performs a full **data analysis pipeline** on the dataset.

---

## 📊 Dataset

| Age | Weight (kg) | Blood Pressure | Cholesterol |
| --- | ----------- | -------------- | ----------- |
| 25  | 70          | 120            | 180         |
| 30  | 80          | 130            | 190         |
| 22  | 65          | 110            | 170         |
| 45  | 90          | 150            | 210         |
| 50  | 85          | 145            | 200         |
| 28  | 75          | 125            | 185         |
| 35  | 88          | 140            | 195         |
| 40  | 95          | 155            | 220         |
| 32  | 78          | 135            | 188         |
| 27  | 72          | 122            | 182         |

*Visualization suggestion: Add a heatmap of the dataset or a table image.*

---

## Part 1 — Basic Statistics 📈

**Objectives:**

* Calculate the **mean** of each column.
* Calculate the **standard deviation** of each column.
* Find **maximum and minimum values** for each feature.

*Visualization suggestion:* Use bar charts to compare mean, min, and max of each feature.

---

## Part 2 — Health Risk Detection ⚠️

**Identify high-risk patients with both conditions:**

* Blood Pressure > 140
* Cholesterol > 200

Return the **indices of these patients**.

*Visualization suggestion:* Highlight high-risk patients in a scatter plot (Blood Pressure vs Cholesterol).

---

## Part 3 — Feature Scaling 🔄

Apply **Min-Max Normalization** to scale all features to the range [0, 1]:

*Visualization suggestion:* Plot a side-by-side comparison of original vs normalized data.

---

## Part 4 — Correlation Analysis 🔗

Compute the **correlation matrix** to explore relationships between features:

* Age
* Weight
* Blood Pressure
* Cholesterol

*Visualization suggestion:* Use a heatmap to visualize correlations between all variables.

---

## Part 5 — Risk Score Calculation 💓

Define a **Health Risk Score** using normalized features:


**Tasks:**

1. Compute the risk score for each patient.
2. Identify the **top 3 highest-risk patients**.

*Visualization suggestion:* Use a horizontal bar chart to show risk scores and highlight the top 3 patients.

---

## 📌 Summary

This project demonstrates:

* **Basic statistical analysis** of health data
* **High-risk patient detection** based on multiple health metrics
* **Feature normalization** for consistent scaling
* **Correlation analysis** to understand relationships
* **Risk scoring** to prioritize patients

*Optional visuals:*

* Dataset table with highlighted top 3 risk patients
* Scatter plot of Blood Pressure vs Cholesterol
* Correlation heatmap
* Risk score bar chart

---
