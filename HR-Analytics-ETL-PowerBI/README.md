
# HR Analytics: From Raw Data to Insights

## End-to-End Data Engineering & BI Project

An end-to-end HR analytics project demonstrating how raw workforce data can be transformed into structured analytical datasets and actionable business insights using **SQL Server, SSIS, and Power BI**.

The project implements an ETL pipeline, dimensional data modelling, and interactive reporting to analyse employee attrition, performance, workforce trends, and organisational metrics.

## 📊 Dataset

The project uses the publicly available **[IBM HR Analytics Employee Attrition & Performance Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)** from Kaggle.

The dataset contains employee-related information, including demographics, job roles, satisfaction levels, performance, compensation, and attrition status.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Microsoft SQL Server | Database management and data storage |
| SQL Server Integration Services (SSIS) | ETL development and data integration |
| SQL | Data transformation and analytical queries |
| Power BI | Interactive dashboards and reporting |
| DAX | Measures and analytical calculations |
| Star Schema | Dimensional data modelling |
| Fact Constellation | Multiple fact tables sharing common dimensions |

## 🏗️ Project Architecture

The project follows an ETL-based data engineering workflow:

```text
Raw HR Dataset (CSV)
        |
        ▼
SSIS - Data Extraction
        |
        ▼
Data Transformation & Cleaning
        |
        ▼
SQL Server Data Warehouse
        |
        ▼
Dimensional Data Model
        |
        ▼
Power BI Dashboards
```

## 📈 Business Questions & Analytical Focus

The solution explores key HR and workforce management questions:

- What factors contribute to employee attrition?
- How does employee performance vary across departments?
- Are employees experiencing career stagnation or delayed promotions?
- How does managerial stability relate to employee outcomes?
- How do workforce demographics and diversity metrics vary across the organisation?

## 🔄 ETL & Data Engineering

The ETL workflow was developed using SQL Server Integration Services (SSIS).

Key activities include:

- Extracting raw employee data from CSV files.
- Cleaning and transforming workforce data.
- Loading transformed data into SQL Server.
- Organising data into dimensional structures.
- Preparing analytical datasets for Power BI reporting.

## 🗄️ Data Modelling

Designed a dimensional data model using Star Schema and Fact Constellation concepts to support analytical reporting.

The model enables structured analysis across employee, department, job, performance, and attrition-related dimensions.

## 📊 Power BI Reporting

Developed Power BI dashboards to explore workforce trends and support HR decision-making.

The analytical focus includes:

- Employee attrition analysis.
- Employee performance and satisfaction.
- Departmental workforce comparisons.
- Career progression and promotion trends.
- Workforce diversity metrics.
- Managerial and organisational analysis.

## 🎯 Key Skills Demonstrated

- ETL pipeline development using SSIS.
- SQL Server database development.
- SQL-based data transformation.
- Dimensional data modelling.
- Star Schema and Fact Constellation.
- Power BI dashboard development.
- DAX calculations and reporting.
- HR analytics and business intelligence.

## 👤 Author

**Selam**

Data Engineer | Data Warehousing | Business Intelligence

- Medium: [Row by Row: BI & Data Engineering]
