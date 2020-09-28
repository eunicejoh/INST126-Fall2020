# INST126-Fall2020

## Project 1: Calculator

### Overview
This Calculator program takes user input and performs basic operations of Addition, Subtraction, Multiplication, Division, Exponentiation, Floor, and Modulus.

### How It Works
The program will begin with the Calculator asking the user what operation they would like for it to perform (or if they would like to exit the program).
A list of options with a number corresponding to each of the seven operations will be provided, with exiting the program as the eighth option.

If the user selects a number that corresponds with an operation (ex. 1 for Addition), the user will be informed of which operation they chose. They then will be prompted to enter two whole integer values, positive or negative. The Calculator will then perform that operation and display the final answer.

Example:
Please choose an option (#): 1
Addition operation chosen.
Please enter your first number: 5
Please enter your second number: 6
5 + 6 = 11

Afterwards, the Calculator will ask the user to select another operation for the Calculator to perform. This will continue until the user selects option 8 (Quit).

If the user selects option 8, the Calculator will cease action and the program will end there.

### Assumptions
The Calculator will assume that the user:
- selects a valid option when asked (#s 1-8 only)
- inputs valid whole number integers (both positive and negative are accepted)
- will not enter the number 0 as their second number if they ask the Calculator to perform division

### Sample Outputs

