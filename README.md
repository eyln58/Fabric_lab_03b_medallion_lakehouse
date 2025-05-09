# 📊 Medallion Lakehouse Architecture with Microsoft Fabric

This repository documents the completion of a hands-on lab focused on implementing a **Medallion Lakehouse Architecture** using Microsoft Fabric.

## 🎯 Purpose of the Lab

The goal of this lab was to simulate a modern data engineering pipeline within Microsoft Fabric by building a structured lakehouse using the **Bronze–Silver–Gold** architectural pattern. The exercise aimed to demonstrate how raw data can be ingested, cleaned, modeled, and finally transformed into a business-ready form suitable for reporting and analysis.

## 🧠 What I Learned

Through this lab, I gained practical experience with the following concepts and processes:

- **Lakehouse Fundamentals**  
  I understood how a lakehouse serves as a unified platform for both structured and semi-structured data, blending the best of data lakes and data warehouses.

- **Medallion Architecture Design**  
  I learned the value of organizing data in **incrementally refined layers** (Bronze, Silver, Gold) to improve quality, traceability, and usability:
  - *Bronze:* Raw data as-is from source systems  
  - *Silver:* Cleaned and validated data  
  - *Gold:* Curated, modeled data ready for analysis  

- **Data Validation and Enrichment**  
  I applied typical real-world data quality operations such as null handling, derived columns, and timestamp tracking.

- **Dimensional Modeling**  
  I created **dimension and fact tables** to represent customers, products, dates, and transactions, effectively applying the *star schema* approach used in analytical systems.

- **Incremental Data Loading and Upserts**  
  I practiced updating and inserting data dynamically using merge strategies that help maintain data consistency over time.

- **Semantic Modeling**  
  I learned how to build a semantic model in Fabric, define relationships, and prepare the data for direct integration with reporting tools like Power BI.

## ✅ Outcome

At the end of the lab, I successfully built a complete lakehouse architecture that enables end-to-end data flow:
- From ingestion of raw files (CSV)
- To cleaning and validation
- To dimensional modeling and fact aggregation
- And finally, to creating a semantic model for business intelligence

## 🤝 Let's Connect

If you're working with Microsoft Fabric or planning to, I'd be happy to connect and share insights.  
Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/eyilan/) — let's talk Fabric!
