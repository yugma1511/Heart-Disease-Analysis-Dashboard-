#💓 Heart-Disease-Analysis-Dashboard
This project is a data-driven dashboard developed in Power BI, providing insightful visualizations around heart disease survival trends based on gender and age groups.
🔍 Overview
The dataset includes medical and demographic information, which has been visualized to highlight:

Total Deaths and Survivals

Survival Rate & Avg Age of Survival

Comparison by Gender (Female, Male, All)

Key Health Factors:

Serum Creatinine

Ejection Fraction

High Blood Pressure, Anaemia, Smoking, Diabetes

📊 Visuals Included
Survival Rate by Age Group

Death Count vs Serum Creatinine

Death Count vs Ejection Fraction

Spline chart of comorbidities

Gender toggle: Compare trends across M/F

⚙️ Tools & Technologies
Power BI

DAX
avg age of Survival = CALCULATE(AVERAGE(heart_Disease_clinical_records_[age]),heart_Disease_clinical_records_[DEATH_EVENT]=0)
Survival rate = 1-DIVIDE(sum(heart_Disease_clinical_records_[DEATH_EVENT]),count(heart_Disease_clinical_records_[count]))
total death = CALCULATE(count(heart_Disease_clinical_records_[count]),heart_Disease_clinical_records_[DEATH_EVENT]=1)
total Survival = CALCULATE(COUNT(heart_Disease_clinical_records_[count]),heart_Disease_clinical_records_[DEATH_EVENT] = 0)

Data Cleaning & Modeling

📁 Screenshots
Includes dashboards for:
Overall Population:
<img width="1276" height="714" alt="Screenshot 2025-08-07 135512" src="https://github.com/user-attachments/assets/65dd2927-d84b-4726-9a48-50f7fede2b62" />
Female-Only Analysis
<img width="1274" height="713" alt="Screenshot 2025-08-07 135537" src="https://github.com/user-attachments/assets/a56ae86a-aeb2-4251-9587-5981bc60bb61" />
Male-Only Analysis
<img width="1278" height="716" alt="Screenshot 2025-08-07 135555" src="https://github.com/user-attachments/assets/5b447a9a-f6ac-49e3-ad9e-9a6120918c07" />

📎 Use Cases
Health risk profiling by demographic

Identifying age groups at higher cardiac risk

Comparative gender-based health data visualization

Medical data storytelling with interactive dashboards

🌐 LinkedIn Post
View the live post 👉 https://www.linkedin.com/posts/activity-7359170578810908674-tEnI?utm_source=share&utm_medium=member_desktop&rcm=ACoAADv0_ywB9yrAw6kapsW8WJUgO9Fjs4eGzRo



