<p align="center">
  <img src="./Screenshot%202026-09-04%20184614.png" alt="Beacon Innovation Hub Logo" width="100%" height="500">
</p> Innovation Hub

Your project description goes here...
# 📊 BIH Data Analyst Journey

<p align="center">

**Learning by Doing • Building by Solving • Growing into a Data Analyst**

</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)
![Database](https://img.shields.io/badge/Database-336791?style=for-the-badge\&logo=postgresql\&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)

</p>

---

# 📖 About

This repository documents my journey through the **Beacon Innovation Hub Data Analyst Pathway**.

The purpose of this repository is to document not only what I learn, but also **how I learn, how I apply concepts, the problems I solve, the mistakes I make, and how my analytical thinking develops over time.**

The pathway takes me from foundational data analysis toward the ability to independently work on an end-to-end data analytics project.

The core principle behind this repository is:

> **Don't just learn the tool. Learn how to use the tool to solve a problem.**

---

# 🎯 My Goal

My goal is to develop the skills required to become a **job-ready Junior Data Analyst**.

I want to be able to take a real-world organisational problem and move through the complete analytical process:

```mermaid
flowchart LR

A["💡 BUSINESS<br/>PROBLEM"]
--> B["❓ ANALYTICAL<br/>QUESTIONS"]

B --> C["📊 DATA"]

C --> D["🧹 PREPARATION<br/>& VALIDATION"]

D --> E["🔎 ANALYSIS"]

E --> F["📈 VISUALIZATION"]

F --> G["🧠 INTERPRETATION"]

G --> H["💡 RECOMMENDATIONS"]

H --> I["🎯 DECISION<br/>SUPPORT"]
```

The objective is not simply to produce charts or SQL queries.

The objective is to turn **trustworthy data into useful information that can support better decisions.**

---

# 🧠 My Learning Philosophy

I am following a **learning-by-doing** approach.

I don't want to simply watch tutorials and copy what the instructor does.

Instead, I follow this process:

```mermaid
flowchart LR

A["🎥 WATCH"]
--> B["⏸️ PAUSE"]

B --> C["⌨️ RECREATE"]

C --> D["🔧 MODIFY"]

D --> E["🧩 SOLVE A<br/>BIH PROBLEM"]

E --> F["📚 CONSULT<br/>DOCUMENTATION"]

F --> G["🧠 UNDERSTAND"]

G --> H["🚀 BUILD"]

H --> I["📝 DOCUMENT"]

I --> A
```

### My rule

**Watch it → Recreate it → Change it → Break it → Fix it → Apply it → Understand it → Document it.**

---

# 📚 BIH Data Analyst Pathway

My journey is organised into five levels.

```mermaid
flowchart TD

A["📊 BIH DATA ANALYST<br/>JOURNEY"]

A --> L1["📘 LEVEL 1<br/>Data Analytics Foundations"]

A --> L2["📗 LEVEL 2<br/>SQL & Statistical Analysis"]

A --> L3["📙 LEVEL 3<br/>Pathway Content<br/>To Be Added"]

A --> L4["📕 LEVEL 4<br/>Business Analytics &<br/>Communication"]

A --> L5["🏆 LEVEL 5<br/>Junior Data Analyst<br/>Readiness & Capstone"]

L1 --> L1A["Data Understanding"]
L1 --> L1B["Data Quality"]
L1 --> L1C["Exploratory Analysis"]
L1 --> L1D["Spreadsheet Analysis"]

L2 --> L2A["SQL"]
L2 --> L2B["Relational Data"]
L2 --> L2C["Statistics"]
L2 --> L2D["Analytical Reasoning"]

L3 --> L3A["Learning"]
L3 --> L3B["Practice"]
L3 --> L3C["Projects"]

L4 --> L4A["KPIs"]
L4 --> L4B["Dashboards"]
L4 --> L4C["Data Storytelling"]
L4 --> L4D["Management Communication"]

L5 --> L5A["Business Problem"]
L5 --> L5B["Data Preparation"]
L5 --> L5C["SQL & Statistics"]
L5 --> L5D["BI Report"]
L5 --> L5E["Findings & Recommendations"]
```

---

# 📘 Level 1 — Data Analytics Foundations

**Focus:** Building reliable analytical foundations.

The first level focuses on understanding how analysts frame questions, inspect data, identify quality problems, perform exploratory analysis, and use spreadsheets to produce reliable summaries.

### Key areas

* Business questions
* Data understanding
* Data quality
* Missing values
* Duplicate records
* Invalid data types
* Inconsistent categories
* Data cleaning
* Cleaning documentation
* Descriptive summaries
* Group comparisons
* Excel / spreadsheet analysis
* PivotTables
* PivotCharts
* Basic dashboards
* Evidence vs unsupported conclusions

### Analyst workflow

```mermaid
flowchart LR

A["Business Question"]
--> B["Data"]

B --> C["Investigation"]

C --> D["Preparation"]

D --> E["Analysis"]

E --> F["Visualization"]

F --> G["Interpretation"]

G --> H["Recommendation"]

H --> I["Decision Support"]
```

### Level 1 structure

```text
Level-1-Data-Analytics-Foundations/
│
├── datasets/
│   └── bih_data_analyst_practice.csv
│
├── excel/
│   └── level1_analysis.xlsx
│
├── analysis/
│   ├── data-understanding.md
│   ├── cleaning-log.md
│   └── findings.md
│
├── visuals/
│   ├── charts/
│   └── dashboards/
│
└── README.md
```

---

# 📗 Level 2 — SQL & Statistical Analysis

**Focus:** Moving from single-file analysis toward relational data and statistical reasoning.

### Key areas

* SQL fundamentals
* Filtering
* Aggregation
* `GROUP BY`
* `CASE`
* Joins
* Join validation
* Subqueries
* CTEs
* Window functions
* Descriptive statistics
* Distributions
* Skewness
* Outliers
* Covariance
* Correlation
* Population vs sample
* Sampling
* Sampling bias
* Confidence intervals
* Association vs causation
* Statistical reasoning

### Level 2 analytical workflow

```mermaid
flowchart TD

A["🗄️ RELATIONAL DATA"]

A --> B["SQL QUERY"]

B --> C["FILTER"]

C --> D["AGGREGATE"]

D --> E["JOIN"]

E --> F["VALIDATE"]

F --> G["STATISTICAL ANALYSIS"]

G --> H["INTERPRET"]

H --> I["BUSINESS CONCLUSION"]
```

### Level 2 structure

```text
Level-2-SQL-Statistics/
│
├── datasets/
│
├── sql/
│   ├── basic-queries.sql
│   ├── aggregation.sql
│   ├── joins.sql
│   ├── join-validation.sql
│   └── advanced-analysis.sql
│
├── statistics/
│   ├── descriptive-statistics.md
│   ├── distributions.md
│   ├── correlation.md
│   └── sampling.md
│
├── exercises/
│
├── outputs/
│
└── README.md
```

---

# 📙 Level 3 — Data Analysis

> **Level 3 details will be documented here as I progress through the official BIH pathway content.**

### Planned repository area

```text
Level-3-Data-Analysis/
│
├── datasets/
│
├── notebooks/
│
├── analysis/
│
├── exercises/
│
├── outputs/
│
└── README.md
```

---

# 📕 Level 4 — Business Analytics & Communication

**Focus:** Converting technically correct analysis into useful management information.

At this stage, the focus moves beyond simply analysing data toward answering:

> **What does this information mean for the organisation?**

### Key areas

* Metrics
* KPIs
* Leading indicators
* Lagging indicators
* KPI formulas
* KPI limitations
* Visualization selection
* Dashboard hierarchy
* Dashboard design
* Pattern interpretation
* Uncertainty
* Evidence vs interpretation
* Recommendations
* Management briefs
* Data storytelling
* Communicating with non-technical stakeholders

### Data storytelling framework

```mermaid
flowchart LR

A["📊 EVIDENCE"]
--> B["🔎 PATTERN"]

B --> C["🧠 INTERPRETATION"]

C --> D["⚠️ LIMITATION"]

D --> E["💡 RECOMMENDATION"]
```

### KPI development

```mermaid
flowchart TD

A["Business Objective"]
--> B["What should be measured?"]

B --> C["Define KPI"]

C --> D["Create Formula"]

D --> E["Define Purpose"]

E --> F["Identify Limitations"]

F --> G["Monitor"]

G --> H["Interpret"]

H --> I["Recommend Action"]
```

### Level 4 structure

```text
Level-4-Business-Analytics/
│
├── kpis/
│   ├── community-growth.md
│   ├── engagement.md
│   ├── skills-development.md
│   ├── project-participation.md
│   ├── project-completion.md
│   └── technical-performance.md
│
├── dashboards/
│   └── BIH-dashboard/
│
├── reports/
│   └── management-brief.md
│
├── storytelling/
│   └── findings.md
│
└── README.md
```

---

# 🏆 Level 5 — Junior Data Analyst Readiness & Capstone

**Focus:** Demonstrating independent, end-to-end data analyst competence.

The final stage brings together the skills developed throughout the pathway.

### End-to-end process

```mermaid
flowchart TD

A["💡 BUSINESS<br/>UNDERSTANDING"]

A --> B["👥 STAKEHOLDERS"]

B --> C["📊 DATA<br/>ACQUISITION"]

C --> D["🧹 CLEANING<br/>& TRANSFORMATION"]

D --> E["✅ VALIDATION"]

E --> F["🗄️ SQL"]

F --> G["📐 STATISTICS"]

G --> H["🧠 ANALYTICAL<br/>MODEL"]

H --> I["📊 POWER BI"]

I --> J["🔎 FINDINGS"]

J --> K["⚠️ LIMITATIONS"]

K --> L["💡 RECOMMENDATIONS"]

L --> M["🎯 DECISION<br/>SUPPORT"]
```

---

# 🏢 BIH Community Performance Analysis

### Capstone Business Question

> **How effectively is Beacon Innovation Hub engaging participants, developing technical skills, and supporting project activity?**

The capstone will bring together:

* Business understanding
* Data preparation
* Data validation
* SQL
* Statistics
* Data modelling
* Power BI
* KPIs
* Findings
* Recommendations
* Professional communication

---

## 📊 Capstone Dashboard

The final Power BI report will be organised around decision-focused pages.

```mermaid
flowchart TD

A["📊 BIH COMMUNITY<br/>PERFORMANCE DASHBOARD"]

A --> B["🏠 EXECUTIVE<br/>OVERVIEW"]

A --> C["👥 TEAM<br/>PERFORMANCE"]

A --> D["📈 PARTICIPANT<br/>ENGAGEMENT"]

A --> E["🚀 PROJECT<br/>ANALYSIS"]

B --> B1["KPIs"]
B --> B2["Key Findings"]

C --> C1["Team Comparison"]
C --> C2["Performance"]

D --> D1["Attendance"]
D --> D2["Task Completion"]
D --> D3["Training Activity"]

E --> E1["Projects"]
E --> E2["Completion"]
E --> E3["Participation"]
```

---

# 📁 Complete Repository Structure

The complete repository will follow this structure:

```text
BIH-Data-Analyst-Journey/
│
├── 📘 Level-1-Data-Analytics-Foundations/
│   │
│   ├── datasets/
│   │   └── bih_data_analyst_practice.csv
│   │
│   ├── excel/
│   │   └── level1_analysis.xlsx
│   │
│   ├── analysis/
│   │   ├── data-understanding.md
│   │   ├── cleaning-log.md
│   │   └── findings.md
│   │
│   ├── visuals/
│   │   ├── charts/
│   │   └── dashboards/
│   │
│   └── README.md
│
├── 📗 Level-2-SQL-Statistics/
│   │
│   ├── datasets/
│   │
│   ├── sql/
│   │   ├── basic-queries.sql
│   │   ├── filtering.sql
│   │   ├── aggregation.sql
│   │   ├── joins.sql
│   │   ├── join-validation.sql
│   │   └── advanced-analysis.sql
│   │
│   ├── statistics/
│   │   ├── descriptive-statistics.md
│   │   ├── distributions.md
│   │   ├── correlation.md
│   │   └── sampling.md
│   │
│   ├── exercises/
│   │
│   ├── outputs/
│   │
│   └── README.md
│
├── 📙 Level-3-Data-Analysis/
│   │
│   ├── datasets/
│   ├── notebooks/
│   ├── analysis/
│   ├── exercises/
│   ├── outputs/
│   └── README.md
│
├── 📕 Level-4-Business-Analytics/
│   │
│   ├── kpis/
│   ├── dashboards/
│   ├── reports/
│   ├── storytelling/
│   ├── exercises/
│   └── README.md
│
├── 🏆 Level-5-Capstone/
│   │
│   ├── data/
│   │   ├── raw/
│   │   └── cleaned/
│   │
│   ├── sql/
│   │   └── analysis.sql
│   │
│   ├── notebooks/
│   │   └── analysis.ipynb
│   │
│   ├── power-bi/
│   │   └── BIH-dashboard.pbix
│   │
│   ├── outputs/
│   │   ├── charts/
│   │   └── reports/
│   │
│   ├── findings/
│   │   └── findings.md
│   │
│   ├── recommendations/
│   │   └── recommendations.md
│   │
│   └── README.md
│
├── 🖼️ assets/
│   ├── images/
│   ├── screenshots/
│   └── diagrams/
│
└── 📄 README.md
```

---

# 🗺️ Repository Architecture

The entire repository can be viewed as:

```mermaid
flowchart TD

ROOT["📊 BIH DATA ANALYST JOURNEY"]

ROOT --> L1["📘 LEVEL 1"]
ROOT --> L2["📗 LEVEL 2"]
ROOT --> L3["📙 LEVEL 3"]
ROOT --> L4["📕 LEVEL 4"]
ROOT --> L5["🏆 LEVEL 5"]

L1 --> L1D["📂 Data<br/>Foundations"]
L1 --> L1E["📊 Excel"]
L1 --> L1A["🔎 Analysis"]

L2 --> L2S["🗄️ SQL"]
L2 --> L2ST["📐 Statistics"]
L2 --> L2A["🔎 Analysis"]

L3 --> L3N["📓 Notebooks"]
L3 --> L3D["📊 Data"]
L3 --> L3A["🔎 Analysis"]

L4 --> L4K["🎯 KPIs"]
L4 --> L4P["📊 Power BI"]
L4 --> L4R["📝 Reports"]

L5 --> L5D["📊 Data"]
L5 --> L5S["🗄️ SQL"]
L5 --> L5N["📓 Analysis"]
L5 --> L5P["📊 Power BI"]
L5 --> L5F["💡 Findings"]
L5 --> L5R["🎯 Recommendations"]

L1 --> L2
L2 --> L3
L3 --> L4
L4 --> L5
```

---

# 🛠️ Tools & Technologies

| Category                  | Tools                                  |
| ------------------------- | -------------------------------------- |
| Programming               | Python                                 |
| Data Analysis             | Pandas, NumPy                          |
| Interactive Analysis      | Jupyter Notebook                       |
| Databases                 | SQL, PostgreSQL / relational databases |
| Spreadsheets              | Microsoft Excel                        |
| Visualization             | Power BI                               |
| Business Analytics        | KPIs, Metrics, Data Storytelling       |
| Data Engineering Concepts | ETL, Data Pipelines                    |
| Version Control           | Git                                    |
| Repository                | GitHub                                 |

---

# 📊 What I Aim to Produce

Throughout this journey, I will build and document:

* 📓 Jupyter notebooks
* 🧹 Data-cleaning workflows
* 🗄️ SQL queries
* 📐 Statistical analyses
* 📊 Excel analyses
* 📈 Power BI dashboards
* 🎯 KPI frameworks
* 📝 Management briefs
* 💡 Business recommendations
* 🏆 End-to-end analytics projects

---

# 🔬 How I Document My Analysis

For major projects, I will follow:

```mermaid
flowchart LR

A["❓ PROBLEM"]
--> B["📊 DATA"]

B --> C["🧹 PREPARATION"]

C --> D["🔎 ANALYSIS"]

D --> E["📈 VISUALIZATION"]

E --> F["💡 FINDINGS"]

F --> G["🎯 RECOMMENDATIONS"]

G --> H["⚠️ LIMITATIONS"]
```

Every major project should answer:

### 1. What problem am I solving?

### 2. What data am I using?

### 3. How did I prepare the data?

### 4. What analysis did I perform?

### 5. What did I discover?

### 6. Why does it matter?

### 7. What should decision-makers consider doing?

### 8. What are the limitations of the analysis?

---

# 🚦 Evidence Framework

I will distinguish between three different types of statements:

```mermaid
flowchart TD

A["📊 DATA"]

A --> B["✅ DATA PROVES"]

A --> C["🧠 ANALYST SUSPECTS"]

A --> D["🔎 MANAGEMENT SHOULD<br/>INVESTIGATE"]

B --> E["Evidence"]

C --> F["Interpretation"]

D --> G["Further Investigation"]
```

This helps prevent the common mistake of presenting assumptions or correlations as proven facts.

---

# 📈 Progress Tracker

## Foundation

* [ ] Level 1 — Data Analytics Foundations
* [ ] Level 2 — SQL & Statistical Analysis

## Development

* [ ] Level 3 — Data Analysis
* [ ] Level 4 — Business Analytics & Communication

## Professional Readiness

* [ ] Level 5 — Junior Data Analyst Capstone

---

# 🏆 Final Competency Goal

By the end of this journey, I want to be able to independently:

```mermaid
flowchart TD

A["Understand a Business Problem"]
--> B["Understand the Data"]

B --> C["Prepare & Validate"]

C --> D["Query"]

D --> E["Analyse"]

E --> F["Visualize"]

F --> G["Interpret"]

G --> H["Recommend"]

H --> I["Communicate"]

I --> J["Support Decisions"]
```

---

# 💭 Lessons & Reflections

This section will grow throughout the journey.

I will document:

* What I learned
* What confused me
* Mistakes I made
* Problems I solved
* New techniques discovered
* Documentation I consulted
* What I would do differently
* How my analytical thinking is developing

---

# 🚀 Journey Principle

> **Learn → Build → Experiment → Solve → Understand → Document → Repeat**

This repository is more than a collection of exercises.

It is a record of my development from **learning data analysis concepts to applying them to real analytical problems**.

---

<p align="center">

### 📊 From Data → Information → Insight → Decision

**BIH Data Analyst Journey**

</p>

