# Excel-SQL-Data-Analysis-Project


# 🍕 Pizza Sales Analysis 

***This project is a comprehensive analysis of pizza sales data using SQL and Excel to uncover key business insights and trends. 
The dataset includes information about orders, pizzas sold, categories, sizes, and sales revenue, 
making it an excellent resource for practicing data analysis and SQL query writing***

### 📊 Key Performance Indicators (KPIs)                        
**Total Revenue**: Calculated the total sales revenue.                                                                                                                                                       
**Average Order Value**: Determined the average revenue per order.                                                                                                                                                  
**Total Pizzas Sold**: Summed the total number of pizzas sold.                                                                                                                                                      
**Total Orders**: Counted the distinct orders placed.                                                                                                                                                    
**Average Pizzas Per Order**: Calculated the average number of pizzas per order.                                                                                                                      
  
### 📈 Analytical Insights
**A. Daily Trend Analysis**                                                                                                                                                                                        
Identified trends in order volume by day of the week.                                                                                                                                                          
**B. Hourly Trend Analysis**                                                                                                                                                                                
Explored order patterns by hour to understand peak business times.                                                                                                                                      
**C. Category-Wise Sales Analysis**                                                                                                                                                      
Analyzed the percentage of sales revenue contributed by each pizza category.                                                                                                                          
**D. Size-Wise Sales Analysis**                                                                                                                                                    
Evaluated the percentage of sales revenue by pizza size.                                                                                                                                                  
**E. Monthly Trends**                                                                                                                                                                            
Analyzed pizza category performance for specific months (e.g., February).                                                                                                                                    

### 🥇 Best and Worst Sellers                                                                                                
**Top 5 Best Sellers:** Identified the most popular pizzas based on the total quantity sold.                                                                                                                        
**Bottom 5 Best Sellers:** Highlighted the least popular pizzas based on sales.                                                                                                                  


## 🛠️ Tools Used                                                                                                      
### SQL:                                                                                                              
Used SQL queries to calculate KPIs, identify trends, and perform category- and size-based analyses.                                                                            
Filtered data by month, quarter, and week for detailed insights.                                                                                                                    
### Excel:                                                                                                                                                
Visualized trends and summarized data for reports and dashboards.                                                                                                

### 📂 Project Structure
**SQL Queries:** Contains detailed SQL scripts for analysis.                                                                                                        
**Excel Workbooks:** Includes data visualizations and pivot tables for additional insights.                                                                                      

### Documentation: Step-by-step explanations of queries and their outputs.                                                                                          
### 📝 Sample Queries
**Total Revenue:**
SELECT SUM(total_price) AS Total_Revenue FROM pizza_sales;  

**Daily Trend for Orders:**
SELECT DATENAME(DW, order_date) AS order_day, COUNT(DISTINCT order_id) AS total_orders  
FROM pizza_sales GROUP BY DATENAME(DW, order_date);  

**Top 5 Best Sellers:**
SELECT TOP 5 pizza_name, SUM(quantity) AS Total_Pizza_Sold  
FROM pizza_sales GROUP BY pizza_name ORDER BY Total_Pizza_Sold DESC;  

### 🌟 Key Takeaways
**This project demonstrates the ability to:**
*Analyze business data using SQL.                                                                                          
Extract actionable insights through structured queries.                                                                                                    
Combine SQL and Excel to present data-driven solutions.*                                                                                                                            


D:\PowerBI+SQL\Pizza Excel+SQL

