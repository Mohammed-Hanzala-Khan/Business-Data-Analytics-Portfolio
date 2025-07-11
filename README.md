# SKLAXIS-Store-Data-Analysis
*Optimizing Gaming Peripheral Stock and Pricing with Machine Learning and Power BI*

## Tools & Technologies Used
- Power BI for data visualization and interactive dashboards
- SAS Viya for advanced analytics and data cleaning
- Excel for initial data cleaning
- Octoparse for web scraping Amazon data
- Machine Learning models: Gradient Boosting, Linear Regression, Random Forest

## 📋 Table of Contents
- [Project Objective](#project-objective)
- [Dataset](#dataset)
- [Dataset Cleaning](#dataset-cleaning)
- [Visualization & Analysis](#visualization--analysis)
- [Conclusion & Recommendations](#conclusion--recommendations)

## 📈 Key Results
- Achieved **R² = 0.92** in predicting retail price drivers.
- Gradient Boosting model with **ASE = 0.1873** on rating prediction.
- F1 Score **0.88** on order type classification.
- Created an **interactive Power BI dashboard** for SKLAXIS's pricing and stock optimization.

## 📊 Dashboard Preview

![Image](https://github.com/Mohammed-Hanzala-Khan/SKALXIS-Sales-Optimization/blob/main/Dashboards-Model/Stock%20Optimization%20Dashboard.png)




## Project Objective
To derive SKLAXIS's success in the gaming peripheral market using machine learning and Power BI to optimize product selection, pricing, and stock management through data-driven insights

## Dataset
### Collection
### Dataset 1
<a href="https://github.com/Mohammed-Hanzala-Khan/SKALXIS-Sales-Optimization/blob/main/Dataset/SKLAXIS%20Store%20RAW.xlsx">Dataset</a>
- Collected using Octoparse from Amazon.com

### Dataset 2 
'PRODUCTANALYSIS' dataset consisting of 
- Price
- Cost
- Discount
- Quantity
- Order Type
- Region
- Profit
Collected from SAS Viyas's datasets

## Dataset Cleaning
Dataset 1 was imported into Excel for cleaning, whilst dataset 2 was cleaned using SAS Viya. The dataset cleaning process involved - 
- Removing irrelevant columns
- Removing rows with critical missing values (Price, rating)
- Removing duplicate product titles
- Adjusting for outliers


## Visualization & Analysis
### Dataset 1
### Power BI dashboard 
<a href="https://github.com/Mohammed-Hanzala-Khan/SKALXIS-Sales-Optimization/blob/main/Dashboards-Model/Stock%20Optimization%20Dashboard.png">Stock Optimization Dashboard</a>
* Visualizes gaming peripheral stock optimization for SKLAXIS.
* Shows brand share (Logitech, Razer, Corsair, SteelSeries, HyperX) for market analysis.
* Displays average rating by brand to identify high-performing products.
* Price vs. review volume scatterplot to analyze pricing vs. customer engagement.
* Interactive filters for company, rating, product type, and price range.
* Provides stock recommendations based on price and high ratings (5.0).

### Gradient Boosting (ASE = 0.1873)
<a href="https://github.com/Mohammed-Hanzala-Khan/SKALXIS-Sales-Optimization/blob/main/Dashboards-Model/Gradient%20Boosting%20Dataset%201.png">Gradient Boosting Model</a>

* Performed to analyze the factors influencing product rating using 50 trees
* The importance of price and review volume was highlighted

### Dataset 2

### Linear Regression (R^2 :0.92)
<a href="https://github.com/Mohammed-Hanzala-Khan/SKALXIS-Sales-Optimization/blob/main/Dashboards-Model/Linear%20Regression%20Dataset%202.png">Linear regression Model</a>

* Conducted to determine variables affecting a product's retail price'
* Identified Cost, profit, quantity ordered, discount, and seasonality as significant factors influencing retail Price


### Gradient Boosting (F1 = 0.880, 50 trees)
<a href="https://github.com/Mohammed-Hanzala-Khan/SKALXIS-Sales-Optimization/blob/main/Dashboards-Model/Gradient%20Boosting%20Dataset%202.png">Gradient Boosting Model</a>

* Conducted to identify the variables affecting an order type (Online or Physical)
* The insights gained from this analysis show us that the country in which a customer is located (score of 1186.3988) highly influences the type of order they would use. The product category was second in the hierarchy of importance, with a score of 1052.5160, letting us know that the type of product influences a customer’s order type. The product group came in third with a score of 564.1060. The remaining variables are in the following hierarchy order: Region name (1959466), state name (108.5353), product line (51.1445), year (44.2233), month (27.3823), quarter (20.5097), retail price (1.0928), and Product name (0.3576).

### Deep Learning

- <a href="https://github.com/Mohammed-Hanzala-Khan/SKALXIS-Sales-Optimization/blob/main/Dashboards-Model/Deep%20Learning/Deep%20Learning%201.png">Deep Learning Image 1</a>
- <a href="https://github.com/Mohammed-Hanzala-Khan/SKALXIS-Sales-Optimization/blob/main/Dashboards-Model/Deep%20Learning/Deep%20Learning%202.png">Deep Learning Image 2</a>
- <a href="https://github.com/Mohammed-Hanzala-Khan/SKALXIS-Sales-Optimization/blob/main/Dashboards-Model/Deep%20Learning/Deep%20Learning%203.png">Deep Learning Image 3</a>
- <a href="https://github.com/Mohammed-Hanzala-Khan/SKALXIS-Sales-Optimization/blob/main/Dashboards-Model/Deep%20Learning/Deep%20Learning%204.png">Deep Learning Image 4</a>

The Deep Learning model shows that 'Forest' is the Machine Learning model that performs the best out of the 3 with a KS score of 0.3209 using a total of 100 trees. A random forest machine learning model is a model that combines multiple decision trees to make a predictive analysis. From the above image, we can also see that the continent name is the variable with the highest importance, which shows similar results to gradient boost, where a customer’s order type highly depends on their location. Thus, to capitalize on this, SKLAXIS needs to develop their physical as well as online stores if they want to gain the maximum profits out of their gaming peripherals.

## Conclusion and Recommendation
- Stock the highest-rated brands to align with customer preferences.
- Implement dynamic pricing based on cost, seasonality, and demand.
- Expand online sales channels targeting countries with higher online order preferences while maintaining physical presence.
- Utilize the Power BI dashboards for continuous monitoring of sales, ratings, and inventory turnover for data-driven decisions.

## Future Work
- Incorporate real-time sales data for dynamic dashboard updates.
- Deploy the model into a pipeline to automate stock recommendations.
- Perform hyperparameter tuning on ML models to improve ASE and F1 scores.
- The ASC score obtained from dataset 1 for gradient boosting was very low, suggesting the requirement for further optimization of the data
  
