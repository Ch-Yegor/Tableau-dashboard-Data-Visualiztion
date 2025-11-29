# Tableau dashboard Data Visualiztion

## Link to Dashboard  
https://public.tableau.com/views/KeyBusinessMetricsoftheBicycleStoreChain/Dashboard1

## Description and Goals
An interactive Tableau dashboard consisting of three interconnected parts. The first part shows key metrics for the store chain, the second shows employee performance indicators, and the third shows the impact of discounts and timely delivery on the business.  
The purpose of the dashboard is to clearly present key data and metrics for assessing the current state of the business and making informed management decisions.

![Dashboard 1](https://i.imgur.com/AzVekJi.png)  
![Dashboard 2](https://i.imgur.com/U9KMmxS.png)
![Dashboard 3](https://i.imgur.com/iuYS9eI.png)

## Data
Data generated using PostgreSQL queries to a relational database is used for visualization. Initially, this database is divided into two subsystems, Sales and Production. The Sales subsystem includes five tables: customers, staff, orders, stores, and order_items. The Production subsystem includes four tables: categories, products, stocks, and brands.  
– Source of original data: [Bike Store Relational Database | SQL](https://www.kaggle.com/datasets/dillonmyrick/bike-store-sample-database)  

## Data Modeling Process
Some of the visualizations were created directly from data sources, while others (discounts, delivery, staff) is built around a primary fact table connected to supplementary datasets at the same store-month granularity. This structure keeps the models clean, consistent, and easy to analyze in Tableau.  

## Methods, Functions and Techniques
The dashboards use calculated fields, parameters, and action filters to control how metrics update and how views change during interaction. The setup connects these elements across all dashboards to support navigation, comparisons, and dynamic content.
