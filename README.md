# Minesweeper

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)

A terminal-based implementation of the classic game **Minesweeper**, built entirely in Python.

## 🌟 Features

1. **Dynamic Board Generation**: Creates a custom board of any `dim_size` with a specified `num_bombs`.
2. **Recursive Digging (Flood Fill)**: Automatically reveals large, safe areas (zero-value cells) using a recursive algorithm.
3. **Neighbor Counting**: Accurately assigns numbers to cells based on adjacent bomb count.
4. **Terminal Visualization**: Displays the game board clearly using standard character formatting.

## 🎮 How to Play

The game will prompt you for a location to dig.

### Input Format
Enter your move as two comma-separated integers: `row,col`.

**Example:**
```text
where to dig? 5,5
