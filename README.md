# mineswapper

A terminal-based implementation of the classic game Minesweeper, built entirely in Python.
🌟 Features

   1.Dynamic Board Generation: Creates a custom board of any dim_size with a specified num_bombs.
   2.Recursive Digging (Flood Fill): Automatically reveals large, safe areas (zero-value cells) using a recursive algorithm.
   3.Neighbor Counting: Accurately assigns numbers to cells based on adjacent bomb count.
   4.Terminal Visualization: Displays the game board clearly using standard character formatting.

🎮 How to Play

The game will prompt you for a location to dig.
    Input Format: Enter your move as two comma-separated integers: row,col.
        Example: where to dig? 5,5
    Gameplay:
        If you dig a safe, numbered cell, the number (1-8) will reveal the count of adjacent bombs.
        If you dig a zero-value cell, the game automatically reveals the surrounding safe area (Flood Fill).
        If you dig a bomb (*), the game ends!

   
Winning: You win when all non-bomb cells have been revealed.

            
       
