# Banking System Application

## Application Description
This is a mini-banking system application built in Java that simulates basic banking functionalities. It is a console-based program that allows users to manage customer accounts. The application enables the user to perform the following operations:

1. **Display All Account Details**: View details of all existing bank accounts.
2. **Search by Account Number**: Look up a specific account by its account number.
3. **Deposit Amount**: Add money to a customer's account.
4. **Withdraw Amount**: Withdraw money from a customer's account, provided there is sufficient balance.
5. **Exit**: Exit the application.

### Key Features
- Account management for multiple customers.
- Deposit and withdrawal functionalities with balance checks.
- Search functionality to quickly find account details.
- Easy-to-use console interface.

### Prerequisites
- Java Development Kit (JDK) installed.
- A Java IDE or a command-line environment for execution.

## Getting Started

### Steps to Run the Application
1. Clone the repository or download the source code files.
   ```bash
   git clone https://github.com/sandbox259/BankApp.git
   ```

2. Navigate to the project directory.
   ```bash
   cd BankApp
   ```

3. Compile the Java files.
   ```bash
   javac BankingApp.java
   ```

4. Run the application.
   ```bash
   java BankingApp
   ```

5. Follow the on-screen prompts to use the application.

## Program Flow
1. The user specifies how many customers they want to add initially.
2. The program prompts for details such as account number, account type, customer name, and initial balance.
3. A menu is displayed, allowing the user to:
   - View all account details.
   - Search for a specific account.
   - Perform deposit and withdrawal operations.
   - Exit the application.

## Example
### Sample Input/Output:
```text
How many number of customers do you want to input? 2

Enter Account No: 1010
Enter Account type: Savings
Enter Name: Aibani
Enter Balance: 5000

Enter Account No: 102
Enter Account type: Current
Enter Name: Samee
Enter Balance: 10000

***Banking System Application***
1. Display all account details
2. Search by Account number
3. Deposit the amount
4. Withdraw the amount
5. Exit
Enter your choice: 1

Name of account holder: Aibani
Account no.: 1010
Account type: Savings
Balance: 5000

Name of account holder: Samee
Account no.: 102
Account type: Current
Balance: 10000
```

## Contributing
Feel free to fork this repository and make improvements. Submit a pull request if you have any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

