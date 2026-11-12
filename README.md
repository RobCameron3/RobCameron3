
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:071525,50:123C57,100:087F8C&height=150&section=header&text=Hello,%20I'm%20Robert%20Cameron%20%F0%9F%91%8B&fontColor=FFFFFF&fontSize=29&fontAlignY=40&animation=fadeIn" width="100%" alt="Robert Cameron"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=17&duration=2600&pause=1200&color=20B8C3&center=true&vCenter=true&width=800&height=50&lines=I+build+business+intelligence+solutions.;I+improve+data+quality+and+efficiency.;I+turn+data+into+better+business+decisions.;I+transform+analytics+into+business+value." alt="Animated professional introduction"/>

</div>

<table>
<tr>
<td width="28%" align="center" valign="middle">

<h1>🎓</h1>

<img src="https://img.shields.io/badge/UMASS-AMHERST-881C1C?style=for-the-badge" alt="UMass Amherst"/>

<br/><br/>

<strong>MASTER OF SCIENCE</strong>

<br/><br/>

<strong>BUSINESS ANALYTICS</strong>

<br/><br/>

Isenberg School of Management

<br/><br/>

Class of 2023

</td>
<td width="72%" valign="middle">

<h2>Robert J. Cameron</h2>

<h3>Business Intelligence & Data Analyst</h3>

Business intelligence professional with nearly three years of experience in data integration, reporting, operational analytics, and workflow automation.

I transform fragmented datasets into reliable insights that help businesses improve efficiency, strengthen decision-making, and generate measurable value.

<br/><br/>

<a href="https://www.linkedin.com/in/robertjcameron-">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

<a href="https://github.com/RobCameron3">
<img src="https://img.shields.io/badge/GitHub-Portfolio-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
</a>

</td>
</tr>
</table>

---

## 💼 Professional Experience & Business Impact

### Financial / Data Analyst | Solmetex
**April 2024 – October 2026**

Worked with distributor, customer, and CRM datasets to improve data quality, customer identification, and operational reporting.

| Business Challenge | Solution | Business Impact |
|:---|:---|:---|
| Customer records could not consistently be matched to existing CRM accounts | Developed Python fuzzy-matching and data-standardization workflows | Improved customer identification from approximately **60% to 80–90%** |
| Large volumes of customer records required manual investigation | Analyzed unmatched records and validated customer relationships | Resolved **648 of 877 records (73.9%)** in a targeted review |
| Distributor data was fragmented across separate spreadsheets | Consolidated and standardized **17 distributor workbooks** | Improved cross-distributor analysis and data-quality review |
| Inconsistent customer information complicated reporting | Standardized customer names, addresses, and account relationships | Improved data reliability and reduced manual matching effort |

---

## 🚀 Featured Analytics Projects

### 🏀 01 | NBA Four-Factor Modeling & Team Performance Analytics

**Understanding what drives winning in basketball through statistical analysis.**

<img src="assets/nba_three_point_split.svg" width="100%" alt="Animated NBA Four Factors comparison showing shooting efficiency, turnovers, offensive rebounds, free-throw rate, and the overall Team A versus Team B result"/>

The animated dashboard demonstrates how **Dean Oliver's Four Factors** can be used to compare basketball teams across four key performance measures.

Each metric includes a basketball animation illustrating the underlying action, its statistical formula, and a head-to-head comparison between Team A and Team B.

#### The Four Factors Explained

**1. Effective Field Goal Percentage (eFG%) — Shooting Efficiency**

Measures shooting efficiency while accounting for the additional value of three-point field goals.

- The animation illustrates a three-point shot entering the basket.
- A made three-pointer receives an additional 0.5 field-goal credit in the calculation.
- **Higher eFG% indicates better shooting efficiency.**

`eFG% = (FGM + 0.5 × 3PM) / FGA`

**2. Turnover Percentage (TOV%) — Ball Security**

Estimates the percentage of possessions ending in turnovers.

- The animation illustrates a defender taking possession of the basketball.
- Turnovers represent lost scoring opportunities.
- **Lower TOV% indicates better ball security.**

`TOV% = TOV / (FGA + 0.44 × FTA + TOV)`

**3. Offensive Rebound Percentage (ORB%) — Second-Chance Opportunities**

Measures the proportion of available offensive rebounds secured by a team.

- The animation illustrates a missed shot followed by an offensive rebound.
- Recovering missed shots creates additional scoring opportunities.
- **Higher ORB% indicates stronger offensive rebounding performance.**

`ORB% = ORB / (ORB + Opponent DRB)`

**4. Free Throw Rate (FT/FGA) — Free-Throw Production**

Measures made free throws relative to field-goal attempts.

- The animation illustrates a successful free throw.
- The metric captures free-throw scoring production relative to field-goal volume.
- **Higher FT/FGA indicates greater made free-throw production per field-goal attempt.**

`FT/FGA = FTM / FGA`

#### Team A vs. Team B — Overall Comparison

The visualization compares the two teams across all four factors and highlights which team performs better in each category.

| Four Factor | Team A | Team B | Advantage |
|:---|---:|---:|:---|
| Effective FG% | 55.2% | 52.1% | Team A |
| Turnover % | 12.4% | 14.1% | Team A |
| Offensive Rebound % | 28.6% | 31.2% | Team B |
| Free Throw Rate | 19.8% | 17.5% | Team A |
| **Factors Won** | **3 of 4** | **1 of 4** | **Team A** |

**Overall illustrative result:** Team A leads in three of the four statistical categories.

This comparison demonstrates how different dimensions of basketball performance can be evaluated together rather than relying on points scored alone.

The factor count is a descriptive comparison, **not a predicted win probability or a weighted model score**. A predictive model would require historical game data, fitted coefficients, and performance validation.

**Tools:** Python · Pandas · Statistical Analysis · Predictive Modeling

**[Explore NBA Four-Factor Modeling](https://github.com/RobCameron3/nba-four-factor-modeling)**

<sub>Team A and Team B statistics are illustrative examples, not actual NBA team results. Basketball animations conceptually demonstrate the statistical formulas.</sub>

---

### ⚙️ 02 | Python Customer Identification & Automation

**Transforming fragmented customer records into reliable business intelligence.**

<img src="assets/customer-matching.svg" width="100%" alt="Animated Python workflow showing record cleaning, fuzzy matching, confidence scoring, and CRM validation"/>

Developed Python-based matching workflows to identify customer accounts across distributor datasets and CRM records.

The workflow demonstrates how incoming customer data moves through several stages:

1. **Data ingestion:** Read incoming distributor records.
2. **Standardization:** Clean and normalize names, addresses, and other identifying fields.
3. **Candidate matching:** Compare records against potential CRM accounts using fuzzy matching.
4. **Validation:** Review similarity scores and verify candidate relationships.
5. **Business outcome:** Improve customer identification and reduce manual investigation.

**Measured professional result:** Increased customer identification from approximately **60% to 80–90%**.

**Tools:** Python · Pandas · Fuzzy Matching · Data Cleaning · CRM Integration

<sub>Professional work example. Animation is a conceptual representation of the matching workflow.</sub>

---

### 🕵️ 03 | SQL Data Breach Investigation

**Connecting fragmented evidence to identify the responsible record.**

<img src="assets/sql-investigation.svg" width="100%" alt="Animated SQL investigation with three cards flipping to reveal incorrect matches and the identified record"/>

Investigated a simulated data breach using SQL queries to examine records and uncover relationships across datasets.

The animation represents the investigation as a sequence of candidate checks: two incorrect matches are ruled out before the matching record is revealed.

**Analytical methods:**
- SQL joins to connect related records.
- Filtering to narrow potential matches.
- Relational analysis to investigate suspicious activity.
- Query validation to establish the matching relationship.

**Tools:** PostgreSQL · SQL · Joins · Data Investigation

**[Explore SQL Investigation](https://github.com/RobCameron3/sql-data-breach-investigation)**

---

### 📊 04 | Power BI Operational Performance & Logistics

**Turning operational data into actionable KPIs.**

<img src="assets/power-bi-performance.gif" width="100%" alt="Animated operational KPI dashboard showing business performance metrics"/>

Developed an interactive business intelligence dashboard analyzing operational and commercial performance.

**Analytical focus:**
- Revenue and operational KPI monitoring.
- Shipment and logistics trends.
- Regional performance comparisons.
- Subscription and business activity analysis.
- Interactive filtering and reporting.

**Tools:** Power BI · Power Query · DAX · Data Visualization

**[Explore Operational Logistics Dashboard](https://github.com/RobCameron3/power-bi-operational-logistics-dashboard)**

---

### 🌎 05 | Geographic Density & Trend Analytics

**Understanding where business activity is concentrated.**

<img src="assets/geographic-density.gif" width="100%" alt="Animated geographic density visualization showing regional activity patterns"/>

Built a Power BI analytics project examining geographic density and trends over time.

The visualization illustrates how regional activity can be compared to identify geographic concentrations and changing patterns.

**Tools:** Power BI · Power Query · DAX · Geographic Analytics

**[Explore Geographic Density Analytics](https://github.com/RobCameron3/power-bi-geographic-density-analytics)**

---

### 📉 06 | Telecommunications Customer Churn Prediction

**Identifying customers who may be at risk of leaving.**

<img src="assets/customer-churn.gif" width="100%" alt="Animated customer churn risk segmentation visualization"/>

Developed a predictive classification model to analyze customer characteristics and identify potential churn risk.

**Analytical focus:**
- Customer behavior and retention patterns.
- Data preparation and feature analysis.
- Classification modeling.
- Risk segmentation and model evaluation.

**Tools:** Python · Pandas · Classification · Predictive Analytics

**[Explore Telecom Churn Prediction](https://github.com/RobCameron3/Telco_Churn_Prediction)**

---

### 🚗 07 | Used Car Price Prediction

**Estimating vehicle prices using statistical modeling.**

<img src="assets/used-car-regression.gif" width="100%" alt="Animated regression visualization showing predicted used-car prices"/>

Developed a regression-based analytics project examining the relationship between vehicle characteristics and used-car prices.

**Analytical focus:**
- Data cleaning and exploratory analysis.
- Feature relationships and pricing trends.
- Regression modeling.
- Predicted versus actual price evaluation.

**Tools:** Python · Pandas · Regression · Predictive Modeling

**[Explore Used Car Price Prediction](https://github.com/RobCameron3/Used_Car_Price_Prediction)**

---

## 🛠️ Technical Skills

### Business Intelligence & Reporting

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Advanced_Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square)
![Power Query](https://img.shields.io/badge/Power_Query-217346?style=flat-square)
![DAX](https://img.shields.io/badge/DAX-0878D1?style=flat-square)
![Power Pivot](https://img.shields.io/badge/Power_Pivot-217346?style=flat-square)

### Programming & Data Analysis

<img src="https://skillicons.dev/icons?i=python,r,postgres,mysql,azure,git,github,vscode" alt="Programming and development tools"/>

<br/>

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-3776AB?style=flat-square)
![Requests](https://img.shields.io/badge/Requests-3776AB?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

### Databases & Enterprise Systems

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Azure SQL](https://img.shields.io/badge/Azure_SQL-0078D4?style=flat-square)
![Access](https://img.shields.io/badge/Microsoft_Access-A4373A?style=flat-square)
![Dynamics 365](https://img.shields.io/badge/Dynamics_365-002050?style=flat-square)
![SAP BW](https://img.shields.io/badge/SAP_BW-0FA6D4?style=flat-square)
![SAP BusinessObjects](https://img.shields.io/badge/SAP_BusinessObjects-0FA6D4?style=flat-square)
![NetSuite](https://img.shields.io/badge/NetSuite-1B365D?style=flat-square)

### Data Integration, Analytics & Automation

![Data Integration](https://img.shields.io/badge/Data_Integration-5865F2?style=flat-square)
![ETL](https://img.shields.io/badge/ETL-5865F2?style=flat-square)
![Fuzzy Matching](https://img.shields.io/badge/Fuzzy_Matching-5865F2?style=flat-square)
![Data Cleaning](https://img.shields.io/badge/Data_Cleaning-5865F2?style=flat-square)
![Workflow Automation](https://img.shields.io/badge/Workflow_Automation-5865F2?style=flat-square)
![KPI Reporting](https://img.shields.io/badge/KPI_Reporting-008B8B?style=flat-square)
![Statistics](https://img.shields.io/badge/Statistical_Analysis-008B8B?style=flat-square)
![Regression](https://img.shields.io/badge/Regression-008B8B?style=flat-square)
![Classification](https://img.shields.io/badge/Classification-008B8B?style=flat-square)
![Predictive Modeling](https://img.shields.io/badge/Predictive_Modeling-008B8B?style=flat-square)

---

<div align="center">

### Turning Data Into Decisions. Decisions Into Business Value.

</div>
