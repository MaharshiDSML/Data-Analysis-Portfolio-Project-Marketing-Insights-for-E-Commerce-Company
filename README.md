# <mark>Data Analysis Portfolio Project: Marketing Insights for E-Commerce Company</mark>

## <mark>Business Problem Statement:</mark>

- A rapidly growing e-commerce company aims to transition from intuition-based marketing to a data-driven approach.
- By analyzing customer demographics, transaction data, marketing spend, and discount details from 2019, the company seeks to gain a comprehensive understanding of customer behavior.
- The objectives are to optimize marketing campaigns across various channels, leverage data insights to enhance customer retention, predict customer lifetime value, and ultimately drive sustainable revenue growth.

## <mark>Data description:</mark>

https://drive.google.com/drive/folders/1VXaZSDFqN_Zi3FxucRlthz97Etl1CYfJ?usp=sharing

**1. <ins>Online_Sales.csv:</ins>**
This file contains actual orders data (point of Sales data) at transaction level with the below variables.

- CustomerID: Customer unique ID
- Transaction_ID: Transaction Unique ID
- Transaction_Date: Date of Transaction
- Product_SKU: SKU ID – Unique Id for product
- Product_Description: Product Description
- Product_Cateogry: Product Category
- Quantity: Number of items ordered
- Avg_Price: Price per one quantity
- Delivery_Charges: Charges for delivery
- Coupon_Status: Any discount coupon applied

**2. <ins>Customers_Data.csv:</ins>**
This file contains customer’s demographics.

- CustomerID: Customer Unique ID
- Gender: Gender of customer
- Location: Location of Customer
- Tenure_Months: Tenure in Months

**3. <ins>Discount_Coupon.csv:</ins>**
Discount coupons have been given for different categories in different months

- Month: Discount coupon applied in that month
- Product_Category: Product category
- Coupon_Code: Coupon Code for given Category and given month
- Discount_pct: Discount Percentage for given coupon

**4. <ins>Marketing_Spend.csv:</ins>**
Marketing spend on both offline & online channels on day wise.

- Date: Date
- Offline_Spend: Marketing spend on offline channels like TV, Radio, NewsPapers, hoardings etc.
- Online_Spend: Marketing spend on online channels like Google keywords, facebook etc.

**5. <ins>Tax_Amount.csv:</ins>**
GST Details for given category

- Product_Category: Product Category
- GST: Percentage of GST

## <mark>Approach:</mark>
Through this project, we expect to leverage a range of data analysis techniques to uncover actionable insights that propel the e-commerce company towards significant customer retention and revenue growth. This includes:

- **Identifying key customer segments and behaviors:** Utilizing descriptive statistics and segmentation techniques to understand what drives customer acquisition and churn.
- **Evaluating marketing campaign effectiveness:** Employing hypothesis testing to assess the impact of online and offline marketing efforts on customer behavior and revenue.
- **Optimizing discount strategies:** Analyzing the influence of discounts and promotions on revenue and customer engagement to identify optimal pricing strategies.
- **Predicting customer lifetime value:** Implementing data-driven models to anticipate future customer value and prioritize retention efforts.
- **Unveiling cross-selling opportunities:** Performing market basket analysis to discover frequently co-purchased products and inform product placement strategies.
- **Formulating data-driven recommendations:** Presenting clear and compelling visualizations and reports that translate insights into actionable marketing strategies for maximizing customer retention and revenue growth.

## <mark>Solution Methodology:</mark>

**1. <ins>Data Cleaning and Preprocessing:</ins>**

- **Data Cleaning:** Ensure data quality by identifying and handling missing values, inconsistencies, and outliers in each dataset.
- It is crucial to begin by calculating the invoice amount or revenue for each transaction using this formula, This establishes the foundation for revenue analysis. Invoice Value = ((Quantity Avg_price) (1 - Discount_pct) * (1 + GST)) + Delivery_Charges.

**2. <ins>Exploratory Data Analysis (EDA):</ins>**

- **Customer Acquisition & Retention:** Analyze trends in customer acquisition and churn across different customer demographics (gender, location, tenure) and timeframes (monthly). Tools like time series analysis and segmentation can be helpful here.
- **Marketing Campaign Impact:** Explore the relationship between marketing spend (online & offline) and customer behavior (orders, revenue) to assess campaign effectiveness. Utilize techniques like hypothesis testing to validate your findings.
- **Discount Analysis:** Investigate how discounts and promotions affect revenue and customer engagement. Analyze KPIs like average order value and customer acquisition cost across different discount structures.

**3. <ins>Deeper Analysis:</ins>**

- **Seasonality & Trends:** Identify seasonal trends and patterns in sales data across different timeframes (month, week, day) to inform future marketing strategies.
- **Calculate key performance indicators (KPIs):** KPIs like revenue, number of orders, and average order value across various dimensions (category, month, week, day).
- **Marketing Spend & Revenue:** Calculate revenue, marketing spend, and delivery charges by month to understand their correlation. This can reveal areas for optimization.
- **Product & Customer Relationships:** Analyze co-purchased products through market basket analysis. This will uncover cross-selling opportunities and inform product placement strategies. (Optional)
- **Customer Lifetime Value (CLTV):** Implement predictive models to estimate the future value of each customer. This helps prioritize retention efforts for high-value customers. (Optional)

**4. <ins>Cohort Analysis:</ins>**
Create customer cohorts based on their acquisition month: Track their behavior (orders, revenue) over time to identify the cohort with the highest retention rate. This reveals valuable customer acquisition trends.

**5. <ins>Actionable Insights & Recommendations:</ins>**

- **Insights:** Translate your findings into clear and compelling visualizations and reports.
- **Recommendations:** Formulate data-driven recommendations for optimizing marketing strategies, improving customer retention, and maximizing revenue growth for the e-commerce company.
