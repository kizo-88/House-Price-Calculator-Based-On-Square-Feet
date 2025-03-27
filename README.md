Here’s a simplified and more interactive version of the README for your "Buying or Selling House Calculation" program on GitHub:

---

# House Buying or Selling Calculator

Welcome to the **House Buying or Selling Calculator**! This program helps customers calculate how much they need to spend or how much money they will get when buying or selling a house.

## How it Works

Many people want to buy or sell a house after reaching age 20, but they often don’t know the cost or how much they will get. This tool helps by providing:

- A **price calculator** based on the size of the house.
- A **discount** if it's the customer's first time buying a house.
- A **household tax** added to the price when buying or selling.

### Age Requirement
- **Under 20**: You cannot buy or sell a house.
- **20 or older**: You are eligible to buy or sell a house.

### First-Time Buyers
- If it’s your **first time** buying a house, you’ll get a **10% discount** on the price!

## Tables for Price Calculation

### Table 1: Price Based on House Size (For Buying a House)

| Square Feet  | Price (RM)    |
|--------------|---------------|
| More than 2400 | RM 1,250,000  |
| 2101 - 2400    | RM 1,100,000  |
| 1801 - 2100    | RM 950,000    |
| 1501 - 1800    | RM 800,000    |
| 1201 - 1500    | RM 650,000    |
| 901 - 1200     | RM 500,000    |
| 1 - 900        | RM 350,000    |

### Table 2: Price Based on House Size (For Selling a House)

| Square Feet  | Price (RM)    |
|--------------|---------------|
| More than 2400 | RM 1,450,000  |
| 2101 - 2400    | RM 1,300,000  |
| 1801 - 2100    | RM 1,150,000  |
| 1501 - 1800    | RM 1,000,000  |
| 1201 - 1500    | RM 850,000    |
| 901 - 1200     | RM 700,000    |
| 1 - 900        | RM 500,000    |

---

### How to Use

1. **Enter your details**:
   - Agent’s name
   - Worker ID
   - Type of business (buy or sell)
   - Customer’s name and age
   - First time buying or selling?
   - Total square feet of the house

2. The program will display:
   - Customer's name and age
   - House price
   - Discount (if applicable)
   - Household tax
   - Final price

---

### Key Functions:

1. **Price Calculation**:  
   This function calculates the price based on the size of the house (square feet) and whether the user is buying or selling.

2. **Discount Calculation**:  
   If it's the **first time** buying, a 10% discount is applied. This function checks whether the user is a first-time buyer and applies the discount.

3. **Household Tax**:  
   This function calculates the **household tax** based on the price of the house.

4. **Final Price Calculation**:  
   The final price is calculated by adding the household tax to the price (for selling) or subtracting the discount and adding the tax (for buying).

---

### Example Flow

1. User enters:  
   - **Name**: John Doe  
   - **Age**: 25  
   - **First-time Buyer**: Yes  
   - **House Size**: 2000 sq ft  
   - **Type of Business**: Buy

2. The program returns:  
   - **House Price**: RM 950,000  
   - **Discount**: RM 95,000  
   - **Household Tax**: RM 5,000  
   - **Final Price**: RM 860,000

---

## Contributions

Feel free to fork, modify, and create pull requests to contribute to the project!

---

Let me know if you need any further adjustments or details for the README!
