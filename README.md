# 520 Sliding Puzzle Game

A progressive sliding puzzle game built with HTML, CSS, and JavaScript. The game features multiple levels with increasing difficulty and a point-based reward system.

## Features

- 5 progressive levels
- 3x3 grid for levels 1-4
- 4x4 grid for level 5 (increased difficulty)
- Point system with base points and move-based bonuses
- Hint system to show the complete image
- Option to display tile numbers
- Progress saving using localStorage
- Responsive design

## How to Play

1. Click "開始挑戰" to start the game
2. Click tiles adjacent to the empty space to move them
3. Arrange the tiles in numerical order to complete each level
4. Use "顯示圖片" for a hint of the complete image
5. Use "顯示數字" to see the tile numbers
6. Complete all levels to win!

## Scoring System

- Levels 1-4: 20 base points + bonus points (up to 50 based on moves)
- Level 5: 40 base points + bonus points (up to 50 based on moves)
- Bonus points = max(0, 50 - number of moves)

## Setup

1. Clone the repository
2. Open index.html in a web browser
3. Start playing!

## Required Files

Make sure you have the following image files in your project directory:
- cover_image.png
- puzzle-image.jpg
- puzzle-image2.jpg
- puzzle-image3.png
- puzzle-image4.png
- puzzle-image5.jpg
- end_image.png 