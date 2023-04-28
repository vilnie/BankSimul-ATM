# group_1

<img src="er-diagram.png">

ATM Simulator
The ATM Simulator is a software application that enables users to withdraw money. The application is designed to simulate the functions of an ATM machine. The software has been developed using JavaScript to create a REST API, and Qt Creator (C++) to create the frontend. The data is stored in a MySQL database that has four tables: card, owner, account, and transactions.
Features
The ATM Simulator offers the following features:
•	Withdraw money
•	Check account balance
•	View transaction history
•	User login/logout
•	Serial port communication
Installation
To install the ATM Simulator, follow these steps:
1.	Clone the repository:
bash
git clone https://github.com/username/repo-name.git
2.	Install the required dependencies:
•	MySQL server (Uni Server)
•	Qt Creator
•	JavaScript
3.	Set up the MySQL database:
•	Create a database named my_db
•	Import the database schema from the database-schema.sql file
4.	Start the application:
•	Run the frontend.exe file in Qt Creator
Usage
To use the ATM Simulator, follow these steps:
1.	Insert your card into the card reader. If you don’t have one, you can bypass by modifying the frontend code.
2.	Enter your PIN code
3.	Select the desired bank account
4.	Select the desired action. (withdraw or transactions history)
5.	Make withdraw
6.	Wait for the transaction to complete
7.	Wait for automatic log out
Contributing
Contributions to the ATM Simulator are welcome. If you find a bug or have a feature request, please open an issue on the GitHub repository.
License
The ATM Simulator is open-source software licensed under the MIT license. See the LICENSE file for more information.

