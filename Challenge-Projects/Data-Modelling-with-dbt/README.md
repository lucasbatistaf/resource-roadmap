# Data Modelling with dbt

- This challenge was taken from a take-home challenge for a Analytics Engineer position

## Introduction
 Northwind Traders is a fictional store that manages orders, products, customers, suppliers, and many other aspects of a small business. Today, the company has about 30 employees and a monthly revenue of 1.5 million dollars. Its customers and suppliers are distributed across several countries. Its main products today are food, beverages, and household goods.

Today, Northwind has reports made in spreadsheets on demand. When the company was small, this format worked, but now with the company's accelerated growth, the data from different areas started to not match, and meetings became more conflicting.

The company also wants to better understand its data to increase the average ticket and reduce churn, two objectives considered strategic in the medium term.

Northwind's CEO, Tony Stark, is convinced that data is the key to the company's growth and now wants to have an integrated view of all the company's data in one place. However, the company's IT manager, John Snow, is apprehensive about the technical difficulties, costs, and deadlines for this project. Worse, John has participated in BI projects in the past using tools from large technology companies that did not achieve the expected success. The company's sales manager, Maria Antonieta, although very competent in her area, does not know the world of data and BI and has not yet been able to reach a conclusion about the project. On the other hand, the company's newly hired Innovation Manager, Pedro Pedreiro, is also betting heavily on the project to make Northwind a data-driven company.

The company's ERP database is a PostgreSQL system on a cloud server. In addition, the company uses a CRM from Salesforce and an accounting system from ContaAzul. Currently, the company does not have a BI system, but would be open to using tools such as Tableau, Data Studio, PowerBI, among others.

## Suggested tech stack for the project

- Data Modelling: **dbt**
- Data Warehouse: **Databricks, BigQuery, Redshift or Snowflake**
- Orchestration: **Airflow**
- CI/CD: **GitHub Actions**
- Data Visualization APP: **PowerBI, Looker Studio or Tableau**
- Data Testing and Documentation: **dbt**
- Relational Data Model: [**Diagram.io**](https://dbdiagram.io/d)


## Suggested Dataset

- [**Northwind Traders at Kaggle**](https://www.kaggle.com/datasets/jeetahirwar/northwind-traders/data)


## Challenge
- In this challenge, you will generate a report with performance indicators to meet Northwind's demands. To do this, you must create business indicators and suggest how we can act upon them to improve the company's results. You can use the tools you find easiest or most interesting, such as Excel, Google Sheets, Python, R, etc. Remember that this report will be presented to our CEO, so you must format it professionally.

- You also need to build a Relational Data Model for later documentation of the project.