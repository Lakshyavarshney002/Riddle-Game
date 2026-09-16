#Riddle Game – Java Mini Project

## Project Description
Riddle Game is a console-based Java application that displays random riddles, accepts the player's answer, checks it, maintains a score, and provides an optional hint when the answer is incorrect.

## Features
- Random riddle selection
- Case-insensitive answer checking
- Score tracking
- Optional hints
- Continue/exit option
- Simple console interface
- No external libraries required

## Requirements
- Java Development Kit (JDK) 8 or later
- Any Java IDE such as IntelliJ IDEA, Eclipse, NetBeans, VS Code, or a terminal

## Project File
Main source file:
`RiddleGame.java`

## How to Run

### Using Terminal
1. Save the code in a file named `RiddleGame.java`.
2. Open the terminal in the folder containing the file.
3. Compile:
```bash
javac RiddleGame.java
```
4. Run:
```bash
java RiddleGame
```

### Using an IDE
1. Create a Java project.
2. Create a class named `RiddleGame`.
3. Paste the provided code into the class.
4. Run the `main()` method.

## How It Works
1. The program creates arrays containing riddles, answers, and hints.
2. A random index is generated using `Math.random()`.
3. The selected riddle is displayed.
4. The player enters an answer.
5. `equalsIgnoreCase()` checks the answer without case sensitivity.
6. The score increases when the answer is correct.
7. If the answer is wrong, the player can request a hint.
8. The program asks whether to continue.
9. When the player exits, the final score is displayed.

## Java Concepts Used
- `Scanner`
- String arrays
- `while` loop
- `if-else`
- `Math.random()`
- `equalsIgnoreCase()`
- `toLowerCase()`
- Variables and basic input/output

## Sample Output
```text
Riddle: The more you take, the more you leave behind. What am I?
Footsteps
Correct!
Continue playing? (yes/no)
no
Your final score: 1
Thanks for playing!
```

## Current Riddles
1. Echo
2. Footsteps
3. Fire

## Future Improvements
- More riddles
- Difficulty levels
- Timer
- Lives and streaks
- High-score storage
- GUI using Swing/JavaFX
- Riddle categories
- Database/file-based question storage
