# 🛒 Online Shopping Management System

This is a simple **console-based shopping management system** written in C++. It allows users to simulate a basic shopping cart experience with the ability to:

- Add products from a CSV-based product catalog
- Remove products from the cart
- View a dynamically generated bill with total cost

---

## 📦 Features

- ✅ Load products from a CSV file
- 🛒 Add products to cart
- ❌ Remove items from cart
- 💸 Generate and display a bill with the total amount
- 📂 File handling for product data (`Products.csv`)
- 🧾 Clean and structured object-oriented design using classes

---

## 🗂️ File Structure

```bash
.
├── expl.cpp           # Main source code for the project
├── Products.csv       # CSV file containing available product names and prices
```

🧾 Products.csv Format
Each product should be listed in the format:
```bash
ProductName,Price
```

Example:
```bash
Pen,10
Notebook,50
Eraser,5
```

🛠️ How to Compile and Run
1. Compile
```bash
g++ expl.cpp -o shopping
```

2. Run
```bash
./shopping
```

💡 How It Works
Once you run the program, you’ll see a menu:
```bash
Main Menu:
1. Add Product to Cart
2. Show Bill
3. Remove Product from Cart
0. Exit
```

➕ Add Product
Enter the name of a product listed in Products.csv.

If it exists, it's added to your cart.

➖ Remove Product
Enter the name of the product you want to remove from the cart.

📃 Show Bill
Displays a list of items in the cart with their individual prices and total amount.

❗ Notes
Input is case-sensitive. Make sure the product names match exactly.

The system does not support quantity or multiple units of the same product (one entry per item).

Designed for a single-user session in the terminal.

🧑‍💻 Author & License
Made with ❤️ for educational purposes.

This project is open-source and available under the MIT License.

