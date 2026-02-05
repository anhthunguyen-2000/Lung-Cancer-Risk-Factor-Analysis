# Lung Cancer Risk Factor Analysis

**Tools:** Power BI  
**Objective:** Visualize and analyze key risk factors associated with lung cancer, including Lifestyle, Symptoms, Genetic & Biological, General Health Symptoms.
---

## Project Overview
Lung cancer is one of the leading causes of cancer-related mortality worldwide. Analyzing risk factors helps identify early warning signs, supports early screening, and provides insights for effective prevention strategies.

This project uses **Power BI** to:
- Clean and transform the dataset  
- Visualize lung cancer risk factors  
- Explore relationships between symptoms, lifestyle habits, and risk levels  
- Present insights across different factor groups
  
---

## Dataset  
<img width="503" height="409" alt="image" src="https://github.com/user-attachments/assets/876cd289-8f68-4c7e-a5c4-016d5e01c2fa" />
<img width="506" height="411" alt="image" src="https://github.com/user-attachments/assets/c3dc5858-58e6-4509-9594-563edcc5fa6d" />

---

## Data Preprocessing (Power BI – Power Query)

Key data cleaning and transformation steps:
- The dataset contains multiple measurement scales (1–7, 1–8, 1–9).  
  → All health-related variables were normalized to a **0–1 scale** for consistency.  
- Standardized data formats  
- Checked for missing or abnormal values  
- Restructured tables based on factor groups:
  - Lifestyle  
  - Symptoms  
  - Genetic & Biological Factors  
  - General Health Symptoms  
- Created a **Risk Level** classification column based on the sample data   

---

## Power BI Dashboard

The dashboard is divided into several analytical sections:

### Data Overview
- Lung cancer prevalence by gender  
- Age group distribution  
- Risk level distribution  

### Risk Factor Group Analysis
- Lifestyle vs Lung Cancer  
- Symptoms vs Lung Cancer  
- Genetic & Biological Factors  
- General Health Symptoms  

### Symptom Analysis
- Frequency of symptom occurrence  
- Number of symptoms by risk group  
- Relationship between symptoms and lung cancer outcome  

### Correlation Analysis
- Correlation matrix of risk factors  
- Identification of the most influential risk factors  

---

## Key Findings

### Strongest Risk Factors
Based on correlation analysis and frequency within the **Lung Cancer = Yes** group, the most influential factors are:

1. Smoking  
2. Chronic Disease  
3. Wheezing  
4. Shortness of Breath  
5. Chest Pain  

---

### Demographic Insights
- Males show a higher lung cancer risk than females  
- The **31–45 age group** has the highest prevalence  

---

### Lifestyle Factors
- **Smoking** has the strongest impact on lung cancer risk  
- **Peer pressure** indirectly increases risk by influencing smoking behavior  
- **Alcohol consumption** has an impact, but weaker compared to other factors  

---

### Symptom Patterns
Key warning symptoms include:
- Shortness of breath  
- Chest pain  
- Persistent cough  
- Wheezing  

The combination of **shortness of breath + chest pain** appears most frequently in the high-risk group.

---

## Conclusion
The analysis shows that lung cancer risk is strongly influenced by:
- Lifestyle factors (especially smoking)  
- Respiratory symptoms  
- Chronic or respiratory-related diseases  
- Age and gender  

Among all variables, **smoking is the dominant risk factor** with the greatest overall impact.

---

## Recommendations

### For the Community
- Reduce or eliminate smoking  
- Seek medical screening when persistent symptoms appear  
- Pay special attention to individuals aged **45+** or those with underlying health conditions  

---

## Attachments
- `lung_cancer_dashboard.pbix` — Power BI dashboard  
- `lung_cancer_presentation.pptx` — Presentation slides  
- `README.md` — Project documentation  

---

## Skills Demonstrated
- Power BI Data Cleaning (Power Query)  
- Data Visualization  
- Dashboard Design  
- Correlation Analysis  
- Insight Interpretation  
- Analytical Storytelling  

