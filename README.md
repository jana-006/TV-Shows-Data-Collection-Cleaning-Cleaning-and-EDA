# 🎬 TV Shows Data Collection, Cleaning & Exploratory Data Analysis (EDA)

##  Project Overview
A complete Data Methodology pipeline focused on extracting, inspecting, cleaning, and analyzing real-world TV Shows data using a public REST API. The project demonstrates practical data engineering techniques by transforming messy, raw API responses into a clean, analysis-ready dataset.

---

##  Methodology & Project Tasks

1. Data Collection (API Integration):
   - Automated data extraction from a public TV Shows API using Python (`requests` library).
   - Structured raw JSON responses into flat relational formats.
2. Data Inspection & Quality Assessment:
   - Identified data quality issues, including missing values, incorrect data types, duplicated records, and inconsistent nested attributes.
3. Data Cleaning & Transformation:
   - Implemented systematic cleaning routines (handling nulls, parsing dates, converting numerical/categorical types).
   - Documented Before vs. After dataset metrics to quantify data quality improvements.
4. Exploratory Data Analysis (EDA) & Visualization:
   - Conducted univariate and bivariate analysis to uncover rating trends, genre distributions, runtime patterns, and release trends.

---

🛠️ Tech Stack & Tools
- Languages: Python
- APIs & Data Scraping: requests, RESTful APIs, JSON Parsing
- Data Manipulation: Pandas, NumPy
- Data Visualization: Matplotlib, Seaborn
- Environment: Jupyter Notebook

---

## Repository Deliverables
- TV_Shows_Pipeline.ipynb: Fully executed Jupyter Notebook containing API collection, cleaning logic, and EDA.
- raw_tv_shows.csv: Raw dataset extracted directly from the API.
- cleaned_tv_shows.csv: Final processed dataset ready for analysis.
