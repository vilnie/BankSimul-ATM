# group_1

<img src="er-diagram.png">


The ATM Simulator is a software application that enables users to withdraw money. The application is designed to simulate the functions of an ATM machine. The software has been developed using JavaScript to create a REST API, and Qt Creator to create the frontend. The data is stored in a MySQL database that has four tables: card, owner, account, and transactions.
Features

The ATM Simulator offers the following features:

    Withdraw money
    Check account balance
    View transaction history
    User login/logout
    Serial port communication

 # Installation

To install the ATM Simulator, follow these steps:

Clone the repository:

git clone https://github.com/username/repo-name.git

    Install the required dependencies:

    MySQL server (Uni Server)
    Qt Creator (QSerial might not work every Qt version)
    JavaScript
    Postman/SQLworkbench
    Node.js

    Set up the MySQL database:

    Create a database named my_db
    
    Import the database schema from the dbdump.sql file

    Start the application:

    Run the frontend.exe file in Qt Creator

Usage

To use the ATM Simulator, follow these steps:

    Insert your card into the card reader. You can bypass this by modifying frontend code.
    Enter your PIN code
    Select the bank account
    Select the desired transaction (e.g., withdraw money)
    Enter the transaction amount
    Wait for the transaction to complete
    Wait for automatic log out

Contributing

Contributions to the ATM Simulator are welcome. If you find a bug or have a feature request, please open an issue on the GitHub repository.
License

The ATM Simulator is open-source software licensed under the MIT license. See the LICENSE file for more information.

