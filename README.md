# cake_Baby

The purpose of this project was implementing an application for the employees of a cake shop to calculate the total price that they will have to pay to get all the ingredients for the desired quantity of any of the two recipes that the cake shop offers.

In my code I implemented a function that calculates the total price of both recipes and then do the following simple math expression: totalPrice = priceR1*quantity1 + priceR2*quantity2 to get the total price. So if we click on the ‘Calculate total price’ button this total price will be displayed.

￼If we want to know the price that we have to invert in each supplier and the amount of each ingredient that we have to buy to each of them, we will click on the calculate price per supplier button.

To achieve this I had to create four arrays with 8 positions each (one array for each recipe for each supplier). Each position in the array represents the quantity of a product from the products array (inducted from the adata1.json document provided). Doing this, I could get the total number of each ingredient that the employees will have to buy to each supplier to be able to cook the number of each recipe specified.
￼
