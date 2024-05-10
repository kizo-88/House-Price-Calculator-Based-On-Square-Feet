# House-Price-Calculator-Based-On-Square-Feet

Many people want to buy or sell a house after reaching age 20. Unfortunately, they don't know how much they have to spend or how much money they will get. You as a house agent, develop "Buying or Selling House Calculation" program. The customers will know how much they have to spend or how much they will get. There is a minimum age requirement to buy or sell a house. If a customer's age is more than equal to 20, they can buy or sell a house. If this is their first time buying a house, they will get a 10% discount, refer to Table 2. Customers can refer to Table 3 if they want to buy a house, and Table 4 if they want to sell a house. Household tax will be add if they want to buy or sell a house.
Age
Decision
Less than 20
You cannot buy or sell a house.
More than equal 20
You can buy or sell a house

Table 1
For First Time Buying
Get 10% Discount

Table 2
Square Feet
			Price
More Than 2400 
Price =square feet2700 RM 1250000
(2101-2400)
Price =square feet2700 RM 1100000
(1801-2100)
Price =square feet2700 RM 950000
(1501-1800)
Price =square feet2700 RM 800000
(1201-1500)
Price =square feet2700 RM 650000
(901-1200)
Price =square feet2700 RM 500000
(1-900)
Price =square feet2700 RM 350000

Table 3


Square Feet
			Price
More Than 2400 
Price =square feet2700 RM 1450000
(2101-2400)
Price =square feet2700 RM 1300000
(1801-2100)
Price =square feet2700 RM 1150000
(1501-1800)
Price =square feet2700 RM 1000000
(1201-1500)
Price =square feet2700 RM 850000
(901-1200)
Price =square feet2700 RM 700000
(1-900)
Price =square feet2700 RM 500000

Table 4
If they want to buy	(Final Price=price-discount+household tax)
If they want to sell	(Final Price=price+household tax)
The detailed description of each process and functions are given as follows:
The user needs to enter Agent’s name, worker ID, type of business (buy or sell), how much house user want to calculate, Customer’s name and age, first time to buy or sell a house, total square feet of the house. This function will display the customer’s name and age, price, discount price, household tax and final price.
First function responsible to calculate the price based on the house’s square feet. This function will receive a total square foot and type of business (buy or sell). Then, this will return the price to the main function.
Second function responsible to calculate the discount price based on the user’s decision on the “First time”. This function will receive a price and decision “First time”. Then, this will return the discount price.
Third function responsible to calculate the household tax. This function will receive a price. Then, this will return the household tax.
Forth function responsible to calculate the final price. This function will receive a price, discount, household tax and type of business (buy or sell).. Then, this will return the final price.
