# cis129_lab03_coffeeShop.py
# Practicing for lab 3
# Satya Dulam
print("**************************************")
print("Nick's Coffee and Muffin Shop")
# input the number of each item ordered
print("Number of coffees bought?")
numberCoffee = input()
print("Number of muffins bought?")
numberMuffin = input()
print("Number of scones bought?") 
numberScone = input()
print("Number of matchas bought?")
numberMatcha = input()
print("**************************************")
print("\n")
print("**************************************")
print("Nick's Coffee and Muffin Shop Receipt")
# price of each item set as constants and used to calculate the price of total items
COFFEE = 5.00
MUFFIN = 4.00
SCONE = 3.00
MATCHA = 6.00
totalCoffee = float(numberCoffee) * COFFEE
totalMuffin = float(numberMuffin) * MUFFIN
totalScone = float(numberScone) * SCONE
totalMatcha = float(numberMatcha) * MATCHA
print(numberCoffee, "coffee at $5 each:$", format(totalCoffee,'0.2f'))
print(numberMuffin, "muffin at $4 each:$", format(totalMuffin,'0.2f'))
print(numberScone, "scone at $3 each:$", format(totalScone,'0.2f'))
print(numberMatcha, "matcha at $6 each:$", format(totalMatcha,'0.2f'))
taxX = 0.06 * (totalCoffee + totalMuffin + totalMatcha + totalScone)
#after total amount is calculated, tax is calculated
print("6% tax:$", format(taxX,'0.2f'))
print("---------")
#total amount spent including tax 
totalReceipt = taxX + totalCoffee + totalMuffin + totalMatcha + totalScone
print("Total:$", round(totalReceipt,2))
print("**************************************")
print("Thank you! Come back again soon!")
