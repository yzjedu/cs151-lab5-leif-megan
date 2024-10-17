# Algorithm Document

1. Set the starting balance of the account to 1000
2. Set sentinel to "e"
3. Output introductory message to user, which includes the user's starting balance (always $1000)
4. Create option variable and assign it empty string
5. While forever (until sentinel is selected):
   1. There are four possible routes for the program: Deposit, Withdraw, View Balance, and Exit. While the selected route is not Deposit, Withdraw, View Balance, or Exit:
       1. Request the user input one of the three options expressed with the first letter (D, W, V, or E)
      2. Convert the input to lowercase
      3. If the user does not input a valid option, output an error message to the user and remind them of the accepted inputs
   2. If the user input is equal to d:
        1. Request the user input the amount of money they wish to deposit to the account
      2. If the user input is greater than 0.0099999...:
            * Add the input number to the users current balance
            * Otherwise, output an error message explaining that the input value is invalid
   3. Otherwise, if the user input is equal to w:
        1. Request the user input the amount of money they wish to withdraw from the account
      2. If the user input is greater than 0.0099999...:
            * Subtract the input number from the users current balance
            * Otherwise, output an error message explaining that the input value is invalid
   4. Otherwise, if the user input is equal to v, print the current balance of the account to the user
   
      
