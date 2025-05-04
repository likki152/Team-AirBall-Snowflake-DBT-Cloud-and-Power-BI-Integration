Publishers Data Warehousing Project

Overview

This project focuses on building a data warehousing solution for managing and analyzing a publishing company's operations. Utilizing the "publishers" dataset, our solution encompasses the entire publishing process, from tracking title sales and managing author contracts to handling publisher information and employee details.

Dataset

The dataset includes tables for authors, titles, publishers, sales, stores, discounts, royalties schedule, title author, publisher information, and employees and jobs. These tables facilitate a comprehensive analysis of the publishing process.

Dimensional Modeling

High-Level Modeling: Our bus matrix captures core business processes: Title Sales, Store Sales, and Publisher Owned Titles, each associated with a specific fact table.
Detail-Level Modeling: Dimension tables identified include dim_title, dim_store, dim_discount, and dim_publisher, among others, contextualizing the facts.
Implementation

Tools Used: Azure Data Studio, MinIO S3, Snowflake, DBT Cloud, and Power BI.
Process: Data is initially staged in Snowflake, transformed using DBT Cloud based on our business processes, and visualized using Power BI dashboards.
