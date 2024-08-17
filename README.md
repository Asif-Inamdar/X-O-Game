Tic Tac Toe Game
A simple Tic Tac Toe game built using HTML, CSS, and JavaScript. The game allows two players to take turns marking the spaces in 
a 3×3 grid with "X" and "O". The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner.

Features
. Responsive Design: The game layout adjusts based on screen size for a smooth experience on mobile, tablet, and desktop devices.
. Interactive Gameplay: Players take turns marking the grid, with the game automatically detecting wins and announcing the winner.
. Visual Effects: Winning lines are highlighted, and an animated GIF is displayed upon winning.
. Sound Effects: Includes sound effects for turns and game over (requires the appropriate audio files).
. Reset Functionality: The game can be easily reset using the "Reset" button.

Project Structure
. HTML (index.html): The basic structure of the game, including the grid and the game info section.
. CSS (style.css): Handles the styling and layout of the game, including responsive design and hover effects.
. JavaScript (script.js): Manages game logic, such as turn handling, win detection, and resetting the game.

How to Run the Project
. Download or clone the project files.
. Open index.html in your web browser.
. Enjoy playing the game!

Game Logic
. The game alternates turns between "X" and "O".
. The checkWin() function checks predefined winning combinations to determine if a player has won.
. The game displays the winning line and a message declaring the winner.
. The game resets when the "Reset" button is clicked.

Dependencies
. The project uses Google Fonts (Roboto and Baloo Bhaina 2) for styling.

Media Files
To include sound effects, add the following audio files in the appropriate folder:
. music.mp3
. ting.mp3
. gameover.mp3
The winning animation is displayed using excited.gif.

How to Play
. Players take turns to click on the grid.
. The current turn is indicated by a message below the grid.
. If a player wins, the game displays the winning line and shows a celebratory animation.
. Click "Reset" to start a new game.
