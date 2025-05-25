# Coding Week 2025 — Task 1 Report

**Name:** Aditya Garg  
**Roll Number:** 240101008

---

## Overview

This report summarizes my approach and key findings for Task 1 of the Coding Week 2025 Machine Learning challenge. The main objective was to explore the student dataset, clean and visualize the data, and extract meaningful insights about student performance, background, and aspirations.

---

## 1. Data Cleaning and Preparation

- Loaded the dataset and examined its structure and summary statistics.
- Checked for missing values and handled them to ensure data quality.
- Converted categorical variables (such as parental education, support, and aspirations) into a usable format for analysis.
- Explored distributions of important variables (grades, absences, support, activities, etc.).

---

## 2. Exploratory Data Analysis (EDA)

### A. Academic Performance and Parental Education

- Visualized average final grades (`G3`) by parental education levels (`Fedu`, `Medu`).
- **Insight:** Students with more highly educated parents tend to achieve higher grades.

### B. Impact of Past Failures

- Analyzed the relationship between number of past failures and final grades.
- **Insight:** Students with more past failures have significantly lower average grades.

### C. Absences and Academic Performance

- Plotted average grades against the number of absences.
- **Insight:** More absences are strongly associated with lower academic achievement.

### D. Aspirations for Higher Education

- Compared aspirations for higher education (`higher`) among students with above- and below-average grades.
- **Insight:** A high percentage (about 80%) of students with below-average grades still aspire to higher education.

### E. Support Systems and Internet Access

- Explored the effects of family support (`famsup`), school support (`schoolsup`), and internet access (`internet`) on grades.
- **Insight:** Students with both family and school support, and those with internet access, generally perform better.

### F. Social and Extracurricular Activities

- Examined the relationship between participation in extracurricular activities and academic results.
- **Insight:** Students involved in activities tend to have better attendance and, in some cases, higher grades.

---

## 3. Key Visualizations

- Bar charts showing average grades by parental education, absences, and support types.
- Violin and box plots illustrating the distribution of grades by failures and activities.
- Scatterplots for relationships between social activity and performance.

---

## 4. Summary of Insights

- Parental education, support systems, and attendance are strong predictors of academic success.
- Most students, even those struggling, remain ambitious about higher education.
- Early academic struggles and frequent absences highlight students at risk, suggesting areas for targeted intervention.

---

## 5. Next Steps 

- Using these insights to inform feature selection for predictive modeling.
- Focus on the most impactful variables identified in EDA for building robust models.

---

## Conclusion

Through systematic data cleaning, visualization, and analysis, I have developed a clear understanding of the factors influencing student outcomes in the dataset. These findings provide a solid foundation for any further modeling or intervention strategies.

---

*Thank you for reviewing my submission.*
