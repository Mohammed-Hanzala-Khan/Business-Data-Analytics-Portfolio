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

### Dataset 2

### Linear Regression (R^2 :0.92)
<a href="https://github.com/Mohammed-Hanzala-Khan/Business-Data-Analytics-Portfolio/blob/main/Snapshot%20of%20Linear%20regression%20-%20Retail%20Price%201%2007-09-2023%20at%203.57.33%20AM.png">Linear regression Model</a>

* Conducted to determine variables affecting a products 'retail price'
* Identified Cost, profit, quantity ordered, discount, and sesionality as significant factors influencing retail Price


### Gradient Boosting (F1 = 0.880, 50 trees)
<a href="https://github.com/Mohammed-Hanzala-Khan/Business-Data-Analytics-Portfolio/blob/main/image_2025-07-02_234432642.png">Gradient Boosting Model</a>

* Conducted to identify the variables affecting an order type (Online or Physical)
* The insights gained from this analysis show us that the country in which a customer is located (score of 1186.3988) highly influences the type of order they would use. The product category was second in the hierarchy of importance with a score of 1052.5160 letting us know that the type of product influences a customer’s order type. The product group came in third with a score of 564.1060. The remaining variables are In the following hierarchy order Region name (1959466), state name (108.5353), product line (51.1445), year (44.2233), month (27.3823), quarter (20.5097), retail price (1.0928), and Product name (0.3576).

### Deep Learning

- <a href="https://github.com/Mohammed-Hanzala-Khan/Business-Data-Analytics-Portfolio/blob/main/Screenshot%202023-07-09%20at%205.15.16%20PM.png">Deep Learning model 1</a>
- <a href="https://github.com/Mohammed-Hanzala-Khan/Business-Data-Analytics-Portfolio/blob/main/Screenshot%202023-07-09%20at%205.15.03%20PM.png">Deep Learning model 2</a>
- <a href="https://github.com/Mohammed-Hanzala-Khan/Business-Data-Analytics-Portfolio/blob/main/Screenshot%202023-07-09%20at%205.14.52%20PM.png">Deep Learning model 3</a>
- <a href="https://github.com/Mohammed-Hanzala-Khan/Business-Data-Analytics-Portfolio/blob/main/Screenshot%202023-07-09%20at%205.14.35%20PM.png">Deep Learning model 4</a>

The Deep Learning model shows that 'Forest' is the Machine Learning model that performs the best out of the 3 with a KS score of 0.3209 using a total of 100 trees. A random forest machine learning model is a model that combines multiple decision trees to make a predictive analysis. From the above image, we can also see that continent name is the variable with the highest importance which shows similar results to gradient boost where a customer’s order type highly depends on their location. Thus, to capitalize on this, SKLAXIS need to develop their physical as well as online stores if they want to gain the maximum profits out of their gaming peripherals.


  
