# flipkart-product-analysis
🛍️ Flipkart Product Analysis – Summary
🎯 Objective
To analyze Flipkart product listings and extract insights regarding sales, ratings, pricing strategies, and category/seller performance using data science techniques.

📊 Workflow Breakdown
1. Data Loading & Cleaning
Dataset: Flipkart product listings from a Kaggle dataset (flipkart_products_20250405.csv).

Cleaning Tasks:

Removed special characters from Price (₹) and Discount (%).

Converted those fields into numeric format.

Filled missing values:

Rating (★) → with mean

Number of Buyers, Total Sold → with 0

2. Exploratory Data Analysis (EDA)
📌 Summary Statistics
Used .describe() to understand central tendency, spread, and outliers.

📌 Visualizations
Histograms for:

Product Prices

Ratings

Discounts

Correlation Heatmap:

To explore relationships between variables like price, ratings, and sales.

3. Top Product Insights
🏆 Top 10 Products
By Rating: Highest-rated products

By Sales: Best-selling products

4. Category-Wise Analysis
Aggregated average:

Price

Rating

Discount

For each product category to identify trends and preferences.

5. Seller-Wise Analysis
Total sales and average ratings by seller.

Helps highlight high-performing sellers.

6. Return Policy Impact
Evaluated how return policy availability influences:

Sales

Ratings

This helps assess customer trust and satisfaction.

📌 Key Takeaways & Use Cases

Area	Application
Marketing	Strategy development based on top categories and sellers.
Pricing	Optimizing price and discount strategy to maximize conversions.
Customer Insight	Understand how return policies influence buyer behavior.
Decision-Making	Actionable insights for product selection and promotion.
