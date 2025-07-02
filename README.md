# SKLAXIS-Store-Data-Analysis
## Project Objective
To derive SKLAXIS's success in the gaming peripheral market using machine learning and Power BI to optimize product selection, pricing, and stock management through data-driven insights

## Dataset 1 Used (Collected Using Octoparse from Amazon.com)
<a href="https://github.com/Mohammed-Hanzala-Khan/Business-Data-Analytics-Portfolio/blob/main/SKLAXIS's%20Store%20Raw%20Data.xlsx">Dataset</a>

## Dataset 2 
'PRODUCTANALYSIS' dataset from SAS Viya, containing 951.7K rows with variables including-
Price
Cost
Discount
Quantity
Order Type
Region
Profit


## Visualization & Analysis
### Dataset 1
### Power BI dashboard 
<a href="https://github.com/Mohammed-Hanzala-Khan/Business-Data-Analytics-Portfolio/blob/main/SKLAXIS%20Powe%20Bi%20dashboard.png">Stock Optimization Dashboard</a>
* Visualizes gaming peripheral stock optimization for SKLAXIS.
* Shows brand share (Logitech, Razer, Corsair, SteelSeries, HyperX) for market analysis.
* Displays average rating by brand to identify high-performing products.
* Price vs. review volume scatterplot to analyze pricing vs. customer engagement.
* Interactive filters for company, rating, product type, and price range.
* Provides stock recommendations based on price and high ratings (5.0).

### Gradient Boosting (ASE = 0.1873)
<a href="https://github.com/Mohammed-Hanzala-Khan/Business-Data-Analytics-Portfolio/blob/main/Snapshot%20of%20Gradient%20boosting%20-%20Rating%201%2007-09-2023%20at%203.31.32%20AM.png">Gradient Boosting Model</a>

* Performed to analyze the factors influencing product rating using 50 trees
* Importance of price, and review volume were highlighted

### Linear Regression (R^2 :0.92)
<a href="https://github.com/Mohammed-Hanzala-Khan/Business-Data-Analytics-Portfolio/blob/main/Snapshot%20of%20Linear%20regression%20-%20Retail%20Price%201%2007-09-2023%20at%203.57.33%20AM.png">Linear regression Model</a>

* Conducted to determine variables affecting a products 'retail price'
* Identified Cost, profit, quantity ordered, discount, and sesionality as significant factors influencing retail Price

### Dataset 2
### Gradient Boosting
<a href="https://github.com/Mohammed-Hanzala-Khan/Business-Data-Analytics-Portfolio/blob/main/Snapshot%20of%20Gradient%20boosting%20-%20Rating%201%2007-09-2023%20at%203.31.32%20AM.png">Gradient Boosting Model</a>


  
