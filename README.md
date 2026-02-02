# STEP BY STEP PROCEDURE TO EXECUTE THE PROJECT
1. Install all requirements.txt file
2. Create a database with name trading_db
3. Perform trading_db.sql commands on your database
4. Run index.php code


Interface will look like this. If you not registered register and click on login with your credentials

![Screenshot (15)](https://github.com/user-attachments/assets/1445c2f2-ccbb-4ec6-bb28-7cfd3f7d0900)

After successfull login you will see the interface like below 👇👇
![Screenshot (16)](https://github.com/user-attachments/assets/b7da049f-2bf2-4e67-85ea-7f54d13e375f)
# tradeEassy

tradeEassy is a PHP and MySQL-based web application that simulates a basic stock trading platform.  
It allows users to register, log in, buy and sell stocks, view their portfolio, track transactions, and calculate profit or loss.

This project is built to demonstrate backend web development, database integration, and core trading workflow logic.

---

## Objectives
- To understand PHP–MySQL integration
- To implement CRUD operations in a real-world use case
- To simulate basic stock trading operations
- To design a simple web-based trading system

---

## Technologies Used
- **Frontend:** HTML, CSS  
- **Backend:** PHP  
- **Database:** MySQL  
- **Server:** Apache (XAMPP / similar)  
- **Deployment:** Vercel (for demo hosting)

---

## Features
- User registration and login
- Dashboard overview
- Buy and sell stocks
- Portfolio management
- Transaction history tracking
- Profit and loss calculation
- Database-backed persistent storage

---

## Project Architecture
This project follows a **2-Tier Architecture**:
1. **Application Layer:** PHP-based web application  
2. **Data Layer:** MySQL database  

The frontend and backend logic are handled together using PHP, which communicates directly with the database.

---

## Project Structure
tradeEassy/
│
├── assets/ # Static assets (CSS, images, etc.)
├── includes/ # Database connection and reusable PHP files
│ └── db.php
├── index.php # Login page
├── register.php # User registration
├── dashboard.php # User dashboard
├── buy.php # Buy stocks
├── sell.php # Sell stocks
├── view_portfolio.php # Portfolio overview
├── view_transactions.php # Transaction history
├── profit_loss.php # Profit and loss calculation
├── README.md
├── LICENSE
└── vercel.json # Deployment configuration


---

## How to Run the Project (Local Setup)

### Step 1: Install Requirements
- Install **XAMPP** or any Apache + MySQL server
- Start **Apache** and **MySQL**

---

### Step 2: Database Setup
1. Create a database in MySQL (example: `tradeeassy`)
2. Create required tables for:
   - users
   - stocks
   - transactions
   - portfolio
3. Update database credentials in:
includes/db.php


---

### Step 3: Run the Application
- Place the project folder inside:
htdocs/

- Open browser and visit:
http://localhost/tradeEassy/


---

## Live Demo
🔗 https://tradeeassy.vercel.app

*(Note: Live demo may use limited or sample data)*

---

## Limitations
- No real-time market data
- No API-based stock prices
- No advanced authentication or encryption
- Intended for educational purposes only

---

## Future Enhancements
- Integration with real stock market APIs
- Secure authentication and password hashing
- Role-based access control
- Improved UI using modern frameworks
- Real-time price updates

---

## Conclusion
tradeEassy demonstrates the core working of a trading platform by combining PHP backend logic with MySQL database management.  
It provides practical exposure to web development, database operations, and system design concepts.

---

## Author
**Varun Balaji Ankinapalli**
