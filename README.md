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
   - 
     ![image](https://github.com/user-attachments/assets/9ff7376b-2392-4d96-bc17-133b0c470b09)


### 2. Product Size Grouping
   - Grouped data provides a breakdown of quantity sold by size, confirming that **M-Size items dominate sales**.
     
     ![image](https://github.com/user-attachments/assets/f25dc71b-5662-4e42-8f79-529de63e3c72)

  
### 3. Shipping and Order Status
   - An analysis of shipping and order statuses reveals that a **majority of orders are shipped via courier**.
     
     ![image](https://github.com/user-attachments/assets/d22290a6-72f1-44f9-a7c2-2a83f564c869)
     ![image](https://github.com/user-attachments/assets/bce18343-73fe-40d9-b0aa-7adc9e32126a)


### 4. Product Category Distribution
   - A histogram shows the distribution of purchases by category, with **T-shirts being the top-selling item**.
     ![image](https://github.com/user-attachments/assets/f38cdb7e-e68d-4746-a92b-c426bcb4d031)


### 5. B2B Analysis
   - A **pie chart** displays the split between Business-to-Business (B2B) and retailer buyers, where **retailers account for 99.2% of purchases**.
     ![image](https://github.com/user-attachments/assets/06b59afe-eca8-4260-8cd8-d4b6bc457ad4)



### 6. Geographic Distribution and Product Size Relationship
   - Scatter plots explore relationships between categories and sizes, while a **state-wise distribution plot** indicates **Maharashtra as the highest buyer concentration**.

     ![image](https://github.com/user-attachments/assets/61e39c69-27d7-49d0-af55-f3015fb33e20)
     ![image](https://github.com/user-attachments/assets/3fba6853-0c1d-44ba-a706-37c4ca3aec96)
     ![image](https://github.com/user-attachments/assets/a2a55601-b37a-415d-8c5c-c09742c4fbfa)

     


## Conclusion
The **Amazon Sales Analysis** project provides actionable insights into customer preferences, popular products, and state-wise distribution patterns. This information aids in making strategic decisions around inventory, marketing, and fulfillment to improve operational efficiency and customer satisfaction.
