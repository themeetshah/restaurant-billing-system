# 🍽️ Restaurant Billing System

A Java **console** application that simulates a food ordering and billing system. It allows customers to view a menu, place orders, select a payment method (cash/card), and receive a receipt with itemized billing.


## 📜 Features

- Display a detailed food menu with prices
- Take multiple item orders with quantities
- Calculate total price and quantity dynamically
- Validate user inputs like card number and phone number
- Support payment via **Cash** or **Card**
- Generate a formatted receipt with customer details

---

## 🧾 Menu Items

| Item       | Price (₹) |
|------------|-----------|
| Burger     | 50        |
| Pizza      | 60        |
| Sandwich   | 80        |
| Misal      | 100       |
| Dosa       | 110       |
| Pasta      | 120       |
| Biryani    | 180       |


## ▶️ How to Run

1. **Compile** the project:
   ```
   javac BillingSystem.java
   ```

2. **Run** the program:

    ```
    java BillingSystem
    ```

3. **Follow on-screen** prompts:

    - View the menu

    - Place your order by choosing item numbers and quantities

    - Enter personal and payment details

    - Receive your receipt at the end

### 🧍 Customer Flow
1. View the menu

2. Select number of items to order

3. Input item numbers and their quantities

4. Enter name, address, and 10-digit phone number

5. Choose payment method:

    - Cash: Instant success

    - Card: Validates 16-digit number

6. View receipt with order summary and payment status

### 💳 Payment Validation
- Card Payment requires:

    - 16-digit numeric card number

    - Input validation to ensure only digits are accepted

- Phone Number requires:

    - Exactly 10 digits

    - Numeric-only input

## 📂 Project Structure
```
BillingSystem.java  
# Main class with menu, order, customer, and receipt logic
```

## 🛠️ Technologies Used
- Java

- Scanner for I/O

- Object-Oriented Programming

    - Classes: Menu, Customer, Order, BillingSystem

- Arrays for order history tracking

## 📌 Notes
- Input validation ensures robust error handling for card and phone number entries.

- Order ends automatically when selected number of items are added or "0" is entered.

- Receipt includes customer details, order summary, and total bill.

## 💡 Future Enhancements
- Add support for multiple customers or sessions

- Store order history in files or a database

- GUI version using JavaFX or Swing

- Implement discounts, taxes, and loyalty points

## 🤝 Contribute to Restaurant Billing System  

Feel free to contribute to Restaurant Billing System by creating [**pull requests**](https://github.com/themeetshah/restaurant-billing-system/pulls) or [submitting issues](https://github.com/themeetshah/restaurant-billing-system/issues).  

---

### 👨‍💻 Developed by [**Meet Shah**](https://github.com/themeetshah)