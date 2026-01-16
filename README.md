# Simple Grocery Price Calculator

## Objective
The purpose of this assignment is to practice:

* Writing modular Python programs with functions
* Using a `main()` function to control program flow
* Implementing input validation using `try/except`
* Working with dictionaries to store and access data
* Formatting output neatly for the user

## Program Requirements

You must write a Python program that calculates the **total cost** for a customer buying multiple grocery items.

## 1. Item Price Data

Inside the `main()` function, create a **dictionary** with at least 5 grocery items and their prices.

Example structure:
{
    "apple": 0.75,
    "banana": 0.50,
    "bread": 2.25,
    "milk": 3.00,
    "eggs": 2.50
}

* **Key:** item name (string)
* **Value:** item price (float)

## 2. Display Available Items

Create a function that:

* Accepts the dictionary of items
* Prints all items and their prices in a neatly formatted table
* Does **not** prompt the user for input

## 3. User Input – Item Selection

Create a function that:

* Asks the user how many different items they want to buy

* For each item:

  * Prompts the user to enter the item name
  * Uses `try/except` to handle invalid input (e.g., item not in dictionary)
  * Prompts the user to enter the quantity
  * Validates that the quantity is a positive integer

* Returns a dictionary of the selected items and quantities

## 4️. Calculate Total Cost

Inside `main()`:

* For each item selected, multiply the quantity by the price
* Sum the total cost of all items

## 5. Display Results

The program should display:

* A table of items bought, their quantity, and individual cost
* The total cost
* All values formatted to **two decimal places**

## 6️. Program Structure Requirements

Your program **must**:

* Use a `main()` function
* Use separate functions for:

  * Displaying the item list
  * Gathering user input
  * Calculating total cost (optional: could be in `main()`)

## 7️. Error Handling Requirements

* All user input must be validated using `try/except`
* Prevent negative quantities
* Show clear error messages if invalid input is entered

## Expected Program Flow

1. Display available grocery items and prices
2. Prompt user for how many items they want to buy
3. For each item:

   * Ask for the item name
   * Ask for quantity
4. Calculate total cost
5. Display a receipt with all details
* Must run without modification
* No external files needed

## How it's made:
Developed with Python
