Minesweeper - Java Swing
Author: Panagiotis Georgiadis

Minesweeper is a classic single-player puzzle video game where the objective is to clear a rectangular board that contains hidden mines without detonating any of them. The game is won when all safe squares are uncovered, and it is lost if a mine is clicked. This Java Swing-based Minesweeper game provides a graphical user interface for an immersive gaming experience.

Features: 

Customizable Grid: Choose the dimensions of the game board (number of rows and columns) and the number of mines to challenge your skills.
User-Friendly Interface: Enjoy the game through an interactive graphical user interface built with Java Swing.
Game Rules: This implementation enforces the classic rules of Minesweeper, including flagging mines and revealing safe squares.
Winning and Losing Conditions: The game checks for both victory and defeat conditions.

How to Play:

1)Clone or download the repository to your local machine.
2)Ensure you have Java Development Kit (JDK) installed.
3)Compile and run the game by executing the Minesweeper.java file:

Copy code:
``
javac Minesweeper.java
java Minesweeper
`` 
4)Follow the on-screen instructions to set the game parameters and play.

Gameplay:

Left-Click: Reveal a cell.
Right-Click: Flag a cell.
Middle-Click: Chord (reveals adjacent cells if the number of adjacent flags matches the number of mines around the cell).
Winning Condition: Reveal all safe cells.
Losing Condition: Click on a cell containing a mine.

Customization:

You can customize the game by changing the board size and the number of mines in the Minesweeper.java file. Modify the following lines:

Copy code:
``
// Customize the game board dimensions and the number of mines here
int rows = 8;
int cols = 8;
int numMines = 10;
``

Dependencies: 

This game does not rely on any external libraries or packages. It is written in Java and utilizes Java Swing for the graphical interface.

License:

This project is licensed under the MIT License. For more details, see the LICENSE file.

Acknowledgments:

Special thanks to the Minesweeper community for their inspiration and the countless hours of enjoyment this game has provided.

 
