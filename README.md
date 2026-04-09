# 📊 Global Data Science Salary Insights (Python + Power BI)

## 🚀 Project Overview

This project analyzes global data science salaries using Python for data processing and Power BI for interactive dashboard visualization. The goal is to uncover key insights about salaries based on experience level, company size, job roles, and remote work trends.

---

## 🎯 Objectives

* Analyze salary distribution across different experience levels
* Compare salaries based on company size
* Identify top-paying job roles in data science
* Evaluate the impact of remote work on job distribution
* Explore salary differences across countries

---

## 🛠 Tools & Technologies

* 🐍 Python (Pandas, NumPy for data cleaning & analysis)
* 📊 Power BI (Dashboard & Visualization)
* 📁 CSV Dataset

---

## 🧠 Data Processing (Python)

The dataset was processed and cleaned using Python:

* Handling missing values
* Removing duplicates
* Converting salary to USD
* Feature engineering (experience level, remote ratio)

### Example Code:

```python id="pandas123"
import pandas as pd

df = pd.read_csv("data_science_salaries.csv")

# Data Cleaning
df.drop_duplicates(inplace=True)
df.fillna(0, inplace=True)

# Convert salary to USD (example)
df['salary_usd'] = df['salary_in_usd']

# Grouping
avg_salary = df.groupby('experience_level')['salary_usd'].mean()
print(avg_salary)
```

---

## 📊 Key Metrics

* 💰 Max Salary: $276K
* 📉 Min Salary: $16.23K
* 📊 Average Salary: $94.79K
* 🌍 Remote Jobs: 51.9%
* 🧾 Total Jobs: 32

---

## 📊 Dashboard Insights

### 👨‍💼 1. Salary by Experience Level

* Executive Level: ~$190K
* Senior Level: ~$110K
* Mid Level: ~$93K
* Entry Level: ~$54K

👉 **Insight:** Salary increases significantly with experience.

---

### 🏢 2. Salary by Company Size

* Large Companies: ~$109K
* Medium: ~$88K
* Small: ~$59K

👉 **Insight:** Bigger companies tend to pay higher salaries.

---

### 💼 3. Top Paying Roles

* Staff Machine Learning Engineer (~185K)
* Principal Data Scientist (~174K)
* ML Engineer (~174K)

👉 **Insight:** Advanced AI/ML roles dominate high salaries.

---

### 🌍 4. Remote Work Distribution

* 100% Remote: ~52%
* Hybrid: ~39%
* On-site: ~9%

👉 **Insight:** Remote work is dominant in data science roles.

---

### 🗺️ 5. Salary by Location

* Higher salaries in North America & Europe
* Lower salaries in other regions

👉 **Insight:** Location significantly impacts salary.

---

## ⚠️ Business Insights / Problems

* Entry-level salaries are relatively low
* Salary gap between small and large companies
* Geographic inequality in salaries
* Limited number of job records (small dataset)

---

## 💡 Recommendations

* 🎓 Focus on skill development to reach senior/executive levels
* 🌍 Target global/remote opportunities for higher salaries
* 🏢 Prefer larger companies for better compensation
* 🤖 Specialize in AI/ML roles for top earnings

---

## 📷 Dashboard Preview

<img width="923" height="564" alt="Dashboard (2)" src="https://github.com/user-attachments/assets/abc6767b-ac5d-49b0-b682-8c3c813e7d45" />


---

## 📎 How to Use

1. Run Python script for data cleaning
2. Load processed data into Power BI
3. Explore filters (year, experience, company size)
4. Analyze trends and insights

---

## 📢 Conclusion

This project highlights how Python and Power BI can be combined to analyze salary trends and provide valuable insights for job seekers and businesses in the data science field.

---

## 👤 Author

**Omar Diaa**
Aspiring Data Analyst
