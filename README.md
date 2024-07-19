# CognoriseJavaAllTasks
*NUMBER GUESSING GAME*
1.Objective:
Player tries to guess a randomly generated number within a specified range.
2.Game Flow:
The game generates a random number within a predefined range (e.g., 1 to 100).
The player is prompted to input their guess.
3.The game provides feedback:
If the guess is too high, inform the player that the guess is too high.
If the guess is too low, inform the player that the guess is too low.
If the guess is correct, congratulate the player and end the game.
4.Game Setup:
Initialize the random number generator.
Set the range for the random number (e.g., 1 to 100).
User Input:
Use Scanner class to read player input from the console.
5.Feedback Loop:
After each guess, provide feedback to guide the player.
Repeat the guessing process until the player guesses correctly.
6.Game Termination:
When the player guesses the correct number, display a congratulatory message.
Optionally, display the number of attempts taken to guess correctly.
Prompt the player to play again or exit the game.
7.Error Handling:
Validate user input to ensure it is a valid number within the specified range.
Handle exceptions gracefully (e.g., non-numeric input).
8.Enhancements:
Allow customization of the range (e.g., user can set the lower and upper bounds).
Track the number of attempts and display it at the end.
Add a feature to limit the number of attempts and notify the player when attempts are exhausted.
Include a scoring system based on the number of attempts.
Provide a graphical user interface (GUI) for a more interactive experience.

*CALCULATOR APP*
1.Objective: Perform basic arithmetic operations (addition, subtraction, multiplication, division).
2.Features:
Perform addition, subtraction, multiplication, and division.
Input validation and error handling.
Option to perform multiple calculations.
3.User Interface:
Console-based menu for operation selection and input.
4.Game Flow:
Display a menu of operations.
User selects an operation.
User inputs two numbers.
Perform the operation and display the result.
Option to perform another calculation or exit.
5.User Input:
Use Scanner class for input.
6.Error Handling:
Handle division by zero.
Validate numeric inputs.
Handle invalid menu choices.
Sample Code Outline

*HANGMAN GAME*
1.Objective:
Guess the hidden word by suggesting letters within a limited number of attempts.
2.Features:
Display of hidden word with guessed letters revealed.
Tracking and displaying remaining attempts.
Indication of letters already guessed.
Victory message when the word is guessed correctly.
Failure message when attempts are exhausted.
3.User Interface:
Console-based interaction for simplicity.
4.Game Flow:
Randomly select a word from a predefined list.
Display the word with hidden letters (e.g., "_ _ _ _").
Prompt the user to guess a letter.
Reveal correctly guessed letters and update the display.
Deduct an attempt for incorrect guesses.
Continue until the word is guessed or attempts run out.
Display a win/lose message at the end of the game.
5.User Input:
Use Scanner class to read user guesses from the console.
6.Error Handling:
Validate that the input is a single letter.
Handle repeated guesses.
