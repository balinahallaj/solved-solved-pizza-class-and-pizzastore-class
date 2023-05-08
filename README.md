Download Link: https://assignmentchef.com/product/solved-solved-pizza-class-and-pizzastore-class
<br>
Create a class named pizza that stores the following information about a single pizza:1. pizza brand (only two brands: Pizza Hut or Domino’s) 2. size (two sizes are available: small or large) 3. number of toppings The class pizza should contain the followings:

● accessor methods (get methods) to get the instance variables (attributes).

● mutator methods (set methods) to set the instance variables (attributes).

● a method named calculateCost() which returns a float that is the cost of the pizza. Pizza cost is determined by: ○ Pizza Hut:

■ small: $10 + $1 per topping,

■ large: $14 + $3 per topping ○ Domino’s

■ small: $12 + $2 per topping

■ large: $16 + $3 per topping

● a method __str__(self) that returns the size, number of toppings and the cost of the pizza. Your main method (section) looks like this: p1 = Pizza (“Pizza Hut”, “small”, 3) print (p1) p2 = Pizza (“Domino’s”, “large”, 2) print (p2) The result should look like this: Pizza Hut; Small Pizza; Cost is $13 Domino’s; Large Pizza; Cost is $22

Create another class named PizzaStore. The class PizzaStore (sells all kinds of pizza brands) has the following attributes (instance variables):

● Name of the store

● List of pizza orders received. The class has the following methods:

● __init__ ● orderReceived (pizza)

● __str__ The main section should look like this: p1 = Pizza (“Pizza Hut”, small, 3) p2 = Pizza (“Domino’s”, large, 2) s1 = PizzaStore(“Pizza House”) s1.orderReceived(p1) s1.orderRecevied(p2) print(s1) The result (output) should look like: Pizza House has received the following order: small size, 3 toppings, Pizza Huts; large size, 2 toppings, Domino’s