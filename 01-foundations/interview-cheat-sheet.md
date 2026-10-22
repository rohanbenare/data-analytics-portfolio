# Module 1: Foundations of Data Analytics — Interview Cheat Sheet

## 1. Core Analytics Definitions & Business Value

### What is Data Analytics?
> **Data Analytics** is the collection, transformation, and organization of data in order to draw conclusions, make predictions, and drive informed business decision-making.

### Data Analysts vs. Adjacent Roles
| Role | Primary Focus | Key Deliverables | Typical Tools |
| :--- | :--- | :--- | :--- |
| **Data Analyst** | Answers specific business questions using historical data. | Dashboards, ad-hoc reports, trend analyses, actionable recommendations. | SQL, Excel/Sheets, Tableau, Power BI, R/Python. |
| **Data Engineer** | Builds and maintains data infrastructure, pipelines, and warehouses. | Clean, scalable data pipelines, database schema design, ETL workflows. | SQL, Apache Spark, Airflow, AWS/GCP Data Warehouses. |
| **Data Scientist** | Uses advanced statistical modeling and machine learning to forecast outcomes. | Predictive models, machine learning algorithms, statistical tests. | Python, R, Scikit-Learn, TensorFlow. |

---

## 2. The Google Data Analysis Process Framework

In behavioral interviews, use this 6-phase framework to structure answers when asked:  
*"Walk me through a time you solved a problem with data"* or *"How do you approach a new analytics project?"*

```text
[Ask] ──> [Prepare] ──> [Process] ──> [Analyze] ──> [Share] ──> [Act]
```

##Framework BreakdownAsk: Define the business problem, clarify objectives, understand stakeholder expectations, and establish measurable metrics (KPIs).Prepare: Identify data sources, evaluate data integrity and metadata, ensure compliance with data privacy regulations (PII, GDPR), and store data securely.Process: Clean dirty data, handle missing or duplicate values, fix formatting inconsistencies, and ensure overall data integrity.Analyze: Organize and transform data using sorting, filtering, aggregating, and joining to uncover trends and patterns.Share: Design interactive dashboards, charts, and executive presentations tailored to technical and non-technical stakeholders.Act: Translate analytical insights into concrete recommendations and support business leadership in decision implementation.

## 3. Data Ecosystem & Analytical Thinking Skills
Five Key Mindsets of Analytical ThinkingVisualization: 
Translating complex data into clear graphical representations.Strategy: Aligning analytics goals with overarching business strategies and resource constraints.Problem-Orientation: Framing challenges using structured logic to identify root causes.Correlation: Understanding relationships between variables while recognizing that correlation does not imply causation.Big-Picture vs. Detail-Oriented: Balancing granular data checks with high-level strategic outcomes.Types of Data AnalysisDescriptive Analytics: What happened? (e.g., Monthly sales summaries).Diagnostic Analytics: Why did it happen? (e.g., Drill-down root-cause analysis of customer churn).Predictive Analytics: What is likely to happen in the future? (e.g., Demand forecasting).Prescriptive Analytics: What action should we take next? (e.g., Optimization recommendations).

## 4. Interview Practice Scenarios & Answer Frameworks
Scenario A: "How do you explain technical findings to non-technical stakeholders?"Answer Framework:"I focus on the business impact rather than technical mechanics. I begin with the high-level takeaway or executive recommendation, support it with 1–2 key visual charts, and keep raw query details or technical methodologies in the appendix. I always translate metrics into business metrics (e.g., revenue, operational efficiency, customer retention)."
Scenario B: "How do you handle incomplete or dirty data?"Answer Framework:"During the Process phase, I perform exploratory checks to identify missing values, duplicates, or formatting anomalies. For missing data, depending on the context, I evaluate whether to impute values, filter out incomplete rows without introducing bias, or flag the missing entries to business stakeholders. Documenting every cleaning step in code or audit logs ensures reproducibility."

## 5. Foundations Glossary & Key TermsStructured Data: 
Data organized in predefined tabular formats with rows and columns (e.g., SQL tables, CSVs).Unstructured Data: Data without a predefined model (e.g., audio, raw text, video files).Data Lifecycle: Plan $\rightarrow$ Create $\rightarrow$ Store $\rightarrow$ Use $\rightarrow$ Archive $\rightarrow$ Destroy.PII (Personally Identifiable Information): Any data that could potentially identify a specific individual (e.g., SSN, full names, email addresses).
