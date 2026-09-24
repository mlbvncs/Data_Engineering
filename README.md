# Data Engineering

Projects involving ETL pipelines, data modeling, and data warehousing:

## ETL & Relational Data Modeling

- [Olist Brazilian Ecommerce Data Analysis](https://github.com/mlbvncs/Olist_Brazilian_Ecommerce_Data_Analysis) — Python ETL loading raw data into MySQL across 8 related tables (PK/FK modeling), with query results exposed as Views for direct Power BI consumption.
- [Customer Shopping Behavior Data Analysis](https://github.com/mlbvncs/Customer_Shopping_Behavior_Data_Analysis) — Python ETL notebook (`etl.ipynb`) loading transformed data into MySQL via SQLAlchemy/PyMySQL, structured for downstream analytical queries.

## Data Warehousing & Dimensional Modeling

- [Olist ETL Apache Hop (Group Project)](https://github.com/joaoal1998/etl_olist_apache_hop) — Group data engineering project: Star Schema dimensional model at item-grain, physically implemented in a PostgreSQL Data Warehouse hosted on Supabase; ETL pipeline built with Apache Hop (dimension/fact pipelines and workflows) orchestrated via Docker, feeding a Preset.io dashboard.
- [JJBike Version 1](https://github.com/mlbvncs/JJBike_V1) — Star Schema dimensional model with CTE-based SCD Type 2 logic in PostgreSQL.
- [JJBike Version 2](https://github.com/mlbvncs/JJBike_V2) — Star Schema with MERGE-based SCD Type 2 in SQL Server, plus Analysis Services (SSAS) cube deployment.
- [HotelAndStars](https://github.com/mlbvncs/HotelAndStars) — OLTP-to-OLAP dimensional modeling in SQL Server.