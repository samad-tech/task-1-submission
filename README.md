Class Declaration:
The code is in a public class named Calculator.

Method Definitions:
Four static methods are defined for basic arithmetic operations:
add(double a, double b)
subtract(double a, double b)
multiply(double a, double b)
divide(double a, double b)

User Input & Menu:
It uses a Scanner object to take input from the user.
A menu is displayed repeatedly to let the user choose an operation.

Loop for Continuity:
A while loop allows the calculator to run continuously until the user chooses to exit.

Switch Statement:
Based on the user’s choice, a corresponding method is called to perform the operation.

Exit Option:
Choosing option 5 exits the loop and ends the program.

Error Handling:
Division by zero is handled using a check to avoid runtime errors.
   Start Program:


    WORKING MECHANISM
   
Program execution begins in the main() method.

Displays a welcome message.
Enter Loop:
The while (keepRunning) loop starts, allowing repeated operations.

Display Menu:
User is shown a menu of options (1 to 5).

User Makes a Choice:
User enters a number corresponding to the operation they want.
This input is read using scanner.nextInt().

Exit Condition:
If the user chooses 5, the loop breaks and the program exits.

Input Operands:
If a valid operation is chosen (1–4), the user is prompted to enter two numbers (operands).

Perform Operation:
A switch statement executes the corresponding method:
Addition: add(num1, num2)
Subtraction: subtract(num1, num2)
Multiplication: multiply(num1, num2)
Division: divide(num1, num2) (with zero-check)

Show Result:
The result is printed to the console.
If dividing by zero, an error message is displayed instead of the result.

Repeat or Exit:
Loop continues unless the user chooses to exit.

Close Scanner:
Once exited, the Scanner is closed to release resources.

