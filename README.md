# StockTake

Follow these steps:
● Code a Python program that will read from the text file inventory.txt and perform the following on the data, to prepare for presentation to your managers:
o Create a file named inventory.py, where a Shoe class should be defined.
o Create a class named Shoes with the following attributes:
● country,
● code,
● product,
● cost, and
● Quantity.

Inside this class define the following function:
 
 ▪ get_cost - which return the cost of the shoe
▪ get_quanty - which return the quantity of the shoes
▪ __str__ - This function returns a string representation of a class.
o Outside this class create a variable with an empty list. This variable will be used to store a list of shoes objects
o Then you must define the following functions:
▪ read_shoes_data - this function will open the file inventory.txt and read the data from this file the create shoes object and append this object into the shoes list. one line in this file represents data to create one object of shoes. You must use the try except in this function for error handling.
▪ capture_shoes - this function will allow a user to capture data about a shoe and use this data to create a shoe object and append this object inside the shoe list.
▪ view_all - this function will iterate over all the shoes list and print the details of the shoes that you return from the __str__ function. (Optional: You can organise you data in a table format by using Python’s tabulate module )
▪ re_stock - this function will find the shoe object with the lowest quantity, which is the shoes that need to be restocked. Ask the user if he wants to add the quantity of these shoes and then update it. This quantity should be updated on the file for this shoe.
▪ seach_shoe - This function will search for a shoe from the list using the shoe code and return this object so that it will be printed
▪ value_per_item - this function will calculate the total value for each item . (Please keep the formula for value in mind; value = cost * quantity). Print this information on the console for all the shoes.
  
▪ highest_qty - Write code to determine the product with the highest quantity and print this shoe as being for sale.
o Now in your main create a menu that executes each function above. This menu should be inside the while loop. Be creative.
