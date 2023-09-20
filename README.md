1.	This is a simple calculator program that allows the user to perform addition, subtraction, multiplication, and division. 
2.	The program starts by displaying a menu of options for the user to choose from. The menuLoad() function is responsible for displaying the menu and getting the user's choice. It takes a list of menu options as an argument and returns the user's choice as an integer. If the user enters an invalid choice, the function prints an error message and returns 99.
3.	The addition (), subtract (), multiply (), and divide () functions are the basic mathematical operations that the calculator can perform. Each function takes two numbers as arguments and returns the result of the operation.
4.	The main part of the program is a while loop that keeps running until the user chooses to exit. Inside the loop, the menuLoad() function is called to get the user's choice. If the choice is 0, the program prints a goodbye message and breaks out of the loop. If the choice is 99, the loop continues, and the menu is displayed again.
5.	If the user chooses a valid operation (1, 2, 3, or 4), the program prompts the user to enter two numbers. If the numbers are valid (numeric), they are converted to integers and the corresponding operation is performed using the appropriate function. The result is then displayed on the screen.
6.	If the user enters invalid numbers (not numeric), an error message is displayed.
7.	Overall, this program provides a simple interactive calculator that allows the user to perform basic mathematical operations.

