# 📘 VARIABLES_DICTIONARY.md  
### *Key Variables in the SDOH & Preventable Hospitalizations Dataset*

This dictionary explains the main variables used in the analysis.  
Variable names may be abbreviated in the dataset for clarity.

---

## 🏥 Outcome Variable

### **preventable_hospitalization_rate**  
- County-level hospitalization events that could have been avoided through preventive care.  
- Numeric — rate per 100,000 or as provided in source.

---

## 🌍 Social Determinants of Health (SDOH)

### **poverty_rate**  
- Percentage of residents living below the federal poverty threshold.  

### **education_less_than_high_school**  
- % of population age 25+ with less than a high school diploma.  

### **unemployment_rate**  
- % of workforce unemployed but seeking work.

### **uninsured_rate**  
- % of adults without health insurance coverage.

### **rurality_score**  
- Indicator of rural classification (binary or scaled).  

### **median_household_income**  
- Median annual household income in U.S. dollars.

---

## 📊 Additional Measures

### **social_association_rate**  
- Community membership/participation metric.  
- May be missing or incomplete in rural counties.

### **population_total**  
- Total county population.

---

## 📁 Notes
- Some variables were renamed for clarity.  
- Missing values were imputed using median-based techniques.  
- Outliers were visually inspected during EDA.

