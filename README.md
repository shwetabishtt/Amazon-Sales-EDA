# Amazon Sales Analysis

## Project Overview
The **Amazon Sales Analysis** project is a data-driven exploration of Amazon sales data, built using Python. By leveraging libraries such as **NumPy, Pandas, Matplotlib,** and **Seaborn**, this project provides a comprehensive view of sales trends, customer behavior, and geographic distribution. Insights gained can support Amazon in making data-informed decisions to optimize inventory, enhance customer satisfaction, and improve fulfillment strategies.

## Data Overview
The dataset consists of **128,976 entries across 21 columns**, covering details such as Order ID, Date, Status, Sales Channel, Quantity, and Amount. 

## Steps of Analysis

### 1. Data Loading and Initial Inspection
The first step loads the dataset from a CSV file using Pandas, followed by an initial inspection with:
   - `head()`, `info()`, and `shape` methods to examine the structure and size of the dataset.
   - Quick checks on column types and sample entries to understand the data fields.

### 2. Data Cleaning
To ensure data quality, the dataset undergoes multiple cleaning steps:
   - **Removing Unnecessary Columns**: Columns such as `'New'` and `'PendingS'`, which don’t add value, are dropped.
   - **Handling Null Values**: Missing data is addressed by either dropping rows or imputing values where appropriate.
   - **Data Type Adjustments**: Ensuring consistent data types (e.g., converting 'Date' to datetime format) for accurate analysis.

## Exploratory Data Analysis (EDA)

### 1. Size Analysis
   - A **count plot** visualizes the distribution of purchases by product size, with M-Size being the most frequently bought.

### 2. Product Size Grouping
   - Grouped data provides a breakdown of quantity sold by size, confirming that **M-Size items dominate sales**.

### 3. Shipping and Order Status
   - An analysis of shipping and order statuses reveals that a **majority of orders are shipped via courier**.

### 4. Product Category Distribution
   - A histogram shows the distribution of purchases by category, with **T-shirts being the top-selling item**.

### 5. B2B Analysis
   - A **pie chart** displays the split between Business-to-Business (B2B) and retailer buyers, where **retailers account for 99.3% of purchases**.

### 6. Fulfillment Method Distribution
   - Another pie chart shows fulfillment methods, highlighting **Amazon as the primary fulfillment service**.

### 7. Geographic Distribution and Product Size Relationship
   - Scatter plots explore relationships between categories and sizes, while a **state-wise distribution plot** indicates **Maharashtra as the highest buyer concentration**.

## Conclusion
The **Amazon Sales Analysis** project provides actionable insights into customer preferences, popular products, and state-wise distribution patterns. This information aids in making strategic decisions around inventory, marketing, and fulfillment to improve operational efficiency and customer satisfaction.
