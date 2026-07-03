# Titanic Data Analysis Dashboard (Power BI)

A comprehensive data analytics project using **Power BI** and **DAX** to analyze the factors affecting passenger survival on the Titanic.

## 📊 Dashboard Overview
*Paste your dashboard screenshot link here*

## 🔍 Key Insights
- **Overall Survival Rate:** Around 27%-38% (adjust based on your actual dashboard number).
- **Gender Factor:** Females had a significantly higher survival rate compared to males.
- **Class Factor:** First-class (Pclass 1) passengers had a better chance of survival than lower classes.
- **Age Factor:** Children within certain age groups showed higher survival trends.

## 🛠️ Tech Stack & DAX Used
- **Tool:** Power BI Desktop
- **Data Transformation:** Power Query
- **Key DAX Formulas:**
  ```dax
  Survival Rate = AVERAGE(titan_nic_codanics[Survived])
  ```
  ```dax
  FarePerYearOfAge = DIVIDE(titan_nic_codanics[Fare], titan_nic_codanics[age])
  ```

## 📂 Project Structure
- `titan_nic_codanics.pbix`: Main Power BI project file.
- `Titanic_Report.pdf`: Exported PDF version of the dashboard for quick viewing.
- `dataset.csv`: Raw data source used for the analysis.

---
*Developed by a passionate Data Analyst. Feel free to connect and review my work!*
