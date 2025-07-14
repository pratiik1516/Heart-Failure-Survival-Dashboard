
readme_content = """
# 🫀 Heart Failure Survival Dashboard

![Tableau Badge](https://img.shields.io/badge/Tableau-Dashboard-E97627?style=for-the-badge&logo=tableau&logoColor=white)

## 📌 Description

This **Tableau project** provides a detailed survival analysis of patients with heart failure based on clinical records. The dashboard explores various health indicators—like anaemia, high blood pressure, diabetes, serum creatinine, ejection fraction, and more—to uncover patterns in survival rates.

> 🔍 Built to support data-driven decisions in healthcare and cardiology research.

---

## 📊 Key Insights

- Analyzed data of **299 heart failure patients**, with **96 recorded deaths**.
- Visualized impact of key factors:
  - Anaemia, Diabetes, High Blood Pressure, Smoking  
  - Ejection Fraction, Serum Creatinine, Age & Time
- Found correlations between **low ejection fraction**, **high serum creatinine**, and **increased mortality**.
- Compared survival rates by **gender**, **age**, and **chronic conditions** using interactive visualizations.

---

## 📷 Screenshot

> ![Heart Failure Dashboard](Dashboard%201.png)  
*(Ensure this image is uploaded in your repository)*

---

## 🛠 Tools & Technologies

- [x] Tableau Desktop  
- [x] CSV data integration  
- [x] Filters and slicers for dynamic exploration  
- [x] Dual-axis charts and histograms  
- [x] Calculated fields for survival classification

---

## 📁 Dataset Summary

- **heart_failure_clinical_records_dataset.csv**  
  - Fields: `age`, `anaemia`, `creatinine_phosphokinase`, `diabetes`, `ejection_fraction`, `high_blood_pressure`, `platelets`, `serum_creatinine`, `serum_sodium`, `sex`, `smoking`, `time`, `DEATH_EVENT`
  - Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records)

---

## 📈 Visuals Included

- Donut Charts for comorbidities vs survival  
- Histograms for Age, Time, Ejection Fraction, and Lab Results  
- Boxplots by Sex & Survival  
- Scatter plot of Age vs Time with survival color  
- Summary cards: Total individuals, deaths, gender distribution, and average age

---

## 🧠 Project Learnings

- Explored **clinical predictors of mortality** using Tableau.
- Applied **data blending and formatting** for healthcare records.
- Designed an interactive analytical view to assess **risk factors**.
- Interpreted visual patterns for **decision support in cardiology**.

---

## ✅ How to Use

1. Download the `.twbx` file (`Heart Failure Survival.twbx`) from this repository.  
2. Open it in [Tableau Desktop](https://www.tableau.com/products/desktop).  
3. Explore the dashboard filters and hover for deeper insights.

---

## 🏁 Conclusion

This dashboard helps healthcare professionals and analysts to identify key clinical indicators affecting heart failure survival, guiding proactive treatment strategies and patient monitoring.

---

> 💬 Contributions, feedback, and forks are welcome to enhance the project further!
"""

# Save it as a markdown file
with open("README.md", "w") as f:
    f.write(readme_content)
