# 🦠 COVID-19 Data Analysis (EDA)

## 🚀 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on the **COVID-19 dataset** obtained from **Kaggle** (`Covid Data.csv`).  
The analysis uncovers critical insights into **patient outcomes, comorbidities, ICU admissions, and age-related risk patterns** during the COVID-19 pandemic.

---

## 🧾 Dataset Description

**Source:** Kaggle  
**File Used:** `Covid Data.csv`

Each record represents an individual COVID-19 patient, with attributes such as:

| Feature | Description |
|----------|--------------|
| `USMER` | Level of medical unit (1st, 2nd, or 3rd) |
| `AGE` | Patient age |
| `ICU` | ICU admission status |
| `DIABETES`, `ASTHMA`, `PNEUMONIA`, `COPD`, `OBESITY`, etc. | Presence of underlying conditions |
| `DATE_DIED` | Indicates whether the patient survived or not |
| `PREGNANT` | Pregnancy status (if applicable) |
| `CLASIFFICATION_FINAL` | COVID test result classification |

---

## 📊 Key Insights

### **1️⃣ Death Rate by Medical Unit Level (USMER)**  
**Question:** Who has the highest death rate based on the level of care the patient was admitted to?  
**Answer:** Although patient counts were similar across levels, **first-level medical units recorded the highest death rate**.  


---

### **2️⃣ Diabetes & Asthma Impact**  
**Question:** What percentage of patients with diabetes or asthma survived or died?  
**Answer:** **More than half of these patients survived**, while the rest unfortunately did not.  

---

### **3️⃣ ICU Admission & Survival Rate**  
**Question:** How many patients were admitted to the ICU, and what percentage survived?  
**Answer:** A **small proportion** of patients required ICU care, and **around 50% of those did not survive**, showing the severity of cases requiring intensive support.  


---

### **4️⃣ Disease Most Linked to Death**  
**Question:** Which underlying disease is most associated with higher death rates?  
**Answer:** **Pneumonia** had the **strongest association with fatal outcomes**, making it the most dangerous comorbidity.  


---

### **5️⃣ Age Group Most Affected**  
**Question:** Which age group was most affected by COVID-19?  
**Answer:** The **55–65-year age group** showed the highest infection rate and death count, marking them as the most vulnerable population segment.  


---

## 🧠 Tools & Libraries Used

| Tool | Purpose |
|------|----------|
| **Python** | Programming & analysis |
| **Pandas** | Data cleaning & transformation |
| **NumPy** | Numerical computation |
| **Matplotlib** | Plotting & chart generation |
| **Seaborn** | Advanced visualization (heatmaps, barplots, etc.) |
| **Jupyter Notebook** | Interactive analysis |

---

## 📈 Visualizations

Below are a few key visualizations generated during the analysis:
- **Bar Charts** for comparing disease-wise survival and death counts  
- **Line Plots** for ICU admissions and medical unit trends  
- **Heatmaps** for correlation among diseases  
- **Histograms** for age distribution  


---

## 💡 Conclusion

This analysis provides valuable insights into how **age, comorbidities, and care levels** affected COVID-19 outcomes.  
Key takeaways:
- **First-level medical units** saw higher death rates.  
- **Pneumonia** was the most fatal comorbidity.  
- **Ages 55–65** were the most impacted demographic.  
- **ICU admissions** carried a high mortality risk (~50%).  

These insights can guide **public health strategies** and help identify **high-risk groups** for better preparedness in future pandemics.

---



