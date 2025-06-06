# Adidas-Sales-Performance-Analysis-Excel-

![Image](https://github.com/user-attachments/assets/2244d94f-547d-4df6-8923-d8542c4d90b3)

## **Introduction:**

Adidas, a global leader in the sportswear industry, is evaluating its sales performance across products, regions, retailers, and sales channels. Despite a strong overall sales figure of $899.9 million and a profit of over $332 million, the management seeks deeper insights into which products and regions are driving performance, how retailers and sales methods contribute to revenue, and how seasonal trends affect unit sales.

The marketing and operations teams are particularly interested in:

* Identifying top-performing and underperforming product categories.

* Understanding geographic market contributions.

* Optimizing sales strategies across different sales methods and retail channels.

* Leveraging time-based sales trends for demand forecasting and promotional planning.

## **Objectives of the project:**

**1. Product Performance Evaluation:**

* Compare unit sales and revenue across product categories.

* Identify the best-selling and least-performing product lines.

**2.  Geographic Sales Insights:**

* Analyze total sales distribution across regions and top 10 cities.

* Determine which cities and regions contribute most to overall revenue.

**3. Retailer Impact Assessment:**

* Evaluate sales volume by retailer (e.g., West Gear, Foot Locker, Walmart).

* Provide recommendations on which retailers to strengthen or optimize partnerships with.

 **4. Sales Channel Effectiveness:**

* Compare unit sales across In-store, Online, and Outlet methods.

* Identify the most profitable and scalable channels.

**5. Monthly Sales Trends:**

* Detect peak and off-peak months for strategic planning.

* Understand seasonality and its impact on sales volume.

**6. Performance Benchmarking:**

* Track overall key metrics such as Total Units Sold, Total Sales, Profit, and Average Price.

* Establish benchmarks for future performance comparisons.

## Data Dictionary:

This dataset contains detailed sales transaction data for Adidas products sold through Foot Locker in New York. It includes information on product categories, sales channels, pricing, revenue, and profit metrics.

| *Column Name*       | *Data Type* | *Description*                                                                 |
|------------------------|---------------|----------------------------------------------------------------------------------|
| Retailer             | Text          | The name of the retail partner selling the product (e.g., Foot Locker).         |
| Retailer ID          | Integer       | A unique identifier for the retailer or the transaction batch.                  |
| Invoice Date         | Date          | The date on which the transaction was recorded (MM/DD/YYYY).                    |
| Region               | Text          | The broader geographic region where the transaction took place.                 |
| State                | Text          | The specific state within the region (e.g., New York).                          |
| City                 | Text          | The city where the sales occurred.                                              |
| Product              | Text          | The type of product sold (e.g., Men's Apparel, Women's Street Footwear).       |
| Price per Unit       | Currency      | The selling price of a single unit of the product (in USD).                     |
| Units Sold           | Integer       | The total number of product units sold in the transaction.                      |
| Total Sales          | Currency      | The total revenue generated from the sale (Price × Units Sold).                 |
| Operating Profit     | Currency      | The profit generated after subtracting operating costs from total sales.        |
| Operating Margin     | Percentage    | The percentage of sales that turned into profit: (Operating Profit / Sales).    |

## Methodology:

### Data Preparation and Visualisation:

**1. Remove Empty/Meta Rows:**

•	Drop the first 3 rows that contain metadata.

•	Reset the header using the fourth row (index 3).

**2.  Rename Columns:**

•	Use row 4 (index 3) to set meaningful column names like:
Retailer, Retailer ID, Invoice Date, Region, State, City, Product, Price per Unit, Units Sold, Total Sales, Operating Profit, Operating Margin, Sales Method

**3. Drop Null or Empty Rows:**

•	After header adjustment, drop rows that are completely null or mostly null.

**4. Convert Data Types:**

•	Ensure numeric columns (Price per Unit, Units Sold, Total Sales, etc.) are in the correct format.

•	Parse the Invoice Date column into datetime.

  ### Cleaning Steps Applied:

  1.	Removed metadata rows (top 3 rows).

2.	Renamed columns using the correct header row.

3.	Dropped fully empty rows.

4.	Converted column types:

*	Invoice Date → datetime

*	Price per Unit, Units Sold, Total Sales, Operating Profit, Operating Margin → numeric types

5.	Dropped duplicate rows.


   ### Preview Of Data before Cleaning:

   ![image](https://github.com/user-attachments/assets/da30f370-0bd8-45c3-b709-8b35b9429049)

   

### Preview of data after Cleaning:

![image](https://github.com/user-attachments/assets/375833a6-8da0-4862-96b3-2b0526500f0f)

### Pivot Table:

![image](https://github.com/user-attachments/assets/505786f0-7d4b-4f54-be91-b96fb3671456)

### Visualization:

![image](https://github.com/user-attachments/assets/719ea025-af93-4bfc-aae5-37a6d93681ce)

## Visualization Insights:

1. Top Performing Product: Men's Street Footwear is the highest revenue generator at $208,826.24

  2. Gender Comparison: 

   * Men's products collectively outperform women's (Men's total: $486,228.55 vs Women's total: $358,255.37)
     
  * The gap is most pronounced in street footwear ($208,826 vs $128,003)

    ### Category Performance:
    
  1. Street footwear outperforms athletic footwear for both genders
     
  2. Apparel sales are stronger for men than women

### Sales by Month Analysis

### The monthly sales data shows:

  * Sales show significant growth over time (from ~70M to over 690M)

   * There appears to be seasonal peaks (reaching highest points at year-end)
  
   * The growth trajectory suggests strong year-over-year performance


## **Recommendations:**

**1.	Optimize High-Profit Products Across Regions:**

Focus marketing efforts on Men's Street Footwear and similar high-margin products, especially in regions like the Northeast, which show consistently strong sales and profitability.

**2.	Expand Online Sales Channels:**
   
Although in-store sales dominate, the data suggests growing potential for online sales. Investing in digital marketing and e-commerce logistics could increase overall sales and market reach.

**3.	Target Underperforming Cities with Promotions:**

Cities with lower sales but high population density (e.g., Dallas, Phoenix) could benefit from localized promotions or retail partnerships to boost visibility and engagement.

**4.	Use Dynamic Pricing Based on Sales Performance:**

Implement price optimization for products with consistent high volume but lower margins to improve profitability without sacrificing volume.

**5.	Leverage Seasonal Sales Trends:**

Sales show noticeable fluctuations across months—suggesting seasonal patterns. Adidas should align marketing campaigns and stock levels with these trends to maximize revenue during peak periods.


![image](https://github.com/user-attachments/assets/a93ae9f9-5523-4e96-9698-aadf01f4b695)

For any collaborative work or gigs, reach out to me at:

📧 Email: Bosschuks97@gmail.com  📞: 07064106675




     

















 








