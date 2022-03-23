# Report


## Data source
Dataset from client includes following databases:
- Restaurants
- Orders
- Order-items
- Menu items (orderables)
- Customers' id's
- Customers' allergys  

## Data cleaning
During data analysis we noticed missing data and encoding errors which was cleaned and corrected with Pandas and Geopy libraries. 

## Data modeling 
- Adding new measurements using DAX.
- Creation of relationship between tables in dataset, using primary keys and fact keys.

### Visualization
We separated data findings into 3 categories and created a page for each of them.

#### Executive summary
This page provides an overview of orders and revenue based on the city, restaurant and menu items.

#### Menu items
This page displays parameters of each menu item including:
- Number of orders
- Weekly revenue
- Prediction of future revenue based on adjusted price or trend of orders
- Average price
- Comparison between amount of orders in different cities

#### Customer
This page presents analisys of data about customer: 
- Allergy status
- Amount of orders
- Revenue generated from the customer
- Time of order

## Result

