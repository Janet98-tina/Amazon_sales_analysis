Amazon Sales Data Analysis
________________________________________
Project Overview
This project involves analyzing Amazon sales data to uncover key insights about product performance, sales trends, and customer behavior. Using Python and libraries such as pandas, matplotlib, and seaborn, the analysis includes data cleaning, exploration, visualization, and interpretation of sales patterns over time.
________________________________________
Files Included
•	Amazon_Sales_Analysis.ipynb
Jupyter Notebook containing step-by-step data analysis, including code, visualizations, and commentary.
•	amazon_sales_data.csv
The dataset used for the analysis. It contains sales records such as product details, sales quantities, prices, dates, and regional information.
________________________________________
How to Use
1.	Clone or download this repository to your local machine.
2.	Open the Jupyter Notebook file (Amazon_Sales_Analysis.ipynb) using Jupyter Notebook or JupyterLab.
3.	Ensure the following Python libraries are installed:
o	pandas
o	matplotlib
o	seaborn
o	numpy
pip install pandas matplotlib seaborn numpy
________________________________________
Findings and Insights
1.	Regions with the Highest Sales Revenue
o	Sub-Saharan Africa recorded the highest total sales revenue.
o	Asia had the lowest, suggesting limited market penetration or customer base.
2.	Average Unit Price and Unit Cost by Item Type
o	Household items had the highest average unit price.
o	Office supplies had the highest average unit cost, indicating potentially lower profit margins or higher production costs.
3.	Country with the Highest Total Profit
o	Djibouti had the highest total profit among all countries analyzed, suggesting either high sales volumes, efficient operations, or better profit margins.
4.	Sales Channel and Order Priority Distribution
o	Offline channel: Most common order priority is ‘H’ (High).
o	Online channel: Most common order priority is ‘L’ (Low).
This reflects the nature of purchases—offline may serve business customers or bulk buyers, while online handles more casual or individual orders.
5.	Average Order Processing Time
o	Both online and offline channels had the same average order processing time, indicating consistent operational efficiency.
6.	Item Types with the Highest and Lowest Total Sales
o	Highest: Cosmetics—likely due to repeat purchases or a wide customer base.
o	Lowest: Fruits—possibly due to perishability or limited demand.
7.	Order Priority Across Different Regions
o	'H' priority is most frequent in every region except Asia, where 'L' is dominant.
o	Middle East and North Africa had no records of 'C' (Critical) order priority.
8.	Correlation Between Unit Price and Total Profit
o	The correlation coefficient between Unit Price and Total Profit is 0.557.
This indicates a moderate positive correlation, meaning that as unit prices increase, profit tends to increase as well—though not perfectly. It suggests pricing strategy does influence profitability, but other factors (like cost and volume) are also at play.
9.	Sales Data Seasonal Patterns
o	February had the highest total revenue, which may be tied to seasonal campaigns, new year promotions, or other events.
o	August had the lowest, possibly reflecting a sales dip during off-peak months.
10.	Number of Units Sold Across Countries
•	São Tomé and Príncipe and Djibouti recorded the highest number of units sold.
These countries show strong market engagement despite smaller populations, which might reflect niche demand or strong customer loyalty.
________________________________________
Recommendations
Based on the insights above, here are actionable recommendations for Amazon or similar retailers:
1.	Expand in Asia
Focus marketing and product diversification efforts in Asia to boost revenue, as it's currently underperforming compared to other regions.
2.	Optimize Pricing Strategy
Since unit price is moderately correlated with profit, consider adjusting prices strategically, particularly for items with high cost but low return.
3.	Boost Fruit Sales
Consider seasonal promotions, bundles, or repositioning for fruit products to increase their visibility and appeal.
4.	Target High-Profit Countries
Further develop the market in Djibouti and São Tomé and Príncipe—explore why these countries perform well and replicate strategies elsewhere.
5.	Enhance Online Sales Priority
Online sales skew toward low-priority orders. Consider implementing incentives for bulk or priority orders via online channels.
6.	Plan for Seasonal Fluctuations
Use February as a model for successful sales campaigns and plan proactive strategies for traditionally slower months like August.
7.	Reduce Cost in Office Supplies
Explore supply chain optimizations or sourcing alternatives to lower the high unit cost of office supplies.
________________________________________
Conclusion
This analysis demonstrates how data-driven insights can support better business decisions in sales strategy, marketing, and inventory planning. The findings offer a basis for Amazon to improve profitability, customer engagement, and operational performance across different markets.
