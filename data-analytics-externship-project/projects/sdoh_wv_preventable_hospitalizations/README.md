# TruBridge Externship Project: Social Determinants of Health & Preventable Hospitalizations in West Virginia

**Author:** Eva Brown  
**Date:** November 2025  
**Project Type:** Data Analytics Externship – TruBridge  
**Tools:** Python (Colab), Pandas, NumPy, Matplotlib, Seaborn, Excel, Power BI / AI-assisted presentation

---

## 📌 Project Overview

This project explores how **Social Determinants of Health (SDOH)** relate to **Preventable Hospitalizations** across **West Virginia counties**. Through data cleaning, merging, exploratory data analysis (EDA), visualizations, and dashboard creation, the purpose of this project is to support healthcare insights that enable more proactive decision-making for rural communities.

The final deliverables include:
- Cleaned and merged datasets  
- A fully annotated exploratory notebook  
- Visualizations (scatterplots, histograms, correlation patterns)  
- A structured data story  
- A dashboard  
- A presentation outline created using AI (Gamma)

This repository showcases the entire workflow used to complete the TruBridge externship.

---

## 🎯 Research Questions

1. How do preventable hospitalization rates vary across West Virginia counties?
2. Which SDOH variables (poverty, education, uninsured rates, unemployment, rurality) are most associated with preventable hospitalizations?
3. What patterns emerge when comparing key SDOH indicators to hospitalization outcomes?
4. Which counties represent the greatest need for intervention?

---

## 🧮 Methods & Workflow

This project followed a clear, industry-standard data analytics lifecycle:

### **1. Data Acquisition**
- Downloaded raw County Health Rankings (CHR&R) 2025 dataset for WV  
- Extracted relevant SDOH features  
- Added supplemental datasets (insurance, poverty, education, etc.)

### **2. Data Cleaning & Preprocessing**
- Renamed columns  
- Dropped irrelevant measures  
- Standardized county names  
- Addressed missing values and redlined data  
- Created cleaned and imputed Phase 3 datasets  
- Finalized merged dataset for exploration  

### **3. Exploratory Data Analysis**
Using Python + Pandas + Seaborn:
- Summary statistics  
- Histograms (distribution of hospitalization rates)  
- Scatterplots comparing SDOH variables to hospitalization outcomes  
- Correlation exploration  
- Identification of extreme values or missing data behavior  

### **4. Storyboarding & Presentation Design**
- Structured data story aligned to externship requirements  
- Identified 3–5 core insights to communicate clearly  
- Developed final presentation outline in Gamma  

### **5. Dashboard Creation**
- Designed dashboard views showing:
  - County-level SDOH indicators  
  - Hospitalization rates  
  - Key comparison charts  
- Added screenshots and a dashboard walkthrough  

---

## 📊 Key Insights

- **Preventable hospitalization rates vary significantly** across WV counties.
- Counties with **higher poverty** and **lower educational attainment** generally show **higher hospitalization rates**.
- Rural counties tend to struggle with **higher uninsured rates**, which may contribute to delayed care-seeking.
- SDOH variables interact — they do not act independently.  
  Combined poverty + low education + high uninsurance often correlate with higher risk.
- These insights can guide **targeted resource allocation**, especially for rural healthcare improvement.

---

## 📁 Repository Structure

```text
trubridge-sdoh-wv-analytics/
│
├── README.md
├── requirements.txt
│
├── data/
│   ├── raw/
│   │   ├── 2025_County_Health_Rankings_WV.xlsx
│   │   ├── select_measure_data_cleaned.csv
│   │   ├── additional_measure_data_cleaned.csv
│   │
│   ├── processed/
│   │   ├── county_health_rankings_wv_merged_clean.csv
│   │   ├── df_final_cleaned.csv
│   │   ├── wv_trubridge_cleaned_phase3.csv
│
├── notebooks/
│   ├── PROJECT_County_Health_Rankings_West_Virginia_final.ipynb
│
├── dashboard/
│   ├── dashboard_screenshots/
│   │   ├── dashboard_overview.png
│   │   ├── hospitalization_map.png
│   │   └── sdoh_visuals.png
│   └── dashboard_notes.md
│
├── reports/
│   ├── presentation_outline.md
│   ├── trubridge_data_story.pdf
│   └── trubridge_slide_deck.pdf
│
└── docs/
    ├── DATA_SOURCES.md
    └── project_journal_notes.md
