# Robot-Barista
#Creating a coffee shop Barista robot. The robot will greet the customer, take the order, and serve the coffee.

#Lets start by creating a function that will greet the customer.

print("Hello! Welcome to the Yvonne coffee shop!")

name = input("what is your name? ")

print("Hello " + name + ", thank you for coming in today!\n\n")

menu = "1. Black Coffee\n"  "2. Espresso\n" "3. Latte\n" "4. Cappuccino\n" "5. Americano\n" "6. Macchiato\n" "7. Mocha\n" "8. Tea\n" "9. Hot Chocolate\n" "10. Chai\n" "11. Hot Water\n"

print(name + ", What would you like from our menu today? Here is what we are serving.\n" + menu )

order = input()
price = 6
quantity = input("How many " + order + " Would you like?")
total = price * int(quantity)
print("Thank you. Your total is: N " + str(total))

print("Sounds good " + name + ", we'll have that " + order + " ready for you in a moment.\n")

#creating Variables named int(price) and str(quantity)
#Program the Robot to ask many cups the customer wants
#Program the do total costing 

