# **Analysis of Hiring Trends & Talent Demand in the Indian Job Market 2025 Using SQL & Power BI**

## **Introduction**
The Indian job market is rapidly evolving, with increasing focus on skills, experience, and remote hiring. This project analyzes **hiring trends, talent demand, salary patterns, and remote work practices** using SQL and Power BI, providing actionable insights for recruiters, organizations, and job seekers.

## **Problem Statement**
Organizations often struggle to align hiring strategies with market realities due to fragmented data on roles, skills, salaries, and locations. This study provides a **data-driven solution** to support workforce planning and strategic hiring decisions.

## **Objective of Study**
- Analyze overall hiring activity and market health  
- Identify time-based hiring trends and seasonality  
- Assess talent demand across industries, roles, and skills  
- Examine salary patterns and experience-level trends  
- Compare remote and on-site hiring practices  
- Provide actionable recommendations for recruitment and workforce planning  

## **Scope of Study**
- Covers the Indian job market across industries, roles, and locations  
- Focuses on hiring trends, skill gaps, salary insights, and remote hiring patterns  
- Supports strategic recruitment, workforce planning, and talent acquisition  

## **Dataset Description**
- **Dataset Size:** 3,000 rows × 43 columns  
- **Base Table:** `Job_Market_Base`  
- **Calculation Tables (16):**  
  1. `Demand_vs_Salary`  
  2. `High_Pay_and_High_Demand`  
  3. `Hiring_Trends_Year`  
  4. `Hiring_Trends_Month_Year`  
  5. `Industry_Hiring`  
  6. `Industry_Talent_Demand`  
  7. `Location_Hiring`  
  8. `Market_Pressure`  
  9. `Opening_Trends_Window`  
  10. `Overview_Job_Opening`  
  11. `Ranked_Roles`  
  12. `Remote_Distribution`  
  13. `Remote_Role_Industry`  
  14. `Remote_Salary_Comparison`  
  15. `Salary_by_Experience`  
  16. `Salary_by_Job_Role`  
  17. `Skill_Demand`  

*(The above 16 calculation tables + 1 base table `Job_Market_Base` were used for data processing and analysis.)*

## **Tools & Technologies Used**
- **Data Cleaning & Analysis:** PostgreSQL (SQL, Views, Window Functions)  
- **Visualization:** Microsoft Power BI (Data Modeling, DAX, Interactive Dashboards)  
- **Data Handling & Preprocessing:** Microsoft Excel / CSV  
- **Version Control & Documentation:** GitHub  

## **Data Preparation and Cleaning Using SQL**
- Removed duplicates and handled missing/null values  
- Standardized job titles, industries, and locations  
- Converted experience levels into numeric formats  
- Validated salary ranges and eliminated invalid values  
- Created derived columns: quarter, season, demand index  
- Built **17 structured tables** (1 base + 16 calculation tables) to support analysis and dashboards  

## **Analysis Performed**
- **Exploratory Data Analysis (EDA):** Distribution of roles, skills, salaries, and experience  
- **Time-based Hiring Trends:** Monthly and yearly patterns, seasonal fluctuations  
- **Industry & Location Analysis:** High-demand sectors and regions  
- **Skill & Talent Demand Analysis:** Identifying in-demand skills and roles  
- **Salary & Experience Insights:** High-paying roles, experience-based salary trends  
- **Remote vs On-site Hiring Analysis:** Geographic and role-wise remote trends  
- **Advanced SQL Analysis:** Ranking roles, calculating demand index, window functions, and creating reporting views for dashboards
  
## **Power BI Dashboards**
Developed **5 interactive dashboards**:  

1. **Startup Hiring Overview & Market Health** – Total openings, average salary, demand index, market pressure  
2. **Hiring Trends Analysis (Year & Month)** – Monthly and seasonal hiring patterns  
3. **Talent Demand & Skill Intelligence** – High-demand roles, skill gaps, industry-wise talent needs  
4. **Salary & Experience Insights** – Compensation trends, high-paying roles, and demand alignment  
5. **Remote, Location & Industry Analysis** – Remote vs on-site hiring, geographic and industry distribution  

## **Insights**
- Hiring demand varies across roles, industries, and regions  
- Certain skills consistently remain high in demand across multiple sectors  
- Senior-level roles offer higher salaries, though demand does not always align with pay  
- Remote hiring constitutes a significant portion of opportunities  
- Market pressure and demand index highlight critical roles requiring immediate hiring focus  

## **Suggestions**
- Align hiring strategies with high-demand roles and skill requirements  
- Implement dynamic, seasonal recruitment planning  
- Focus on upskilling/reskilling to close talent gaps  
- Expand remote hiring to access broader talent pools  
- Regularly benchmark salaries and use performance-linked compensation for high-demand roles  

## **Conclusion**
This project demonstrates an **end-to-end data analytics workflow**, from SQL data cleaning and calculation table creation to **interactive Power BI dashboards**, providing actionable insights into hiring trends, talent demand, and workforce planning in the Indian job market.

## **Author**
**Lakshma**  
MBA | Aspiring Data Analyst  
**Skills:** SQL | Power BI | Data Analysis  
