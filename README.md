#welcoming the customer
print("Welcome!!!!!!!")

#asking the customer what there name is and assigning it to a variable so it doesnt get forgotten for later
name = input("What is your name?")

#assining what the menu is to a variable for the next step
menu = "chicken, fruit salad, double combo cheeseburger"

#asking the customer what they want and then showing the variable that is the menu
print(name + ", what would you like from our menu? Here is what we are serveing today. " + menu)

#assigning what the customer's order into a variable
order = input()

#saying what the price for everthing is (easy)
price = 7

#assigning how many of their orders they want
quantity = input("How many " + order + "s" + " would you like?")

#assigning what the total price for that customer is
total = price * int(quantity)

#thanking the customer and saying what their total is
print("Thank you! You total is: $" + str(total))

#just saying that their order will be ready in a few minutes
print("Alright " + name + ", we will have that " + order + " ready for you in a few minutes.")
