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

## Framework Breakdown
* Ask: Define the business problem, clarify objectives, understand stakeholder expectations, and establish measurable metrics (KPIs).
* Prepare: Identify data sources, evaluate data integrity and metadata, ensure compliance with data privacy regulations (PII, GDPR), and store data securely.
* Process: Clean dirty data, handle missing or duplicate values, fix formatting inconsistencies, and ensure overall data integrity.
* Analyze: Organize and transform data using sorting, filtering, aggregating, and joining to uncover trends and patterns.
* Share: Design interactive dashboards, charts, and executive presentations tailored to technical and non-technical stakeholders.
* Act: Translate analytical insights into concrete recommendations and support business leadership in decision implementation.

## 3. Data Ecosystem & Analytical Thinking Skills
Five Key Mindsets of Analytical Thinking
* Visualization: Translating complex data into clear graphical representations.
* Strategy: Aligning analytics goals with overarching business strategies and resource constraints.
* Problem-Orientation: Framing challenges using structured logic to identify root causes.
* Correlation: Understanding relationships between variables while recognizing that correlation does not imply causation.
* Big-Picture vs. Detail-Oriented: Balancing granular data checks with high-level strategic outcomes.
  
### Types of Data Analysis
* Descriptive Analytics: What happened? (e.g., Monthly sales summaries).
* Diagnostic Analytics: Why did it happen? (e.g., Drill-down root-cause analysis of customer churn).
* Predictive Analytics: What is likely to happen in the future? (e.g., Demand forecasting).
* Prescriptive Analytics: What action should we take next? (e.g., Optimization recommendations).

## 4. Interview Practice Scenarios & Answer Frameworks 

* Scenario A: How do you explain technical findings to non-technical stakeholders?"Answer Framework:"I focus on the business impact rather than technical mechanics. I begin with the high-level takeaway or executive recommendation, support it with 1–2 key visual charts, and keep raw query details or technical methodologies in the appendix. I always translate metrics into business metrics (e.g., revenue, operational efficiency, customer retention).
  
* Scenario B: "How do you handle incomplete or dirty data?"Answer Framework:"During the Process phase, I perform exploratory checks to identify missing values, duplicates, or formatting anomalies. For missing data, depending on the context, I evaluate whether to impute values, filter out incomplete rows without introducing bias, or flag the missing entries to business stakeholders. Documenting every cleaning step in code or audit logs ensures reproducibility."

## 5. Foundations Glossary & Key TermsStructured Data: 
Data organized in predefined tabular formats with rows and columns (e.g., SQL tables, CSVs).
Unstructured Data: Data without a predefined model (e.g., audio, raw text, video files).
Data Lifecycle: Plan $\rightarrow$ Create $\rightarrow$ Store $\rightarrow$ Use $\rightarrow$ Archive $\rightarrow$ Destroy.
PII (Personally Identifiable Information): Any data that could potentially identify a specific individual (e.g., SSN, full names, email addresses).

---

### Terms and definitions for Course 1, Module 1

Analytical skills: Qualities and characteristics associated with using facts to solve problems

Analytical thinking: The process of identifying and defining a problem, then solving it by using data in an organized, step-by-step manner

Context: The condition in which something exists or happens

Data: A collection of facts

Data analysis: The collection, transformation, and organization of data in order to draw conclusions, make predictions, and drive informed decision-making

Data analyst: Someone who collects, transforms, and organizes data in order to draw conclusions, make predictions, and drive informed decision-making

Data analytics: The science of data

Data design: How information is organized

Data-driven decision-making: Using facts to guide business strategy

Data ecosystem: The various elements that interact with one another in order to produce, manage, store, organize, analyze, and share data

Data science: A field of study that uses raw data to create new ways of modeling and understanding the unknown 

Data strategy: The management of the people, processes, and tools used in data analysis

Data visualization: The graphical representation of data

Dataset: A collection of data that can be manipulated or analyzed as one unit 

Gap analysis: A method for examining and evaluating the current state of a process in order to identify opportunities for improvement in the future

Root cause: The reason why a problem occurs

Technical mindset: The ability to break things down into smaller steps or pieces and work with them in an orderly and logical way

Visualization: (Refer to data visualization) 

---

## There are six stages to the data life cycle. Here's a recap:

* Plan: Decide what kind of data is needed, how it will be managed, and who will be responsible for it.

* Capture: Collect or bring in data from a variety of different sources.

* Manage: Care for and maintain the data. This includes determining how and where it is stored and the tools used to do so.

* Analyze: Use the data to solve problems, make decisions, and support business goals.

* Archive: Keep relevant data stored for long-term and future reference.

* Destroy: Remove data from storage and delete any shared copies of the data.

### Note: Be careful not to confuse the six stages of the data life cycle (plan, capture, manage, analyze, archive, and destroy) with the six phases of the data analysis process (ask, prepare, process, analyze, share, and act). They are not interchangeable.
