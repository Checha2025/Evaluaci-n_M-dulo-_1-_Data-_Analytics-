# INVENTORY MANAGEMENT SYSTEM 
# BY CECILIA MARTINEZ GANDOLFO

#Python program to manage products stock: it uses a list of dictionaries to keep track of everything and handles logic for updating stock and prices automatically.

# ESTRUCTURE
The whole prohect work around global list called invetorty. Each item is a dictionary making easy the access to the data.
# 1 - Data Normalization: I used .strip().lower() to avoid having the same product twice because of tha capitla letter or an extra space.
# 2 - Adding Products:  Instead of just appending everything, the code checks if the product is already there.
# 3-  Search and delete: For searching and deleting, I used a for loop to go through the inventory

# FUNCTIONS
# add_product_________________________________Normalizes text + loops to check if it exists + updates or appends
# display_invetory____________________________Loop to print every dict
# find_product________________________________Loops trrough the list and compares the search names with the store ones
# delete_product______________________________Finds de product by the names and uses inventory.remove()
# inventory_value_____________________________Accumulator pattern: total+= price * quanty
# shopping_cart_______________________________ add_product_add update de stock
# shopping_cart_______________________________ view_cart_ shows everything the costumer is about to buy and thr final price
# shopping_cart_______________________________ inventory_value_ calculate the total stuff in the inventory

# 	QUICK START GUIDE

# 1. First you have to add some products to the inventory, for that propouse you have de add_product function.
    # Example add_product Syntax: add_prduct( "name", price, quanty) / ("Socks", 14, 34)
# 2. Then you can see the full list of products and their prices, just call the display funcction
		# display_inventory
# 3 . Shopping Cart, shopping_cart()
			# Add items to cart
			#The code automatically rests that amount from the total stock
# 4 . Search and delete
			# find_product ("socks)
			# delete_product ("jeans")
																			

