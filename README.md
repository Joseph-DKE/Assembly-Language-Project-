# Assembly-Language-Project-
Files needed to run the Guessing Game
STEPS TO PROGRAM THE GUESSING GAME

1. Program generates a random number. i.e Number the user is supposed to guess
 
2. Display the number of tries the user has
- Can be written such that it is program specified or set as a constant in the program 
- Or the user enters the number of tries he wants to have

3. Display an output to the screen asking user to enter a number for a specific try. Eg. Try 3 \n Enter a Number:

4. Take User input for each Try

5. Compares User input to the random number generated by the program.
- If User input is greater/lower than the random number, print an appropriate message to the screen preferably with clues like "The number you entered is greater than 25. Guess again! "
- If User input is equal to the random number, print a congratulatory message to the screen saying the user guessed it right at a particular Try Number.

6. If the number of Tries is exhausted, display a sorry message to the screen optionally with a play again function.

7*.  We can add a function that asks the the user if he wants to play the game again.
- Where a Yes answer will refer the program to the label at the global part of the code
- And a No answer will exit or quit the program
