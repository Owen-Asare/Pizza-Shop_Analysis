Pizza Place Sales
A year's worth of sales from a fictious pizza place including the date and time of each order and the pizzas served with aditional details on the type, size, quantity and ingredients.

**Recommended Analysis**
* How many customers do we have each day? 
* Are there any peak hours?
* How many pizzas are typically in an order? 
* Do we have any bestsellers?
* How much money did we make this year? 
* Can we identify any seasonality in the sales?
* Are there any pizzas we should take off the menu or any promotions we could leverage?

Data Dictionary
* order_id: A unique identifier for each order.
* date: The date of the order.
* time: The time of the order.
* order_details_id: Identifier for details related to the order.
* pizza_id: Identifier for the pizza.
* quantity: The quantity of pizzas ordered.
* pizza_type_id: Identifier for the type of pizza.
* size: The size of the pizza.
* price: The price of the pizza.
* name: The name of the pizza.
* category: The category of the pizza.
* ingredients: Ingredients used in the pizza.
* day: The day of the order.
* month: The month of the order.
* hour: The hour of the order.
* sales: Sales related information.

Data Preparation
* import the python libraries needed for the analysis and these are pandas, matplotlib and seaborn for visualisation.
Data was loaded into a dataframe from all the given tables.
the tables were merged on the keys that were foreign keys to each table.
I checked 
