# Fedex-Sales-Report
The analysis provides a comprehensive sales transaction dataset containing multiple variables across independent categories (Customer name, Category, State, City, and Payment mode) and Dependent Variables (Quantity, Amount, and Profit)
<img width="2502" height="1209" alt="FEDEX DASHBOARD" src="https://github.com/user-attachments/assets/d539b862-0a52-4ee1-b6e4-c52e86640360" />
Introduction
The primary objective of this analytical project is to analyze transaction-level sales and profit data to identify top-performing product categories, key geographical strengths customer segments, and seasonal trends.
The goal is to provide data-driven insights that can inform strategic business decisions to maximize overall profitability and optimize resource allocation.

Problem Being Addressed:
The analysis seeks to solve the fundamental business problem of optimizing product and regional performance. It aims to answer:
•	Which product categories and sub-categories are the most profitable?
•	Which states and cities are driving the majority of the profit?
•	Are there predictable seasonal trends that can be leveraged for inventory and marketing? 
Key Datasets and Methodologies:
Dataset: The analysis provides a comprehensive sales transaction dataset containing multiple variables across independent categories (Customer name, Category, State, City, and Payment mode) and Dependent Variables (Quantity, Amount, and Profit)
Methodologies:
Analysis was conducted using Microsoft Excel with Pivot tables, data aggregation functions, and visualization tools to extract meaningful insights from the raw transactional data.
Data Story
The data covers multiple product category and is structured to facilitate easy analysis of sales performance across different locations and time period. This dataset contains detailed sales transaction, including order retails, revenue, profit and customer information. 
Data Source
The dataset originates from an internal retail sales database capturing detailed transaction records across the organization’s entire sales operation.
Important Features and Their Significance:
•	Profit: The core dependent variable, used to measure performance across all dimensions.
•	Product Category and Sub Category: Critical for identifying product profitability and inventory strategy.
•	State and City: Essential for geographical performance assessment and optimizing logistics.
•	Payment Mode: Relevant for operational efficiency and understanding customer behavior.
•	Order Date/Year-Month: Used to analyze performance over time and identify seasonality.
Data Limitations or Biases
The analysis is limited to the available transaction data. It does not include critical external factors such as competitor pricing, marketing spends allocation (beyond general assumptions), detailed Cost of Goods sold per sub-category, which limits the ability to calculate true net profit margin.
Data Transformation
The raw Order Date variable was transformed into a Year-Month format and aggregated by month name for trend analysis. The Amount variable was grouped into predefined bins to analyze the distribution of transaction values.
Data Splitting
The analysis separated independent variables from dependent variables. This separation enabled correlation analysis and causal relationship exploration between operational factors and performance outcomes.
Industry Context
Retail/E-commerce.
Stakeholders
Key stakeholders include:
•	Senior Management: for strategic planning.
•	Sales Team: for performance management.
•	Marketing Department: for campaign targeting.
•	Inventory/Logistics Teams: for forecasting demand.
Value to the Industry
The insights enable the company to move from reactive to proactive decision-making, allowing for precise resource allocation to maximize profit from proven growth areas (e.g., specific products or regions).
Pre-Analysis
Project Split
Category One: Independent Values
•	Customer name
•	Category 
•	Sub category
•	State
•	City
•	Payment mode
Category Two: Dependent Values
•	Quantity 
•	Amount 
•	Profit
Potential Analysis Question
•	Customer performance analysis by profit generated
•	Best performing sub-category of the year by profit generated
•	Sub-category performance by quantity
•	Customer performance analysis by profit generated
•	Customer performance analysis by quantity
•	Payment usage over time by quantity purchased
•	Product category performance by profit generated
•	Product category performance by profit generated
•	Product category performance by quantity purchased
•	Best performing state for the year by quantity purchased
•	State performance analysis by profit generated
•	Top city performance by profit generated 
•	Top city performance by quantity purchased
Potential Insights
•	Recognize and reward most active customers by volume
•	Identify top performing city 
•	Finetune the best performing product of the year to ensure that there is an increase in the level of production to generate more income to the firm
•	Finetune the most profitable product not just the bestselling and increase focus on high margin product
•	Finetune best performing city by sales volume and expand marketing in top cities
•	Finetune customers that generate the highest revenue and provide discounts for these customers
•	Finetune top payment methods to enhance checkout experience
•	compare pricing across categories and adjust pricing for competitiveness and profitability
•	finetune state which have high product demand and set up city hubs
•	finetune categories that give best return and improve pricing on low profit categories
In Analysis
 Product Category Performance
Observation 
•	office Supplies generated the highest profit at $551,575.00.
•	Furniture is a close second at $540,542.00.
•	Electronics generated the lowest profit at $518,580.00.
•	The total profit across the three categories is $1,610,697.00.
Pre Insights
•	Office Supplies is the top-performing category, generating slightly more profit than Furniture. This suggests a strong and consistent demand for recurring consumables, which often have high sales volumes and good margins.
•	The profit across the three categories is relatively close, with only a \approx.\$33,000 difference between the highest (Office Supplies) and the lowest (Electronics). This indicates a healthy and diversified business, not overly reliant on a single category.
•	Electronics is the lowest-profit category. This could represent an area for improvement through targeted marketing, new product sourcing, or adjusting pricing strategies to boost its profitability and align it more closely with the other two categories.

Transaction By Amount
 Observation
•	The vast majority of transactions fall into the lowest dollar range, 0-999, accounting for 581 transactions
•	Between the range of 1000-1999 generated 308 transactions.
•	Between the range of 2000-2999 generated 168 transactions.
•	Between the range of 3000-3999 generated 109 transactions.
•	The highest-value range, 4000-5000, has the lowest count, with only 28 transactions.
Pre Insights
•	The data confirms that the business's transaction volume is primarily driven by low-value purchases. This suggests a focus on mass-market appeal and efficiently processing high numbers of small orders.
•	Given the high volume in the 0-999 range, processes related to sales, fulfillment, and customer service for these low-value orders must be highly optimized to maximize profit margins.
•	The sharp drop-off to only 28 transactions in the $4000-$5000 range highlights that these high-value sales are rare events. This low count could be an opportunity to investigate if there are bottlenecks in the sales process for high-value items, or if the product offering in that tier is insufficient or poorly marketed.
 
Product Category by Quantity
Observation
•	Furniture has the highest sum of quantity 4,441 units.
•	Electronics has the second-highest quantity 4,258 units.
•	Office Supplies has the lowest quantity 4,046 units.
Pre Insights
•	The Furniture category is the volume leader, suggesting high demand or effective sales strategies for items in this category.
•	The extremely close unit totals for all three categories (4441, 4258, 4046) indicate that the business has a very balanced sales mix. This is a positive sign, as it prevents over-reliance on a single product line and distributes sales risk.
•	Office Supplies is the lowest in Quantity but was the highest in Profit. This suggests that Office Supplies items have a higher average profit margin per unit, making them very valuable despite the lower sales volume.
 Top 5 Sub Category Performance 
Observation
•	The Markers sub-category is the clear leader, generating $174,749.00 in profit.
•	Tables follow with $156,796.00.
•	Paper generated $149,723.00
•	Electronic Games generated $148,454.00
•	Printers generated $146,259.00
Pre Insights
•	The Markers sub-category (likely part of the Office Supplies parent category) drives the most profit, significantly more than the others. This suggests they are either sold at a high volume, have an excellent profit margin, or both. This sub-category should be a focal point for inventory management and promotion.
•	Tables likely represent the Furniture category's strongest profit contributor. Given that tables are higher-ticket items, their strong showing confirms that the business is successfully capitalizing on high-value sales, not just high-volume low-cost items.
•	The tight grouping of Paper, Electronic Games, and Printers suggests that a small improvement in marketing, pricing, or sourcing for Printers and Electronic Games could easily push them past Paper. Since Paper (another Office Supply) has a high margin, the focus should be on boosting the volume or price of Printers and Games to increase the total profitability of that group.
•	The top five list includes items from all three major product categories (Markers/Paper from Office Supplies, Tables from Furniture, and Electronic Games/Printers from Electronics). This demonstrates that the profit base is diverse and not vulnerable to a downturn in any single product category.

 Sales Trend Report 
 Observation
•	Profit starts low in January ($110,381.00) and then sees a consistent rise through the first quarter, peaking in March ($152,239.00)
•	April sees a high of $157,739.00
•	A dip in June ($129,023.00) is followed by a strong recovery in July ($141,845.00).
•	August sees a sharp drop to $111,244.00, which is the third-lowest month of the year.
•	Profit experiences a significant surge in the final quarter, leading to the two highest months of the year October ($159,816.00) and December ($159,816.00)
•	November ($116,169.00) is an unexpected dip between the high points of October and December.
Pre Insights
•	The trend is clearly seasonal, with the highest profit occurring in the final quarter (Q4). The October and December peaks suggest a strong reliance on holiday sales or year-end budgeting/spending by customers. This Q4 focus should be central to planning.
•	The months of January ($110K), August ($111K), and November ($116K) represent the lowest profit months.
•	The August slump is typical of a "summer holiday" effect where customer purchasing slows down.
•	The November dip, situated between the two highest profit months (Oct and Dec), is highly unusual and warrants investigation. This could be due to inventory issues, aggressive holiday sales starting late in the month, or a specific marketing gap.
•	The consistent growth from January to March indicates good momentum at the start of the year. This pattern suggests that Q1 is a critical time for building a base that will carry the business through the potentially slower summer months.

Top 6 Customers
Observation
•	Logan Hatfield and Stanley Manning are tied for the highest profit, both generating $8,640.00.
•	Cory Evans follows closely with $7,786.00, and Nicolas Johnson is next with $7,198.00.
•	Melisa Thomas and Marie Thomas generated the lowest profits among the top six, at $5,275.00 and $3,698.00, respectively.
Pre Insights
•	The business relies heavily on a small group of customers for a significant portion of its total profit. The two top customers (Logan Hatfield and Stanley Manning) alone account for over 41% of the top 6 customers' profit and should be treated as VIP accounts with dedicated retention strategies.
•	Since the profit contribution is so concentrated, the loss of even one or two of the top customers would have an immediate and substantial negative impact on the overall profitability of the business. Retention efforts, loyalty programs, and relationship management should be a top priority for all six customers on this list.
•	Marie Thomas has the lowest profit contribution on the list. A targeted investigation may reveal if this customer is new, if their purchasing frequency has dropped, or if there is an opportunity to quickly increase their order value or volume to align more closely with Melisa Thomas.

Payment Mode Analysis 
Observation
•	Debit Card is the most profitable payment mode, contributing $375,721.00 to the total profit.
•	Credit Card follows closely with $349,392.00.
•	UPI (Unified Payments Interface) holds the third position at $333,889.00.
•	The two least profitable modes are EMI (Equated Monthly Installment) at $295,951.00 and COD (Cash on Delivery) at $255,744.00. Debit and Credit Cards combined account for a significant portion of the total profit, indicating a strong preference for traditional plastic card payments.
Pre Insights
•	The combination of Debit Card and Credit Card payments drives the largest share of profit. This suggests the customer base is highly comfortable with, or perhaps incentivized to use, card transactions. The payment gateway should be optimized to ensure low failure rates and a seamless experience for these methods.
•	EMI contributes a solid amount, suggesting that offering financing options successfully enables higher-value purchases (which typically translate to higher profit). Exploring ways to promote EMI options, especially for the high-value product categories (Furniture/Electronics), could boost overall profit.
•	COD, being the lowest contributor, is likely associated with lower-value transactions or customers who are less digitally integrated. While it contributes the least, it's an essential option for market segments that prefer or require it. Efforts should focus on either encouraging COD users to switch to digital methods or increasing the average order value of COD transactions.


Top 5 Cities
 Observation
•	Orlando is the clear leader, generating $128,125.00 in profit.
•	Buffalo follows with $111,823.00.
•	The remaining three cities are very closely grouped in terms of profit: Raleigh: $109,799.00Rochester: $109,729.00San Francisco: $108,106.00
Pre Insights
•	Orlando is the dominant profit driver, suggesting it has either a very large customer base, a high concentration of high-value customers, or a highly effective regional sales team/strategy. This city should be prioritized for marketing investment and operational support.
•	The profit figures for the bottom three cities (Raleigh, Rochester, San Francisco) are almost identical. This suggests that marginal improvements in performance in any of these cities could easily change their ranking. Targeted, small-scale initiatives could be tested in these markets.
•	Buffalo's position as the second-highest profit generator should be investigated to understand what drives its success. If it's a scalable strategy (e.g., specific advertising or product focus), it could be replicated in the cities below it.
Data Visualizations and Charts
Product Category Performance
 <img width="2322" height="1072" alt="FEDEX PRODUCT CATE  PERF" src="https://github.com/user-attachments/assets/ce1060eb-9f0b-4248-b650-69bf0fc186df" />


The Bar Chart displays the Sum of Profit across three main product categories with Office Supplies leading at $551,575.00 (Dark shade). Furniture the second most profitable at $540,542.00 (mid-shade) and Electronics the least profitable at $518,580.00 (Light shade).
The visual representation provides a relative comparison of profitability among the core product categories. It shows which category is the top performer (Office supplies) and the lowest performer (Electronics) in terms of total profit generated.

Payment Mode Distribution
<img width="2399" height="1019" alt="FEDEX SALES TREND REPORT" src="https://github.com/user-attachments/assets/604629ba-65c9-4c3b-b860-8f53625e9bd3" />

 

The Pie Chart displays the payment mode distribution distributed across five different payment modes, Debit card leading at $375,721.00 (23.3%), Credit Card at $349,392.00 (21.7%), UPI at $333,889.00 (20.7%), EMI at $295,951.00 (18.4%) and COD at $255,744.00 (15.8%).
This Visualization shows the proportionate contribution of each payment mode to the overall profit. It highlights the relative importance of each mode by segment size, allowing for a quick visual comparison of which methods are driving the most revenue.

Sales Trend Report
<img width="2399" height="1019" alt="FEDEX SALES TREND REPORT" src="https://github.com/user-attachments/assets/4eb48d53-70e1-4128-b472-0c5aef81a053" />

 
The chart is a line graph that visualizes the Sum of Profit on a monthly basis across an entire year. January at $110,381.00, February at $118,941.00, March at $152,739.00, April $139,373.00, May at $129,023.00, June at $141,845.00, July $132,137.00, August $143,289.00, September at $111,244.00, October at $155,154.00, November at $116,169.00 and December at $159,816.00.

This visualization illustrates the profit trend over time, specifically showing seasonality, fluctuations, and peaks/troughs throughout the year. It allows for the identification of the best and worst performing months

Top 5 Cities
<img width="2129" height="1007" alt="FEDEX TOP 5 CITIES" src="https://github.com/user-attachments/assets/dcabc32e-7516-48a7-adfd-d0f94ebf5da9" />

 
The bar charts display the sum of Profit generated from the five best performing cities, Orlando generated $128,125.00, Buffalo generated $111,823.00, Raleigh generated $109,799.00, Rochester generated $109,729.00 and San Francisco generated $109,729.00.

This visualization clearly highlights the leading city, Orlando, and shows how the profits generated by the other four cities stack up against each other.

Product Category by Quantity
<img width="2054" height="930" alt="FEDEX QUANTITY" src="https://github.com/user-attachments/assets/0e0dbeea-935d-4f42-af2d-7f46a0ae7c20" />

 
The Pie chart visualizes the distribution of the count of Quantity across three Furniture at 4,441 units sold, Electronics at 4,258 units sold and Office supplies at 4,046 units sold.

This visualization shows which category has the highest unit movement and the relative volume contribution of each product line to the total units sold.

Top 6 Customers
<img width="2106" height="1113" alt="FEDEX TOP 6 CITIES" src="https://github.com/user-attachments/assets/c50d5b09-e08e-46ba-9b25-76614e715564" />

 
The bar charts show the Sum of Profit contributed by the six customers who generated the highest profit, Logan Matthews generated $8,640, Stephanie Manning generated $8,640, Cory Evans generated $7,790, Dr. Austin Gentry generated $7,275.00, Nicholas Robinson generated $7,198.00 and Monica Thomas generated $7,139.00.

This visualization identifies and rank most profitable customers, allowing for an understanding of the concentration of profit within the customer base. This information is vital for customer relationship management (CRM) and targeted marketing efforts.
Observations and Recommendations
Observations
•	The highest-profit product category is Office Supplies  generated $551,575, despite having the lowest sales volume of count Quantity sold 4,046, Conversely, Furniture is the volume leader Quantity 4,441 unit sold, but only the second most profitable. This clearly indicates that profitability is driven by high-margin products, not just quantity sold.
•	The business is highly seasonal, with the fourth quarter (Q4) being the absolute peak. The top two months, December generated $159,816 and October generated $155,154, are significantly higher than the lowest months, such as January $110,381, and November $116,169. The dip in November, following a strong October, is an unusual anomaly that requires attention.
•	Key customers and cities are driving disproportionate value. The top 6 customers alone contribute a significant sum $47,141 for just six individuals. Similarly, the top city, Orlando generated $128,125, far exceeds the profit contribution of many other regions.
•	The vast majority of business transactions fall into the low-value bracket. Nearly half of all transactions (581 out of 1,194, or 48.7%) are in the $0-999 range, confirming a business model built on a high volume of small-to-mid-sized orders.
•	The most profitable payment channel is the Debit Card ($375,721), followed closely by Credit Card. The lowest-performing channel is COD (Cash on Delivery ($255,744), which typically involves higher handling and fraud risk.
Recommendations
•	Immediately launch a product-level profitability review to understand the cost structure of the Furniture category. The goal should be to either increase its average selling price or negotiate better vendor pricing to bring its profit margin in line with its high sales volume. Simultaneously, ensure that high-margin sub-categories like Markers ($174,749) receive primary focus in all inventory management and marketing efforts.
•	Develop a comprehensive Q4 Peak Season Strategy. This must involve securing inventory and optimizing logistics capacity starting in Q3 (July/August). Specifically, investigate the cause of the unusual profit dip in November and allocate a strategic marketing push during that month to bridge the gap between the high-performing October and December.
•	Create an Exclusive Customer Loyalty and City Development Program. For the top 6 customers, assign dedicated account managers or provide exclusive perks to secure their future high-value transactions. In top cities like Orlando, invest in localized marketing and potentially a larger physical/logistical footprint to cement market leadership and capture further demand.
•	Launch an Average Order Value (AOV) Optimization Strategy. Implement mandatory cross-selling prompts at the checkout for high-margin, low-weight accessories when a low-value item is purchased. Also, introduce tiered purchase incentives, such as free shipping only for orders over $1,000, to encourage customers to enter the next transaction bin.
•	Implement a small, targeted Payment Method Incentive. Offer a minor, immediate discount (e.g., 1-2%) or bonus loyalty points to customers who choose to pay via Debit Card, Credit Card, or UPI, thereby guiding transaction volume away from the costly and less profitable COD channel.
Conclusion
The analysis successfully validated the main drivers of the business's profitability: the high-margin Office Supplies category, a significant seasonal peak in Q4, and a strong revenue concentration in the Florida/New York corridor.
Limitation
Missing Cost of Goods Sold (COGS) and Operating Expenses: The dataset focuses on Sales and Profit. Without COGS, we cannot calculate the gross margin accurately. Without Operating Expenses (like labor, marketing spends, rent, etc.), the reported Profit is likely a Gross Profit or Operating Profit, making it impossible to determine the true Net Profit or the efficiency of different sales channels/regions.
Future Research
Profitability and Cost Analysis: Integrate COGS and operational expenses to determine the true Net Profit per Product, Sub-Category, and Customer.
References
Analytical Tools
•	Microsoft Excel
