# 💧 Water Quality (Potability) Analysis

This project analyzes the **Water Potability Dataset**, which contains **3,276 samples** of water quality data.  
The goal is to determine whether water is **safe (potable)** or **unsafe (non-potable)** for human consumption based on various chemical and physical parameters.

---

## 📊 About the Dataset

**Dataset Name:** Water Potability Dataset  
**File Name:** `Water Potability Dataset.csv`  
**Total Samples:** 3,276  
**Total Features:** 10  
**Target Column:** `Potability` (1 = Safe to Drink, 0 = Not Safe)

This dataset helps assess the safety of water by analyzing its chemical composition and physical characteristics.  
It can be used for **data analysis**, **machine learning**, and **environmental research** to understand the key factors that affect water quality.

---

### 🧪 Features and Descriptions

| Feature | Description |
|----------|--------------|
| **ph** | pH value of the water, indicates acidity or alkalinity (0–14 scale) |
| **Hardness** | Amount of dissolved calcium and magnesium in mg/L |
| **Solids** | Total dissolved solids in ppm (parts per million) |
| **Chloramines** | Amount of chloramine (disinfectant) in ppm |
| **Sulfate** | Sulfate concentration in mg/L |
| **Conductivity** | Electrical conductivity of water in μS/cm |
| **Organic_carbon** | Amount of organic carbon in ppm |
| **Trihalomethanes** | Concentration of trihalomethanes (chemical compounds) in μg/L |
| **Turbidity** | Measure of light scattering in water (NTU) |
| **Potability** | 1 = Potable (safe for drinking), 0 = Not potable (unsafe) |

---

## 🎯 Objectives

- Analyze and visualize the water quality parameters  
- Handle missing values and outliers effectively  
- Study correlations between features and potability  
- Build machine learning models to **predict water potability**  
- Identify the most influential factors affecting water safety  

---

## 🧠 Tools & Technologies

- **Python**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib / Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning models and evaluation  
- **Jupyter Notebook / Google Colab** – Analysis environment  

---

## 📈 Key Insights from the Dataset

- Around **39%** of the water samples are **potable**.  
- Missing values exist in **ph (491)**, **Sulfate (781)**, and **Trihalomethanes (162)** columns.  
- Parameters like **pH**, **Chloramines**, and **Sulfate** strongly influence water potability.  
- The dataset is suitable for **binary classification** tasks in machine learning.

---

## 🚀 Potential Applications

- Predicting water safety using supervised learning models  
- Environmental monitoring and public health analysis  
- Building dashboards for water quality management  
- Educational projects in data science and environmental studies  

---

## 🗂️ File Information

| File Name | Description |
|------------|-------------|
| `Water Potability Dataset.csv` | Dataset used for analysis and model building |
| `water_quality_analysis.ipynb` | Python notebook containing the code |
| `README.md` | Project documentation |

---
