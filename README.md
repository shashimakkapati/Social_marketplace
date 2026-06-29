# OOPS Project - Marketplace Simulation

A simple console-based marketplace built in C++.  
It lets users register, log in, follow other users, list products, browse products, add items to a cart, and checkout.

## What It Does

This project simulates a small online marketplace with the following features:

- User registration and login.
- Follow and unfollow other users.
- List products for sale.
- Browse products from followed sellers.
- Add and remove items from a cart.
- View cart total and checkout.
- Update product price for products you own.
- Track user balance and product stock.

## How to Run

### Requirements
- A C++ compiler that supports C++17.
- Example compiler: `g++`

### Compile
```bash
g++ -std=c++17 main.cpp -o main
```

### Run
```bash
./main
```

### How to Use
- Start the program and use the menu options shown on screen.
- Register a new user or log in with an existing one.
- Follow other users to see their products.
- Browse products, add items to your cart, and checkout.
- Use the "My Listings" section to add your own products or change their prices.

## Object-Oriented Concepts Used

This project uses some basic object-oriented programming ideas:

- **Classes**: The program is divided into classes like `User`, `Product`, `Cart`, and `Marketplace`.
- **Objects**: Real data is stored using objects made from those classes.
- **Encapsulation**: Each class keeps its own data and actions together.
- **Methods**: Each class has functions for specific actions, like adding to cart or listing a product.
- **Ownership checks**: Only the seller of a product can change its price.
- **Data handling**: Users, products, and carts are stored and managed in a structured way.

## Main Classes

- `Product` - stores product details like name, price, and stock.
- `Cart` - stores items added by the user.
- `User` - stores user details, balance, followed users, and cart.
- `Marketplace` - manages users, products, login, browsing, and checkout.

## Notes

- This is a simple learning project.
- Data is not saved permanently, so everything resets when the program closes.
- Passwords are stored in plain text for simplicity.
