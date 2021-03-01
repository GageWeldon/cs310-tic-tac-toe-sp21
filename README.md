# cs310-tic-tac-toe-sp21

This project was for a class at JSU this semester (Spring 2021). This project is a simple tic-tac-toe game that uses java for the language. 
The program consists of a main method to run the game, a controller to control the game board, and sub-classes for the movement and updating the board display in a JPanel.
This was my first attempt at making any sort of game and my very first attempt at using JPanels to display information. My first thing to do was to edit previously given files
to update the game board to the new state. This involves initializing the board with blank panels and then filling said panels according to the user input. When a user enters
coordinates, the class ticTacToeModel then iterates through the game board and puts the 'mark' on the selected coordinate. This is then updated in the ticTacToeView class which 
prints out the game board to the screen. All while this is going on, the controller class is always checking the game state. If it is not a tie and the game has not ended then 
the game will continue. If the game state detects a tie or a win then the game will update with a messgae corresponding to the current game state.
