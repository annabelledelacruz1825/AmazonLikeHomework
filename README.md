# AmazonLikeHomework
Create an Amazon-like storefront with the MySQL. The app will take in orders from customers and deplete stock from the store's inventory. Bonus task: Program the app to track product sales across the store's departments and then provide a summary of the highest-grossing departments in the store.


Installing
node.js and MySQL

The app uses the following dependencies: * mysql * word-wrap * cli-table * inquirer * colors

Running the app
Open a terminal window and run the following code:

For Customer View: node bamazonCustomer.js

customers can buy products from the store and calculates the total cost.
based on the the quanity purchased the database will be updated, depleting the stock.
For Manager View: node bamazonManager.js

managers are able to choose from the following menu options:
View Products for Sale: - the app lists every available item: the item IDs, names, prices, and quantities.
View Low Inventory: - the app lists all items with an inventory count lower than five.
Add to Inventory: - the app displays a prompt that will let the manager "add more" of any item currently in the store.
Add New Product: - the app allows the manager to add a completely new product to the store.
