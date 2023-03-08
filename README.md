# EGabriel-Task-Challenges
# Stage Two Task
You are to develop a banking software application for a major bank. Your banking applications will include 6 modules, namely
**“signup, login, deposit and withdraw, view balance, get account summary”.**
You are to create signup and login modules. The sign-up collects information from the user while the login cross verifies the input
with the registered information which would be save in a txt file as your database. The login will let the verified user access
further banking operation such as **deposit and withdraw, view balance, view account summary.**
**Signup**
This method will ask the user to register him/herself by providing personal information in the form field or attributes
which are Username, Email, Age, Phone, and Password.
For this assessment there is no restriction on form fields or attributes.
When all given fields provided by the user are entered, you can validate the sign-up by trying to log in using the same
credentials.
If any field is empty in the signup process, your software must prompt the user to enter all details correctly.
Once you can sign up and login using your software program, you can provide evidence of code and all screenshots to
demonstrate your work.
**Login**
Create a Bank class with the name (Bank) which can handle login and signup.
You need to create a “login” method which takes two arguments – username and password - which will then be cross
verified by the program. If user credentials do not match, it shows an error and requests the user to re-enter the
credentials. If credentials are verified, then the application will take the user to the main screen.
You should restrict the password attempts to 3 wrong trials.
For security reasons, it is often necessary to limit the password attempts to 3 or less.
**Deposit**
Add a ‘deposit’ method to the Bank class. Your program should prompt the user to enter the amount to deposit to the
bank. Once a valid deposit information is received (e.g., no negative value and non-numerical value), your program is to
add the deposit amount to your total balance.
The user can deposit multiple times until select to Quit the program.
**View balance**
They should be able to see the updated balance amount after every transaction.
**Withdraw**
This method will ask the user to enter the amount to withdraw. If the withdrawal input amount is valid (e.g., nonnegative and only numerical value), the withdrawal amount should be deducted from the total balance. If the total
balance becomes negative, the withdraw request should not be processed. The program should display ‘not sufficient
fund available’ message.
**View account Summary**
The user should be able to see all transactions carried out in the format below.
E.g. Deposit Date: 2/4/2023 12:00:00 AM === Deposit Amount :5000 === Current Balance In Account: 5000.
**(Transaction Date, Deposited Amount, Current Balance)**
-
