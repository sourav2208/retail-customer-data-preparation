# Retail Customer Analytics: Data Cleaning, Time Series, Churn & RFM Analysis
![Retail](https://github.com/sourav2208/retail-customer-data-preparation/blob/main/ChatGPT%20Image%20Jul%2014%2C%202025%2C%2012_32_30%20PM.png)

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

## Skills Demonstrated
- Real-world Data Cleaning
- Time Series Analysis
- Customer Segmentation using RFM
- Churn Analysis
- Data Visualization
- Business Insight Generation

---
## Key Insights
- A large number of customers are classified as low-value based on their recency, frequency, and monetary activity.

- The top 5 customers contribute a significant portion of total revenue.

- Most customers who responded positively (response = 1) are also among those with higher frequency and monetary value.

- Outliers were detected in transaction amounts, indicating a few unusually high spenders.

- Customer activity varies over time — some customers are active consistently, while others show irregular patterns.

The churn rate is noticeable; a significant percentage of customers did not respond or engage recently.####

## Recommendations
- Retarget mid-value customers with promotional offers to increase their transaction frequency and spending.

- Re-engage churn-prone customers (with low recency) through personalized emails, SMS, or loyalty programs.

- Monitor top customers closely and offer VIP benefits to retain them and increase their lifetime value.

- Use segmentation to create tailored marketing campaigns different strategies for low, mid, and high-value segments.

- Regularly perform RFM analysis to keep track of shifting customer behavior and act on trends early.

### 📫 Connect with me on [LinkedIn] - https://www.linkedin.com/in/sourav2208/



