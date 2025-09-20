📦 Data Warehouse Analysis

This project demonstrates data warehouse exploration and analysis using SQL. The scripts are structured to cover different aspects of data modeling, aggregation, and reporting within a warehouse environment.

📂 Project Structure

The repository is organized as follows:

datasets/ → Contains raw and processed datasets for analysis.

scripts/ → SQL scripts categorized by analysis type:

00_init_database.sql → Initialize and set up the database schema.

01_database_exploration.sql → Explore database metadata and structure.

02_dimensions_exploration.sql → Analyze dimensions and hierarchies.

03_date_range_exploration.sql → Perform time-based exploration.

04_measures_exploration.sql → Explore key performance measures.

05_magnitude_analysis.sql → Evaluate absolute and relative magnitudes.

06_ranking_analysis.sql → Ranking entities based on KPIs.

07_change_over_time_analysis.sql → Time-series and trend analysis.

08_cumulative_analysis.sql → Running totals and cumulative metrics.

09_performance_analysis.sql → Performance tracking & KPI comparison.

10_data_segmentation.sql → Customer/product segmentation analysis.

11_part_to_whole_analysis.sql → Contribution analysis (part-to-whole).

12_report_customers.sql → Customer-focused reporting queries.

13_report_products.sql → Product-focused reporting queries.

⚒️ Tools & Technologies

SQL (analysis & reporting)

Relational Database / Data Warehouse (any SQL-compatible system)

GitHub (version control & collaboration)

🚀 How to Use

Clone the repository:

git clone https://github.com/ToyeshSingh/data_warehouse_analysis.git


Navigate to the scripts/ folder.

Execute scripts sequentially (from 00_init_database.sql onwards).

Use the queries to generate insights and reports on customers, products, and performance.

📌 Key Learnings & Insights

Built a modular approach to data warehouse exploration.

Applied time-based, cumulative, ranking, and segmentation analyses.

Designed customer & product reports for decision-making.

📝 Future Scope

Automate reporting with BI tools (e.g., Tableau/Power BI).

Add ETL pipelines for data ingestion.

Extend analysis with predictive modeling.
