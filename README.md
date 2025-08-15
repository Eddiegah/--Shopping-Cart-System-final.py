Ghana Shopping Cart System
Overview
The Ghana Shopping Cart System is a Python-based command-line application designed to simulate a shopping experience tailored for the Ghanaian market. This project demonstrates a robust, user-friendly system with a focus on functionality, aesthetics, and real-world applicability. It allows users to browse a categorized product catalog, manage a shopping cart, apply discounts, and generate detailed invoices, all presented in a visually appealing, color-coded terminal interface.
Project Highlights

Comprehensive Product Catalog: Features over 30 products across six categories (Fruits, Drinks, Dairy & Breakfast, Meats & Seafood, Staples & Cooking, Household) with prices in Ghana Cedis (GHS).
Advanced Cart Management: Supports adding, updating, and removing items with intuitive input validation to prevent errors.
Discount Logic: Implements "Buy N Get 1 Free" discounts for selected products (e.g., Apples, Bananas, Milk, Soap), showcasing real-world retail logic.
Polished Interface: Uses ANSI color codes for a vibrant, organized terminal display, enhancing user experience and presentation quality.
Error Handling: Robust input validation ensures the system handles invalid inputs gracefully (e.g., non-existent products, negative quantities).
Structured Code: Modular design with clear function separation for readability, maintainability, and extensibility.

Features

📦 Categorized Catalog: Products are grouped into intuitive categories for easy browsing.
🛒 Cart Operations: Add, view, update, or remove items with clear feedback.
💰 Dynamic Discounts: Automatically applies discounts during invoice generation for eligible products.
📃 Detailed Invoice: Generates a formatted invoice with subtotals, discounts, and a final total.
🎨 Color-Coded Output: Enhances readability with distinct colors for headers, categories, and statuses.
✅ Input Validation: Prevents errors with case-insensitive product searches and numeric quantity checks.

Installation

Clone the Repository:
git clone https://github.com/eegah/ghana-shopping-cart.git


Navigate to the Project Directory:
cd ghana-shopping-cart


Run the Program: Ensure Python 3.x is installed, then execute:
python shopping_cart_system.py



Requirements

Python 3.x: No additional libraries required, ensuring easy setup and compatibility.
Terminal with ANSI Support: For optimal display of color-coded output (most modern terminals support this).

Usage

Run the program: python shopping_cart_system.py.
Interact via the menu:
1) Display Catalog: View products by category with prices.
2) Add to Cart: Select products and quantities to add.
3) View Cart: Check current cart contents with subtotals.
4) Update/Remove from Cart: Modify quantities or remove items.
5) Print Invoice & Checkout: View the final invoice and confirm checkout.
6) Exit: Close the application.


Follow prompts for a seamless shopping experience.

Example Output
🌟 Welcome to the Ghana Shopping Cart System! 🌟
✨ Shopping Cart System - Features ✨
📦 Over 30 Ghana-market relevant products in categories
🛒 Add, update, and remove items easily
💰 Buy-N-Get-1-Free discounts on selected products
...

📌 Menu Options:
1) Display Catalog
2) Add to Cart
3) View Cart
4) Update/Remove from Cart
5) Print Invoice & Checkout
6) Exit

Choose an option (1-6):

File Structure

shopping_cart_system.py: Core script containing all logic, including catalog, cart management, and invoice generation.
README.md: This file, providing setup instructions and project details.

Future Improvements

GUI Integration: Add a graphical interface using Tkinter or a web framework like Flask for broader accessibility.
Database Support: Store products and user data in a database for scalability.
Additional Discounts: Introduce percentage-based discounts or bundle offers.
User Accounts: Implement user profiles for personalized shopping experiences.
Export Invoices: Allow users to save invoices as PDF or text files.

Notes

The product catalog and discount rules are hardcoded in catalog and discounts dictionaries for simplicity but can be extended or externalized (e.g., to a JSON file).
ANSI color codes enhance the terminal experience; ensure your terminal supports them (e.g., Windows Terminal, Linux terminals, or macOS Terminal).
The system is designed for ease of use and clarity, making it ideal for educational projects and demonstrations.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Author
[GROUP 25]GitHub:Eegah
