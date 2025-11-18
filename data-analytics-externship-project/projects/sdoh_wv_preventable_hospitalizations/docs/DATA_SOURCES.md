# 📊 DATA_SOURCES.md  
### *SDOH & Preventable Hospitalizations — West Virginia*

This document describes all datasets used in this analysis, their origins, and whether they have been transformed.

---

## 📁 1. Raw Datasets

### **2025 County Health Rankings — West Virginia**  
**Source:** County Health Rankings & Roadmaps (CHR&R)  
**URL:** https://www.countyhealthrankings.org  
**Notes:**  
- Publicly accessible  
- Contains county-level health outcomes and SDOH indicators  
- Used as baseline input data

---

### **select_measure_data_cleaned.csv**  
**Source:** Derived from the CHR&R dataset  
**Transformation:**  
- Selected a subset of relevant SDOH indicators  
- Cleaned column names  
- Standardized county identifiers  

---

### **additional_measure_data_cleaned.csv**  
**Source:** Supplemental variables extracted from CHR&R or other public datasets  
**Transformation:**  
- Cleaned  
- Reshaped  
- Used for merging into main dataset  

---

## 📁 2. Processed Datasets

### **county_health_rankings_wv_merged_clean.csv**  
**Description:**  
Intermediate merged dataset combining selected and supplemental SDOH measures.

---

### **df_final_cleaned.csv**  
**Description:**  
Fully cleaned dataset after:  
- Handling missing values  
- Standardizing column formats  
- Removing irrelevant features  

---

### **wv_trubridge_cleaned_phase3.csv**  
**Description:**  
Final version used in the Jupyter/Colab notebook for EDA.

---

## 📄 Licensing & Redistribution  
All data originates from publicly accessible, non-restricted sources.  
Only cleaned and derived datasets are stored in this repository.  

