# ⚽ "Moneyball" Data Analysis

This project presents a full end-to-end analysis pipeline applied to football player data extracted from a Football Manager save. 
It showcases how SQL and Python can be used for scouting, performance analysis, and player comparison in a structured and repeatable manner.

## 📊 Overview

- **Dataset Source**: Exported from Football Manager
- **Tools Used**: MySQL Workbench, Python (pandas, matplotlib), Datawrapper
- **Focus Areas**:
  - Top player and club performance analysis
  - Under-21 scouting
  - Goals vs xG efficiency
  - Positional aging trends
  - Practical use-case: striker replacement analysis

## 📄 Key Insights

- **Top Goal Scorers**: Identified elite scorers and their over-performance
- **xG Analysis**: Differentiated clinical finishers from inefficient strikers
- **U21 Standouts**: Highlighted future stars and early high-raters
- **Aging by Position**: Defensive lines tend to have older averages
- **Club Performance**: Some clubs excel through individual stars, others through overall squad quality
- **Real Scenario Use**: Used SQL to scout a striker replacement based on key attribute similarity

## 🛠️ How to Reproduce

1. Import `players_data_raw.csv` into MySQL
2. Run SQL queries from the `SQL` section of the `.docx` report
3. Use Python to visualize outputs (see code in notebook or repo)
4. Use visual insights for scouting/recruitment decisions

## 🗺️ Nationality Map

A choropleth map was created externally using Datawrapper to visualize nationality distribution.
