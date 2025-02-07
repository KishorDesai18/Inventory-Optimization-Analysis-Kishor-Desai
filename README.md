# Inventory-Optimization-Analysis-Kishor-Desai
**Inventory Optimization Analytics Project**  

This project focuses on inventory optimization using time-series forecasting and advanced KPIs. The goal is to reduce stockouts, optimize inventory levels, and improve supply chain efficiency using data-driven insights.  

**Dataset Description**  
The dataset contains 365 days of inventory tracking for 500 unique products, simulating real-world inventory trends. It includes:  

**Columns:**  

•	ProductID: Unique identifier for each product.  
•	Date: Daily tracking of inventory and demand.  
•	Demand: Number of units required per day (with trends and seasonality).  
•	StockLevel: Current available stock for the product.  
•	ReplenishmentLeadTime: Number of days required for stock replenishment.  
•	CostPerUnit: Cost per unit of the product.  

**KPIs and Their Importance**  

The project calculates 10 key performance indicators (KPIs) for inventory optimization:  

**1. Stockout Rate (%)**  
•	Formula: (Days with Stock = 0) / (Total Days) × 100  
•	Purpose: Identifies frequently out-of-stock products to prevent revenue loss.

**2. Demand Variability**  
•	Formula: Standard deviation of daily demand.  
•	Purpose: Helps determine safety stock levels for high-variance products.

**3. Reorder Point**  
•	Formula: (Average Demand × Lead Time) + Safety Stock  
•	Purpose: Ensures stock is replenished before running out.

**4. Inventory Turnover Ratio**  
•	Formula: Total Demand / Average Stock Level  
•	Purpose: Measures how efficiently inventory is sold and replaced.

**5. Fill Rate**  
•	Formula: 1 - (Stockout Days / Total Days)  
•	Purpose: Tracks how well demand is met without stockouts.

**6. Economic Order Quantity (EOQ)**  
•	Formula: sqrt((2 × Demand × Ordering Cost) / Holding Cost per Unit)  
•	Purpose: Determines the optimal order size to minimize costs.

**7. Days of Supply**  
•	Formula: Stock Level / Average Daily Demand  
•	Purpose: Estimates how long current stock will last without replenishment.

**8. Dead Stock Percentage**  
•	Formula: (Days with Excess Stock / Total Days) × 100  
•	Purpose: Identifies slow-moving products that occupy storage space.

**9. Revenue Lost Due to Stockouts**  
•	Formula: Stockout Days × Avg Cost per Unit  
•	Purpose: Quantifies revenue loss due to inventory shortages.

**10. Safety Stock Calculation**  
•	Formula: 1.65 × Std Dev(Demand) × sqrt(Lead Time)  
•	Purpose: Ensures extra stock for unexpected demand spikes.  
