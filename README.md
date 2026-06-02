# Power-BI-Project
## [Global Sales Analysis Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNDIyMWFjMWQtODY2MC00ODQ5LTlhOWQtNzUwNjVmOWU5MWRlIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)
<img width="1231" height="682" alt="image" src="https://github.com/user-attachments/assets/cdf42a5d-1d1f-4e62-b20d-9751a5795dd7" />

### Project Overview
This project analyzes international sales performance across multiple markets using Power BI. By combining transactional, product, store, and calendar data, the dashboard provides insights into revenue trends, regional performance, brand contribution, and year-over-year sales growth. The goal is to support data-driven decision-making through interactive visualizations and business intelligence techniques.
### Dataset Source
The analysis is based on the Contoso sample dataset. The dataset includes sales transactions from multiple countries, product information, store details, and calendar data. The project utilizes the following tables:
- Sales USA;
- Sales China;
- Sales Germany;
- Product;
- Store;
- Calendar.
<img width="1042" height="587" alt="image" src="https://github.com/user-attachments/assets/2845309f-592a-49a8-aa53-8750c8cc5a38" />

### Data Preparation
The data preparation process was performed in Power BI and included:
- Combined sales data from the USA, China, and Germany into a single sales table.
- Designed a star schema data model by connecting the Sales table with Product, Store, and Calendar dimension tables.
- Created a Calendar table using `CALENDARAUTO()`.
- Added calculated columns for Year, Quarter, and Month to support time-based analysis.
- Created a calculated column `Sum of Sales` using quantity and unit price.
- Created DAX measures for `Sales Amount`, `Sales Amount PY`, and `Sales Amount PY %` to analyze total sales, previous-year sales, and year-over-year growth.
### Data Visualization
The following visualizations were used to explore sales trends, regional performance, and brand contribution:
- Line charts for quarterly sales trends.
- Bar charts for brand performance comparison.
- Geographic map for regional sales distribution.
- Table for comparing sales performance across countries.
- Interactive slicers for dynamic dashboard exploration.
### Tools and Technologies:
- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling (Star Schema)
- Time Intelligence Functions
- Interactive Dashboard Design
### Key Findings:
- Total sales reached approximately $31.8 million across the analyzed markets.
- China generated the highest sales revenue, contributing approximately 36% of total sales.
- The United States accounted for approximately 34% of total sales.
- Germany represented approximately 30% of total sales.
- Sales performance fluctuated across quarters, with noticeable peaks and declines throughout the analyzed period.
- The Contoso brand generated the highest revenue among all analyzed brands.
- The three markets showed relatively balanced revenue distribution, reducing dependence on a single region.
### Business Recommendations
- Increase investment in the Chinese market, which currently generates the highest revenue.
- Analyze successful sales strategies in China and replicate them in lower-performing markets.
- Continue strengthening the Contoso brand through targeted marketing campaigns and product expansion.
- Investigate quarterly sales fluctuations to identify seasonal patterns and optimize inventory planning.
- Focus on growing sales in weaker regions while maintaining strong sales in existing markets.
- Use the dashboard as a decision-support tool for monitoring regional performance and allocating business resources more effectively.
