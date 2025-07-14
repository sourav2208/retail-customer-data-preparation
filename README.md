# Retail Customer Analytics: Data Cleaning, Time Series, Churn & RFM Analysis
![Retail](https://github.com/sourav2208/retail-customer-data-preparation/blob/main/retail.png)

This end-to-end project covers the complete journey from raw retail transaction data to meaningful business insights. It includes data cleaning, time series analysis, customer churn identification, and RFM segmentation.

## Datasets Used
- `Retail_Data_Transactions.csv`: Customer-level retail transaction data.
- `Retail_Data_Response.csv`: Customer responses indicating churn or retention.

## Tools & Libraries
- Python 
- Pandas 
- NumPy 
- SciPy 
- Matplotlib 
- Seaborn 


---

## Project Workflow

### 1. Data Import & Merging
- Loaded transaction and response datasets
- Merged on `customer_id` with a left join

### 2. Data Cleaning
- Handled missing values and duplicates
- Ensured data type consistency
- Basic sanity checks on date columns, values, etc.

### 3. Exploratory Data Analysis (EDA)
- Statistical summaries using `.describe()`
- Visual exploration using Matplotlib & Seaborn
- Feature inspection and outlier detection

### 4. Time Series Analysis
- Converted transaction date columns to datetime format
- Grouped by time (daily/weekly/monthly)
- Analyzed sales trends, seasonal patterns, and volume spikes

### 5. Customer Churn Analysis
- Identified churned vs retained customers
- Compared purchasing patterns, frequency, and value
- Visualized churn trends

### 6. RFM Analysis (Recency, Frequency, Monetary)
- Calculated:
  - **Recency** = Days since last purchase
  - **Frequency** = Total number of purchases
  - **Monetary** = Total spend per customer
- Segmented customers based on RFM scores
- Identified loyal, at-risk, and lost customers

---

## ✅ Skills Demonstrated
- Real-world Data Cleaning
- Time Series Analysis
- Customer Segmentation using RFM
- Churn Analysis
- Data Visualization
- Business Insight Generation

---

### 📫 Connect with me on [LinkedIn] - https://www.linkedin.com/in/sourav2208/



