**GAME**: This code is a basic "Rock, Paper, Scissors" game where the user plays against the computer. The user selects their choice by entering 0 for Rock, 1 for Paper, or 2 for Scissors. The computer then randomly selects one of these choices using random.randint(0, 2), which generates an integer between 0 and 2. The program then compares the user’s choice with the computer’s choice and prints the result: "It's a draw" if both choices are the same, "You Lose" or "You Win" depending on which choice is stronger. This game uses conditional statements (if, elif) to determine the outcome, and a random number generator to simulate the computer's choice.

The primary concepts used here are conditional statements for decision-making and random number generation for the computer's move. The logic could be improved, as some conditions overlap, but it’s functional for a basic game setup.


**password generator** :This code is a simple password generator program that creates a custom password based on the user’s requirements for letters, symbols, and numbers. It begins by welcoming the user and then prompts for the number of letters, symbols, and numbers to include in the password. The program then initializes an empty string, password, which will hold the generated password.
The password is built in three stages: the first for loop adds random letters to password based on the user’s input, using random.choice(letters) to pick a random letter each time. The second for loop appends random symbols, and the third loop appends random numbers, each according to the user's input. Finally, it prints the password, which contains a mix of letters, symbols, and numbers.

The main concepts used here are:
For loops for repeating actions a specified number of times.
Random selection using random.choice() to pick items randomly from a list.
String concatenation to build the final password step-by-step.
This approach builds the password sequentially, but it doesn’t shuffle the characters, so the letters, symbols, and numbers appear in the order they’re added.
