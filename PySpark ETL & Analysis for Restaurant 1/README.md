# Data Dining: PySpark ETL & Analysis with Databricks for Restaurant Insights 
### Links : [ETL](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4140359732294337/2189550842702141/772302209328010/latest.html) | [Analysis](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4140359732294337/627314337463392/772302209328010/latest.html) | [Dashboard](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4140359732294337/2729860077956927/772302209328010/latest.html)

Developed an end-to-end data processing and analysis pipeline using PySpark in Databricks to derive actionable insights from restaurant sales and menu data. The project involved extracting, transforming, and loading (ETL) data from various sources and performing comprehensive analysis to create insightful dashboards.

## Key Responsibilities and Achievements:
### Data Extraction:
* Extracted restaurant sales data and menu data stored in Databricks File System (DBFS).
* Utilized an API to fetch additional sales data, appending this data to the existing sales dataframe in DBFS.

### Data Transformation:
* Cleaned and transformed the raw data to prepare it for analysis.
* Defined schema for the joined sales and menu data, ensuring consistency and accuracy.
* Derived time-based features from the order date, including month, quarter, and year, to facilitate temporal analysis.

### Data Loading:
*	Saved the processed data into Parquet format for optimized storage and efficient querying.

### Data Analysis:
*	Loaded the Parquet data into PySpark for analysis and exploration.
*	Conducted a variety of metrics analyses, such as identifying the top 5 customers by sales and top 5 products by sales.
*	Calculated monthly sales trends and other relevant business metrics to understand performance.

### Dashboard Creation:
*	Leveraged Databricks to build interactive dashboards showcasing the analytical findings.
*	Developed visualizations and charts to present key insights on customer behavior, product performance, and sales trends.
*	Designed the dashboard for user-friendly navigation and clear data representation.

### Technologies Used:
*	PySpark (Python API for Apache Spark)
*	Databricks (Unified Analytics Platform)
*	Apache Parquet (Columnar storage format)

Through this project, I gained hands-on experience in data engineering and analytics within a cloud-based environment. I successfully implemented scalable solutions to handle large volumes of data, enabling meaningful business intelligence and decision-making for restaurant operations.


