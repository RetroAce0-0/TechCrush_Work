## 🍕 Pizza Place Sales Analysis

This project analyzes a full year's worth of sales data from a fictitious pizza restaurant. The goal is to gain business insights from the data using Python and pandas, and answer key analytical questions to support decision-making.

### 📁 Dataset Description
The dataset is composed of 4 CSV files:

  * orders.csv – Contains the order ID, date, and time.
  * order_details.csv – Contains order_id, pizza_id, and quantity.
  * pizzas.csv – Contains pizza_id, size, price, and pizza_type_id.
  * pizza_types.csv – Contains pizza_type_id, name, category, and ingredients.

A data dictionary is also provided for reference.

## Table 	         Field            	Description
* orders          |	order_id 	        | Unique identifier for each order placed by a t...
* orders 	        | date 	            | Date the order was placed (entered into the sy...
* orders 	        | time 	            | Time the order was placed (entered into the sy...
* order_details 	| order_details_id 	| Unique identifier for each pizza placed within...
* order_details 	| order_id 	        | Foreign key that ties the details in each orde...
* order_details 	| pizza_id 	        | Foreign key that ties the pizza ordered to its...
* order_details 	| quantity 	        | Quantity ordered for each pizza of the same ty...
* pizzas 	        | pizza_id 	        | Unique identifier for each pizza (constituted ...
* pizzas 	        | pizza_type_id 	  | Foreign key that ties each pizza to its broade...
* pizzas 	        | size 	            | Size of the pizza (Small, Medium, Large, X Lar...
* pizzas 	        | price 	          | Price of the pizza in USD
* pizza_types 	  | pizza_type_id 	  | Unique identifier for each pizza type
* pizza_types 	  | name 	            | Name of the pizza as shown in the menu
* pizza_types 	  | category 	        | Category that the pizza fall under in the menu...
* pizza_types 	  | ingredients 	    | Comma-delimited ingredients used in the pizza ...


### 🔧 Tools Used
* Python Programming
* Pandas 📊
* Matplotlib 📈
* Seaborn 🎨
* Jupyter Notebook 📒



* Here's a diagram of the architecture:

![Work Flowchart Diagram](https://github.com/RetroAce0-0/TechCrush_Work/blob/main/Flowchart%20for%20the%20Pizza%20Sales.png)

### 📊 Key Insights
* 💵 Total Revenue = $817860.05
* 🔢 Total Orders = 21350
* 🍕 Pizza types sold: 32
*  Average prices
* 🍕 Top 5 Bestselling Pizzas
* 🕒 Peak Hour for Sales
* 🗓️ Most Profitable Day of the Week
* 📉 Underperforming Pizza Types
* 📅 Sales Trends Across Months
* Most sold size and type of pizza
* Most sold and least sold types of pizza on a daily, weekly, and monthly basis over the year
