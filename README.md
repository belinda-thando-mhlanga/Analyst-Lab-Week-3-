# Superstore Advanced Analytics & Business Intelligence Dashboard

**Project:** Week 3 Data Analytics Internship Assignment  
**Organization:** AnalystLab Africa Consulting  
**Role:** Junior Business Intelligence Analyst  

## 📌 Project Overview
This project involves an advanced analysis of the Superstore Sales Dataset to design an interactive executive dashboard. The objective was to transition from basic data exploration to deep-dive business problem investigation, focusing on profitability, discounting impacts, regional underperformance, and seasonal trends[cite: 2]. 

## 🎯 Business Objectives
The primary goals of this project were to:
* Develop customized Key Performance Indicators (KPIs) and DAX measures to track business health[cite: 2].
* Identify and investigate specific areas of the business generating net losses[cite: 2].
* Perform time-based analysis to uncover seasonal sales trends[cite: 2].
* Build a fully interactive Microsoft Power BI dashboard for executive decision-makers[cite: 2].
* Deliver evidence-based, actionable recommendations to improve overall profitability[cite: 2].

## 🛠️ Tools & Technologies Used
* **Data Visualization & BI:** Microsoft Power BI (Interactive Dashboards, Power Query)
* **Data Modeling:** DAX (Data Analysis Expressions) for calculated measures
* **Version Control & Documentation:** Git, GitHub
* **Analysis Techniques:** Time-Series Analysis, Cohort Analysis (Discount Brackets), Geographic Performance Tracking

## 📊 Key Performance Indicators (KPIs) Developed
I created the following core KPIs using custom DAX measures[cite: 2]:
* **Total Sales:** $2.30M
* **Total Profit:** $286.40K
* **Total Orders:** 5,009
* **Profit Margin:** 12.47%
* **Average Sales per Order:** $458.61
* **Average Discount:** 15.62%

## 💡 Key Business Insights
Through advanced data analysis, I identified several critical business problems and trends:
1. **The Discounting Crisis:** There is a severe inverse relationship between discount size and profit margin. While 0% discounts yield a 29.5% margin, discounts exceeding 50% result in a massive net loss of -$76,559.
2. **Central Region Underperformance:** The Central region is the least profitable market segment, operating at a dismal 7.9% margin. This is driven by aggressive average discounting (24%).
3. **State-Level Liabilities:** Within the Central region, Texas (averaging a 37% discount rate) generated a net loss of -$25,729, making it the worst-performing state in the dataset.
4. **Product Line Failures:** The "Tables" sub-category is structurally unprofitable, generating over $206,000 in revenue but resulting in a net loss of -$17,725.
5. **High Seasonality:** Sales volume heavily spikes in Q4 (specifically November and December) and consistently suffers a severe slump in Q1 (February).

## 🚀 Strategic Recommendations
Based on the dashboard insights, I recommend management implement the following actions:
1. **Implement a strict 20% cap** on all discretionary discounts company-wide to stop profit erosion.
2. **Immediately suspend all promotional discounts** in Texas and Illinois to stabilize regional margins.
3. **Audit the supply chain and pricing model** for the "Tables" sub-category, or consider discontinuing it entirely.
4. **Front-load marketing budgets** into October to maximize the highly predictable Q4 sales rush.

## 📂 Repository Structure
* `Sample - Superstore.csv`: The raw dataset used for this analysis.
* `Superstore_Dashboard_Week3.pbix`: The final interactive Microsoft Power BI project file.
* `DAX_Measures.md`: Documentation of the custom formulas created for this project.
* `Business_Insights_Report.pdf`: The full executive summary and recommendations document.
* `/Images/`: Contains screenshots of the final interactive dashboard.

---
*This project was completed as part of the AnalystLab Africa Data Analytics Internship Programme.*
