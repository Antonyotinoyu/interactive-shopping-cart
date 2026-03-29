# Shopping Cart & Discount Calculator

## Description
A simple, interactive browser-based JavaScript application that acts as a shopping cart calculator. It prompts the user to enter products, calculates individual product totals, and applies conditional discounts based on the final cart subtotal.

## Features
- **Interactive Prompts:** Uses browser `prompt()` dialogs to collect product information (name, price, and quantity).
- **Input Validation:** Ensures prices are strictly greater than 0 and quantities are 1 or more, prompting the user again if invalid data is entered.
- **Dynamic Discount System:** Automatically calculates discounts based on the total purchase amount.
- **Real-time Output:** Prints the receipt dynamically onto the web page using HTML and CSS for a clean look.

## Technologies Used
- HTML5
- JavaScript (Vanilla)
- CSS (Internal basic styling)

## How to Run
1. Clone this repository or download the `index.html` file to your local machine.
2. Double-click the `index.html` file to open it in any modern web browser (e.g., Chrome, Firefox, Edge, Safari).
3. Follow the on-screen prompts to add items to your cart and see the calculated total!

## Discount Rules
The application evaluates the final shopping cart total and applies the following rules:
- **1000 TL and above:** 10% Discount
- **Between 500 TL and 999 TL:** 5% Discount
- **Under 500 TL:** No discount applied

## Example Flow
1. The user is asked how many different products they want to enter.
2. For each product, the user enters the item's name, price, and total quantity.
3. The program computes the subtotal for each item.
4. Discounts are checked and applied if applicable.
5. The final receipt and the total amount to be paid are rendered directly onto the HTML page.
