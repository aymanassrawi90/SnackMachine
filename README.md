# SnackMachine

Introduction
Vending machines can be be of different types. Some vending machines are dedicated to coffee, some are dedicated to drinks, and others are dedicated to snacks. For this assignment, you will implement a Snack Vending machine. 

Deliverables:
1.	Implement the SnackMachine class

Specifications of the Snack Machine 
The Snack Machine has the following characteristics:
•	Money Slots: the machine accepts money of the following types:
o	CoinSlot: There are four denominations: • 10c • 20c • 50c • $1 
	Valid coin slot should be in appsetting 
o	Notes Slot :20$ and 50$ only
	Valid slot should be in appsetting file 
o	Machine only accepts USD currency
	Hint: currency should be in appseting file 
•	Snack Slots
o	The machine has five rows to display snack items.
o	Each row has 5 columns to pile the items.
o	Each column has a number.
•	Keypad
Users can select the items to be purchased using a keypad.

 
Purchase a Snack Use Case

Basic Flow
1.	This use case begins when the customer wants to purchase snacks.
2.	The customer selects a number by pressing on the keypad. 
3.	The VM displays a message that the snack is available for the selected number and displays its price.
4.	The customer inserts the money.
5.	The VM validates the money.
6.	The VM accepts the money. 
7.	The VM displays the accumulated amount of money each time a new money is entered.
8.	The VM monitors the amount of the accepted money, If the money is enough, the VM dispenses the selected snack to the customer. 
9.	The VM determines if any change should be sent back to customer.
10.	The VM displays the change at panel. 
11.	Then, the VM dispenses change.

[ P.S You are required to come up with alternative scenarios to this basic flow.]
