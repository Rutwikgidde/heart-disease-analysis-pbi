# 💓 Heart Disease Analysis Dashboard - Power BI Project

## 📌 Overview

This project presents an interactive Power BI dashboard built to analyze and visualize patterns in a **Heart Disease dataset**. It focuses on identifying **key health indicators**, exploring **risk factors**, and providing **insightful visualizations** to support better understanding and prediction of heart disease presence.

---

## 🧾 Dataset Contains:


**Columns:**
- `age`: Age of the patient
- `sex`: Gender (1 = male, 0 = female)
- `cp`: Chest pain type (1–4)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol in mg/dL
- `fbs`: Fasting blood sugar > 120 mg/dL (1 = true, 0 = false)
- `restecg`: Resting ECG results (0–2)
- `thalach`: Max heart rate achieved
- `exang`: Exercise-induced angina (1 = yes, 0 = no)
- `oldpeak`: ST depression
- `slope`: Slope of peak exercise ST segment (1–3)
- `ca`: Number of major vessels colored by fluoroscopy
- `thal`: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)
- `num`: Target variable (0 = no disease, 1 = presence of heart disease)

---

## 🎯 Objectives

- Analyze demographic trends among patients
- Identify risk factors for heart disease
- Explore patterns in chest pain, ECG results, and exercise responses
- Create interactive visuals for deep exploration
- Highlight insights that aid in heart disease prediction

---

## 📊 Key KPIs

| KPI                             | Value     |
|----------------------------------|-----------|
| Total Patients                  | 303       |
| Heart Disease Prevalence (%)    | 45.87%    |
| Average Age (With Disease)      | 56.63 yrs |
| Average Age (Without Disease)   | 52.59 yrs |
| Overall Average Age             | 54.44 yrs |

---

## 📈 Dashboard Features

### ✅ **Page 1: Overview**
- KPIs and summary cards
- Age & gender distribution
- Disease prevalence by demographic

### ✅ **Page 2: Risk Factor Analysis**
- Cholesterol vs Heart Disease
- Fasting blood sugar impact
- Max heart rate & ST depression by disease status

### ✅ **Page 3: Chest Pain & Symptoms**
- Chest pain type distribution
- Chest pain by gender & age
- Exercise-induced angina comparison

### ✅ **Page 4: ECG & Prediction Insights**
- Resting ECG vs Heart Disease
- Slope of ST segment analysis
- Scatter plots for multi-variable patterns
- Optional Sankey or Tree Map (Chest Pain + Age + Cholesterol combinations)

---

## 🛠 How to Use

1. Download or clone the repository
2. Open `Project 3.pbix` in Power BI Desktop
3. Make sure you have:
   - **Power BI Sankey Chart** (if using Sankey)
   - Custom visuals from Marketplace if needed
4. Refresh the dataset if not preloaded
5. Explore the dashboard using slicers and filters

---

## 🧠 Insights

- **Higher cholesterol and abnormal chest pain types** often correlate with heart disease.
- **Exercise-induced angina and low max heart rate** are common in patients with heart disease.
- **Younger patients** (<50) tend to have a lower prevalence.

---

## 🖥 Tools Used

- Power BI Desktop
- DAX for calculated measures and KPIs
- GitHub (for dataset hosting)

---

