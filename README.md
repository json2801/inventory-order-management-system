Inventory & Order Management System

A Python and MySQL-based application for managing products, inventory, customers, and orders.

Features

- Product management
- Customer management
- Inventory/stock management
- Order creation and management
- Automatic stock updates
- Product search
- Order history
- Input validation
- Exception handling
- MySQL database integration
- Unit testing

Technologies Used

- Python
- MySQL
- SQL
- Object-Oriented Programming
- Pytest
- python-dotenv
- Git & GitHub

Project Structure

inventory-order-management-system/
│
├── main.py
├── requirements.txt
├── .gitignore
├── README.md

Database

The application uses MySQL to store:

- Products
- Customers
- Orders
- Order items
- Inventory information

Setup

1. Clone the repository

git clone https://github.com/json2801//inventory-order-management-system.git
cd inventory-order-management-system

2. Create a virtual environment

python -m venv venv

Activate it on Windows:

venv\Scripts\activate

3. Install dependencies

pip install -r requirements.txt

4. Configure MySQL

Create the required database and configure your database credentials in a ".env" file.

Example:

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=password
DB_NAME=inventory_db

5. Run the application

python main.py

6. Run tests

pytest

Security

Database credentials are stored in environment variables and are not committed to GitHub.

Author

Johnson.Y

GitHub: https://github.com/json2801/
