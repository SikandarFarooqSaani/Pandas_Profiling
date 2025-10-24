# 🧾 Pandas Profiling

*(This response is AI generated except dataset and experience 🙂)*

---

## 📘 Objective
Learned how to perform automatic EDA (Exploratory Data Analysis) using **Pandas Profiling** — now called **ydata-profiling**.  
It performs **univariate and bivariate analysis** and generates an interactive HTML report.

---

## ⚙️ Steps Performed
- Imported pandas  
- Read dataset from repo  
- Installed profiling library  
  ```bash
  pip install ydata-profiling
from ydata_profiling import ProfileReport
profile = ProfileReport(df)
profile.to_file("report.html")



## 📊 Observations from Report

Explored multiple report sections:

Overview: Dataset summary and structure

Variables: Stats, distribution, and data types

Interactions: Relationships between features

Correlations: Strength between numeric columns

Missing Values: Visualization of null data

Samples: Random entries for inspection

Duplicate Rows: Found repeated data if any

## 💡 Experience

Got hands-on experience in automating EDA, quickly understanding dataset quality, patterns, and relationships using just one report.
