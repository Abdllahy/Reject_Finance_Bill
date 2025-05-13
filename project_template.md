# GenData Capstone Project Proposal

## Project Title  
**Public Response & Protest Patterns on Kenya’s Finance Bill (2024/2025)**



## Project Summary  
This project analyzes public reactions to Kenya’s 2024/2025 Finance Bill, focusing on protest events, social media sentiment, and economic grievances. Using **Excel, SQL, and Python**, the project will uncover protest hotspots, trending concerns, demographic indicators, and the role of social discourse.

The goal is to inform civil society, journalists, and policymakers by presenting data-driven insights on how fiscal policy impacts citizen behavior and triggers nationwide mobilization.



## Problem Statement  

- What were the major protest locations during the Finance Bill demonstrations?  
- How did sentiment on social media evolve over time?  
- What economic or policy concerns were raised most frequently?  
- Can we identify patterns in protest demographics, timing, or intensity?  
- How did protest discussions differ across regions?



## Technical Details

### Excel Components
**Concepts:**  
- Data Cleaning: Handling missing values, inconsistencies, duplicates  
- Transformation: Date grouping, protest categorization, calculated fields  
- Summarization: Pivot Tables, VLOOKUP for reference data  

**Visuals:**  
- Line graphs of protest frequency over time  
- Bar charts comparing counties  
- Pie charts for protest reasons  



### SQL Components
**Tool:** MySQL / SQLite  

**Key Concepts:**  
- `SELECT`, `JOIN`, `GROUP BY`, `ORDER BY`  
- Aggregations: `COUNT()`, `SUM()`, `AVG()`  
- Subqueries for advanced filtering  
- Views for cleaned and joined datasets  



### Python Components
**Libraries:** `pandas`, `matplotlib`, `seaborn` 

**Tasks:**  
- Data ingestion and merging  
- Sentiment analysis on tweets/posts  
- Time-series and categorical visualizations  
- Outlier detection, rolling trends  
- Word cloud generation  


## Report Writing

- Executive Summary with key findings  
- Methodology (tools, sources, assumptions)  
- Explanation of datasets  
- Visualizations with interpretation  
- Conclusions and recommendations  



## Program Structure

### 🔹 Core Features

1. **Data Collection**  
   - Social media hashtags  
   - News reports and government releases  
   - Manual protest logs  

2. **Preprocessing**  
   - Cleaning data in Excel  
   - Structuring in SQL  
   - Merging and refining in Python  

3. **Analysis**  
   - SQL trend queries  
   - Excel summaries  
   - Python graphs + sentiment analysis  

4. **Output**  
   - Final PDF report  
   - GitHub repository with code & data  
   - Jupyter notebook for reproducibility  



## Project Timeline

| Phase     | Tasks                                                 | Duration  |
|-----------|-------------------------------------------------------|-----------|
| Phase 1   | Define scope, collect protest and sentiment data      | 2 days    |
| Phase 2   | Clean and prepare data in Excel/SQL                   | 2 days    |
| Phase 3   | Analyze using SQL queries and Python scripts          | 2–3 days  |
| Phase 4   | Build graphs and perform sentiment analysis in Python | 2 days    |
| Phase 5   | Write final report and share findings                 | 2 days    |



## Design Principles

- Modular flow: Excel → SQL → Python  
- Consistent naming for files, tables, and graphs  
- Reusable code and views for scalability  
- Clear documentation for each phase  



## ⚠Potential Challenges

- Inconsistent or sparse protest data  
- Sentiment subjectivity or sarcasm in posts  
- Integration friction between tools  
- Biases in media coverage  



## Future Improvements

- Live scraping via APIs (Twitter, news)  
- Sentiment model refinement using machine learning  
- Integration of economic indicators like fuel price, inflation  
- Flask web app or dashboard for sharing visual insights  



##  Key Project Questions

1. What counties recorded the most protests?  
2. Which keywords and hashtags led online discussions?  
3. How did online sentiment shift around key parliamentary events?  
4. Are specific grievances more common in urban vs rural areas?  
5. Can we predict future protests from past data?  
6. Do protests follow any time patterns (weekends, paydays)?  
7. What economic indicators align with protest locations?  
8. Who are the most mentioned MPs or officials in the discourse?  
9. Are protests mostly youth-driven?  
10. How does social outrage convert to on-ground protest activity?

