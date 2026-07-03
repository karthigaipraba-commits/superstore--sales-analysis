# Superstore Sales Analysis
**Tools:** Python | SQL (SQLite) | Tableau | pandas | matplotlib

## Project Overview
Analyzed 9,994 retail sales transactions to identify profit drivers, 
underperforming products, and top customers using Python, SQL, and Tableau.

## Business Questions Answered
- Which region generates the most profit?
- Which product categories are most/least profitable?
- Who are the top 10 customers by revenue?
- Which sub-categories are losing money despite high sales?

## Key Findings
- **West region** leads with $108,418 profit (14.9% margin)
- **Central region** underperforms — $501K sales but only $39K profit (7.9% margin)
- **Technology** averages $78.75 profit per order vs Furniture at $8.70
- **Tables sub-category** loses $17,725 despite $206K in sales
- **Sean Miller** is the top customer at $25,043 across 5 orders

## Dashboard
[View Live Tableau Dashboard](https://public.tableau.com/app/profile/karthika.vinoth/viz/SuperstoreSalesAnalysis_17830833667920/Dashboard1?publish=yes)

## Project Structure
- `01_load_data.py` — Loads CSV into SQLite database
- `02_sql_queries.py` — SQL analysis (5 business questions)
- `03_visualizations.ipynb` — Python charts (matplotlib/seaborn)

## How to Run
1. Clone this repository
2. Install dependencies: `pip3 install pandas matplotlib seaborn jupyter`
3. Run `01_load_data.py` first to create the database
4. Run `02_sql_queries.py` to see SQL analysis results
5. Open `03_visualizations.ipynb` in VS Code or Jupyter
