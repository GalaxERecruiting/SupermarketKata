# Supermarket Kata
## Problem Description
Calculate the total cost of the groceries in the shopping cart. 

* The shopping cart calculator should accept items in any order when scanned.
* Items should be scanned in to the shopping cart calculator by an identifier.
* Items should have a price. Prices can be for each item (1 = $2), or the weight of the item ($1.99/pound)
  * each items must be exact count
  * weighted items are sold in ounces, but may be priced in ounces or pounds
* Items sold may have a special price based on the quatity purchased, which applies only to the exact quantity or multiples of that quantity. Weighted items can not be sold with special pricing.
  * For example: 
    * 1 = $2, 2 = $4, 3 = $5, 4 = $7, 5 = $9, 6 = $10
    * Buy 2 get 1 free
    * Buy 10 for $10
* The shopping cart calculator should provide an itemized receipt including original price, discounts applied, and the total cost for all items in the cart.
