# 📊 Canada Cost of Living Analysis (2015–2024)

**A full-stack data analytics project** analyzing Canadian Consumer Price Index (CPI) trends from 2015 to 2024 using **Python**, **SQLite**, **SQL**, and **Power BI** — tailored for the Canadian data industry.

---

## 🎯 Objective

Analyze how Canada's cost of living has changed over the past decade by:
- Tracking CPI growth across categories like **Food**, **Shelter**, and **Transportation**
- Identifying major inflation trends and their impacts
- Building an interactive dashboard for business-ready insights

---

## 🧱 Project Structure

```text
Canada-Cost-of-Living-Analysis/
│
├── data/
│   └── cpi_cleaned.csv                  # Cleaned CPI data
│
├── python/
│   ├── CPI_Data_Loading.ipynb           # Data cleaning in Python
│   └── CPI_to_SQL_Loading.ipynb         # SQLite database creation
│
├── powerbi/
│   └── Cost_of_living.pbix              # Power BI dashboard file
│
├── cpi_database.sqlite                  # Final SQLite database
└── README.md                            # Project documentation
```

---

## 🛠️ Tools & Technologies Used

| Tool       | Purpose                                |
|------------|-----------------------------------------|
| **Python** | Data cleaning with Pandas               |
| **SQLite** | Lightweight database to store CPI       |
| **SQL**    | Data querying and aggregation           |
| **Power BI** | Visual analytics & dashboard building |
| **GitHub** | Project version control and hosting     |

---

## 🔄 Workflow Summary

### 1. Data Cleaning & Preparation
- Raw CSV cleaned using **Pandas**
- Filtered years 2015–2024, handled nulls, standardized columns
- Saved cleaned data as `cpi_cleaned.csv`

### 2. Database Integration
- Created SQLite DB using `sqlite3` in Python
- Exported cleaned data into table format
- Verified schema & queried sample results

### 3. Power BI Dashboard
- Connected directly to `cpi_database.sqlite`
- Designed multi-page dashboard including:
  - 📌 KPI Cards (CPI % Change, Total CPI)
  - 📈 Year-over-Year trends (line charts)
  - 🎯 Slicers for Product, Year, and Category
  - 📅 Monthly & Annual Analysis

### 4. GitHub Version Control
- Created a structured local repository
- Synced all files using **GitHub Desktop**
- Wrote clean, professional `README.md`

---

## 📸 Dashboard Snapshot

*(Upload a screenshot to your GitHub repo and link here)*  
Example:

> ![Dashboard Preview](powerbi/dashboard_preview.png)

---

## ✅ Project Status

| Component               | Status |
|------------------------|--------|
| Python Cleaning        | ✅ Done |
| SQLite + SQL Queries   | ✅ Done |
| Power BI Dashboard     | ✅ Done |
| GitHub Repo Structure  | ✅ Done |
| Final README           | ✅ Done |

---

## 🧠 Key Learnings

- Building end-to-end data projects like real-world analysts
- Structuring project files for clarity and teamwork
- Turning raw government data into decision-ready dashboards
- Using GitHub professionally to showcase work

---

## 🚀 Future Scope

- Add inflation-adjusted income comparison
- Use Streamlit for a web dashboard alternative
- Integrate open API for real-time CPI updates

---

## 🙋 About Me

**Ritika Goel**  
📍 Toronto, ON  
[🔗 LinkedIn](https://www.linkedin.com/in/ritika-goel-966122139/)  
💼 Aspiring Data Analyst | Passionate about impactful dashboards & storytelling with data

---
