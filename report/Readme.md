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
There are 425 restaurants in 2 cities with 1432 menu items.
Using our visualization, it is possible to create rating of restaurants and menu items which have the highest number of orders.
With the aid of filter we can adjust the rating according to city.

On the Menu Item page we can analyze if the menu item brings enough revenue and has prospective to be sold further and how revenue responds to price adjustment.
Also, we can study preferences of customers and see that there are differences depending on the city.


