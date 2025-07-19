\# 📊 Canada Cost of Living Analysis (2015–2024)



This project explores \*\*Canadian Consumer Price Index (CPI)\*\* trends between \*\*2015 and 2024\*\* using a full-stack data analytics approach. It demonstrates \*\*end-to-end analysis\*\* using \*\*Python\*\*, \*\*SQLite\*\*, and \*\*Power BI\*\*, covering everything from raw data ingestion to final dashboard visualization.



---



\## 🔍 Objective



To analyze how the cost of living has changed in Canada over the past decade by:



\- Identifying trends in various CPI categories (e.g., Food, Shelter, Transportation)

\- Understanding regional variations (if applicable)

\- Building an interactive dashboard for visual insights



---



\## 📁 Project Structure



```text

Canada-Cost-of-Living-Analysis/

│

├── data/                   # Raw and cleaned data files

│   └── cpi\_cleaned.csv

│

├── python/                 # Jupyter Notebooks for data processing and database loading

│   ├── CPI\_Data\_Loading.ipynb

│   └── CPI\_to\_SQL\_Loading.ipynb

│

├── powerbi/                # Final interactive dashboard

│   └── Cost\_of\_living.pbix

│

└── cpi\_database.sqlite     # SQLite database generated from cleaned data





---



\## 🛠️ Tools \& Technologies Used



| Tool       | Purpose                              |

|------------|---------------------------------------|

| Python     | Data cleaning using Pandas            |

| SQLite     | Lightweight database to store CPI     |

| SQL        | Querying data for analysis            |

| Power BI   | Dashboard creation and visualizations |

| GitHub     | Version control and portfolio sharing |



---



\## 🔄 Workflow Summary



\### 1. Data Cleaning \& Transformation  

\- Loaded the raw CPI data into Python  

\- Cleaned columns, handled missing/null values, filtered the date range  

\- Saved the cleaned data as `cpi\_cleaned.csv`



\### 2. SQL Database Creation  

\- Created an SQLite database called `cpi\_database.sqlite`  

\- Used `sqlite3` and Pandas to create a table and load the cleaned CSV data



\### 3. Power BI Dashboard  

\- Connected Power BI directly to the SQLite database  

\- Built a multi-page dashboard with:

&nbsp; - KPI cards for current CPI values

&nbsp; - Line charts to visualize YoY category trends

&nbsp; - Slicers for year and product category filtering

&nbsp; - Custom title, formatting, and professional layout



\### 4. Version Control with GitHub  

\- Created a local GitHub repo with proper folder structure  

\- Added all data files, notebooks, and dashboard  

\- Pushed the entire project to GitHub using GitHub Desktop



---



\## 📌 Key Skills Demonstrated



\- ✔ Real-world data wrangling and transformation

\- ✔ SQL integration with Python and BI tools

\- ✔ Building dynamic dashboards with filters and insights

\- ✔ Clear folder structure and portfolio presentation using GitHub



---



\## ✅ Project Status



| Task                         | Status |

|------------------------------|--------|

| Data cleaning in Python      | ✅ Done |

| SQL database creation        | ✅ Done |

| Power BI dashboard           | ✅ Done |

| GitHub repo upload           | ✅ Done |

| README documentation         | ✅ Done |



---



\## 💡 Future Enhancements \*(Optional)\*



\- Add region-level CPI breakdowns (e.g., by province or city)

\- Add inflation-adjusted income comparison

\- Create a dynamic dashboard using Python + Streamlit (web-based BI)



---



\## 📬 Contact



\*\*Ritika Goel\*\*  

\[LinkedIn Profile](https://www.linkedin.com/) \*https://www.linkedin.com/in/ritika-goel-966122139/\*  

---







