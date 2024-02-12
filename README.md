# cis129_lab03_coffeeShop.py
# Practicing for lab 3
# Satya Dulam
print("**************************************")
print("Nick's Coffee and Muffin Shop")
print("Number of coffees bought?")
numberCoffee = input()
print("Number of muffins bought!")
numberMuffin = input()
print("**************************************")
print("\n")
print("**************************************")
print("Nick's Coffee and Muffin Shop Receipt")
priceCoffee = 5.00
priceMuffin = 4.00
totalCoffee = float(numberCoffee) * priceCoffee
totalMuffin = float(numberMuffin) * priceMuffin
print(numberCoffee, "coffee at $5 each: $", totalCoffee)
print(numberMuffin, "coffee at $4 each: $", totalMuffin)
taxX = 0.06 * (totalCoffee + totalMuffin)
print("6% tax: $", taxX)
print("---------")
totalReceipt = taxX + totalCoffee + totalMuffin
print("Total:$", round(totalReceipt,2))
print("**************************************")
