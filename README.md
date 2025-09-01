# minmax-on-tictactoe
📌 Aim 

To implement a Tic Tac Toe game in Python where a human player competes against an AI opponent. The AI uses the Minimax algorithm to always play optimally, ensuring it never loses. 

Shape 

📌 Problem Statement 

The classic Tic Tac Toe game is simple but provides a foundation for understanding game theory and AI decision-making. The problem is to: 

Allow a human to play against the computer. 

Use an algorithm that ensures the computer never loses. 

Handle all game outcomes: win, lose, or draw. 

 
 

Shape 

📌 Algorithm Used:  

The Minimax Algorithm is a recursive algorithm widely used in decision-making and game theory. 
It assumes that: 

The maximizing player (AI) tries to maximize the score. 

The minimizing player (Human) tries to minimize the score. 

Working: 

If the game reaches a terminal state (win/loss/draw), return a score: 

+1 → Computer wins (O). 

-1 → Human wins (X). 

0 → Draw. 

If it’s the computer’s turn (Maximizing): 

Try all possible moves, recursively calculate scores using Minimax. 

Pick the move with the highest score. 

If it’s the human’s turn (Minimizing): 

Try all possible moves, recursively calculate scores. 

Pick the move with the lowest score. 

Continue until all possible outcomes are evaluated. 

This guarantees that the AI will always choose the optimal move. 
