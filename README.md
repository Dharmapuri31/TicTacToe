# TicTacToe & Wild TicTacToe Using Minimax search algorithm
<body> 
  I recently worked on this project and it was a fun learning experience. A game is built using the Minimax search. It is a backtracking algorithm that is used for decision making in game theory. There are three aspects that we are looking at while designing the game.
  
  
  <br><em>1) Optimal Vs Optimal: Note that it is pure optimal, meaning that even the first move is optimal. Our minimax function always returns the first best score and plays that move.</em></br>
  <br><em>2) Optimal Vs Random: The first player plays randomly, and the second player plays optimally.</em></br>
  <br><em>3) Optimal VS you: User gets to play as the first player against an optimal player</em></br>
  
  <h2>
  Tic Tac Toe:
  </h2>
  
  The first player plays x and the second player plays o. The player who succeeds in placing three of their marks in a horizontal,
  
  vertical, or diagonal row wins the game. If all cells are used without someone getting a three in a row, the game is a draw.
  
  <b>Points to keep in mind:</b>
  <br>1) If both players play optimally, the game will always be a draw.</br>
  <br>2) If one player is optimal and the other is random, the optimal player will win most of the games and the random player will never win. </br>
  
  Let us get into the details of what has to be done in Tic Tac Toe and Wild Tic Tac Toe
  
  <h2> 
  Wild Tic Tac Toe:
  </h2> 
  
<br> On each turn a player can play either x or o. The player who gets the first three (x’s or o’s) in a row wins the game. </br> 
<br> If all cells are used without someone getting a three in a row, the game is a draw.</br> 

<b>Points to keep in mind:</b>
<br> 1. If both players play optimally, the first player can always win if the middle cell is chosen as his/her first move. </br>
<br> 2. If both players play optimally, the game will be always a draw if the first player does NOT choose the middle cell as his/her first move. </br>
<br> 3. If one player is optimal and the other is random, the optimal player will win most of the games and the random player will never win. </br>

</body>
