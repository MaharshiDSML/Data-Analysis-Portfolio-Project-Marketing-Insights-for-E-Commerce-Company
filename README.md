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

## <mark>Recommendations:</mark>
**I have already provided insights and recommendations in each cell and after almost each chart. However, I am also providing a summarized, more clear and consise list of recommendations:**

**<ins>1. Marketing and Promotions:</ins>**

- **Enhanced Marketing During Low Months:** Increase marketing efforts in February and September to boost customer acquisition with special campaigns or incentives.
- **Leverage Peak Seasons:** Plan significant marketing campaigns and discounts during peak acquisition periods (June, August, December) and ensure inventory and customer support are prepared for increased demand.
- **Promotion Strategies:** Review and optimize discount coupons and experiment with different types of promotions (e.g., bundle deals, limited-time offers).
- **Seasonal Strategies:** Run targeted campaigns during low retention months (February, April, September) and reinforce marketing efforts during high retention periods.
- **Mid-Week and Seasonal Promotions:** Implement special mid-week promotions on Wednesdays and early holiday promotions starting in week 40, leveraging strong sales periods.

**<ins>2. Customer Acquisition and Retention:</ins>**

- **Sustain Customer Acquisition Efforts:** Implement periodic promotions, referral programs, and targeted advertising campaigns to avoid sharp declines in new customer revenue after January.
- **Improving Customer Retention:** Implement loyalty programs, improve post-purchase engagement, and use customer feedback to identify and address pain points.
- **Address Post-Holiday Churn:** Implement targeted retention strategies in January and analyze high churn rates to identify common factors.

**<ins>3. Customer Segmentation and Personalization:</ins>**

- **Utilize Customer Demographics:** Tailor marketing campaigns based on customer demographics, targeting locations and segments with higher engagement and acquisition rates.
- **Customer Segmentation:** Segment customers based on purchasing behavior and demographics to create targeted marketing strategies and improve personalization.

**<ins>4. Coupon Strategy:</ins>**

- Investigate customer behavior to understand why some customers abandon their carts after clicking on a coupon.
- Conduct surveys or focus groups and offer different types of coupons (e.g., free shipping or percentage discounts).
- A/B test coupon placements on the website to optimize visibility and usage, and streamline the checkout process to reduce cart abandonment.

**<ins>5. Inventory and Supply Chain Management:</ins>**

- **Inventory Optimization:** Ensure high-demand products are well-stocked, especially during peak sales periods, and align inventory levels with observed sales trends.
- **Enhance Supply Chain Efficiency:** Optimize the supply chain to handle peak sales periods efficiently and prevent stockouts, particularly for high-demand categories.

**<ins>6. Marketing Spend Analysis and Optimization:</ins>**

- **Analyze Marketing Spend Efficiency:** Conduct detailed analysis to understand the correlation between marketing spend and customer acquisition, and optimize budgets accordingly.
- **Enhanced Attribution Analysis:** Conduct detailed attribution analysis to better understand the impact of online and offline marketing spend on sales.

**<ins>7. Product and Category Focus:</ins>**

- **Focus on High Revenue and High-Value Categories:** Prioritize marketing for high-revenue categories like Nest-USA and Apparel, and explore upselling and cross-selling opportunities.
- **Promote High Volume Categories:** Increase profitability of high-volume categories (Office products) by optimizing pricing strategy and exploring bulk purchase discounts.
- **Product Expansion and Optimization:** Consider expanding product lines within high-demand categories and promoting products with moderate sales to elevate their market presence.

**<ins>8. Customer Feedback and Continuous Improvement:</ins>**

- **Analyze Customer Feedback:** Collect and analyze customer feedback to identify common pain points and areas for improvement, and address these promptly.
- **Monitor and Adapt Strategies:** Continuously monitor sales data and customer feedback to identify trends and adjust marketing strategies accordingly.

**<ins>9. Operational Adjustments:

- **Optimize Staffing and Logistics:** Adjust staffing and delivery logistics to handle higher volume during peak sales periods efficiently.

**<ins>10. Enhanced Customer Experience:</ins>**

- **Improve User Experience:** Ensure the website and mobile app provide a seamless shopping experience, particularly during peak periods, to reduce cart abandonment rates.
- **Customer Support and Service:** Provide excellent customer support, especially during peak months, to enhance customer satisfaction and loyalty.

**By implementing these recommendations, you can improve your marketing efficiency, enhance customer acquisition and retention, and optimize overall business operations.**

​
