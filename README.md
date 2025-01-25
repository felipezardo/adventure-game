# Jungle Escape - Adventure Game

## Description

**Jungle Escape** is an interactive text-based adventure game where players navigate through a jungle filled with mysterious choices. In this game, players are faced with a series of decisions that shape the outcome of the story. There are multiple possible endings, depending on the choices made throughout the game. It features simple input handling, branching storylines, and a hidden hint system to guide players who might get stuck.

### Key Features:
- **Branching Choices**: Players must make decisions that lead them down different paths, with each decision impacting the game's outcome.
- **Multiple Endings**: The game has multiple possible endings, ranging from escaping the jungle to facing dangers that lead to the player's demise.
- **Input Validation**: The game handles user input gracefully, ensuring that invalid responses prompt the player to try again until a valid option is selected.
- **Hidden Hint System**: There is a secret "HELP" option that provides hints to help players who might be stuck.
- **Text-based Story**: The game unfolds in a narrative format, making it easy to expand with new choices and storylines.

## Python Features and Concepts Implemented

### 1. Loops and Nested Loops:
The game is driven by **while loops**, which allow the game to continually prompt the player for choices until a valid input is received. Nested loops are used for handling different levels of decisions, creating a branching story.

### 2. Conditionals:
The game uses **if-elif-else** statements to evaluate the player's input and direct them to the appropriate part of the story based on their choices. Invalid choices prompt the user to try again.

### 3. String Manipulation:
The game performs string manipulation using methods like `strip()` (to remove extra spaces) and `lower()` (to make the input case-insensitive), ensuring that the player's input is correctly interpreted regardless of formatting.

### 4. Input Handling:
The game utilizes Python's built-in `input()` function to capture user decisions. It checks for valid input and loops until a valid response is entered.

### 5. Functions:
The game is organized into a single function, `adventure_game()`, which contains the entire game logic. This keeps the code clean and easy to follow.

### 6. Game Flow Control:
The `return` statements are used strategically within the game to end the game session (i.e., either winning or losing) once a choice is made, effectively controlling the game's flow.

### 7. End of Game Input:
To prevent the terminal from closing immediately after the game ends, a final `input()` is used, allowing the user to press Enter before closing the game, which is especially useful when running from a terminal.

## How to Play

1. Run the Python script `adventure_game.py`.
2. Follow the on-screen prompts to make decisions as you navigate through the jungle.
3. Choose wisely to either win the game or encounter one of the many ways to lose.
4. If you're stuck, use the "HELP" option for a hint!

## Requirements

- Python 3.x
- No additional libraries are required to play this game.

## Example of Gameplay

