
# Chinook Digital Music Store - Sales Data Analysis 🎵📊

**Course:** MIS 443 - Business Data Management  
**Instructor:** Mr. Dang Thai Doan  
**Institution:** Eastern International University (Becamex Business School)  

## 👥 Team Members
* **Pham Hoang Phuc** (IRN: 2232300244)
* **Dang Ho Trung Hieu** (IRN: 2232300...)

## 📝 Project Overview
This repository contains the final project for the MIS 443 course. The objective of this project is to perform a comprehensive data analysis on the **Chinook Database** (a relational database simulating a global digital media store). 

By leveraging **PostgreSQL** for data extraction and **Python** for visualization, we aimed to uncover business trends regarding geographic revenue, year-over-year sales health, and customer product preferences. We also analyzed the business impact of a major UI update implemented in July 2023.

## 🛠️ Tech Stack & Methodology
* **Database:** PostgreSQL (Complex Joins, Aggregations, CTEs, Date/Time Intervals).
* **Data Visualization:** Python (Pandas, Matplotlib) via Jupyter Notebook.
* **Methodology:** Raw data was extracted and cleansed using SQL, then passed to Python to generate actionable visual insights.

## 📂 Repository Structure
* `Chinook_PostgreSql_Query.sql`: The SQL script containing all queries used for data extraction and aggregation.
* `Python_Chinook.ipynb`: The Jupyter Notebook containing the Python code for generating business charts.
* `Phúc_Hiếu_MIS443_final.pdf`: The comprehensive Business Analytics Report (including methodologies, visual charts, and strategic recommendations).
* `schema_chinook1.pgerd`: The Entity-Relationship Diagram (ERD) of the database.
* `PhucHieufinal.zip`: Compressed archive containing all project assets.

## 💡 Key Business Insights
1. **Geographic Dominance:** North America (USA & Canada) is the absolute profit center, generating the highest revenue.
2. **Product Preferences:** "Rock" is the foundational pillar of Chinook’s digital catalog, outperforming the second most popular genre (Latin) by more than double.
3. **Event Impact (Risk Assessment):** The July 2023 UI update negatively impacted the business, causing a significant ~22% drop in sustained medium-term sales. 

## 🚀 Strategic Recommendations
* Transition to a **Subscription-based model** (e.g., "Chinook VIP") to stabilize highly fluctuating year-over-year sales.
* Allocate licensing budgets heavily toward **Rock and Metal** genres.
* Rollback confusing UI features and implement in-app tutorials to recover from the recent sales drop.
