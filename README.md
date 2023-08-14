# [Minesweeper (Java)](https://youtu.be/5VrMVSDjeso)

How to code a Minesweeper game in Java for beginners! Learn how to create a game of Minesweeper in Java using the awt and swing graphics library. 

In this tutorial, you will learn how to make the classic game, minesweeper! You will learn how to create a graphical user interface (GUI) to display 8x8 grid of tiles. You will also learn to add click handlers to select a tile. With a left click, you will learn to open a tile, detect if the tile contains a mine, count the number of mines surround the tile, and recursively check neighboring tiles to count the number of mines surround those tiles. With a right click, you will learn to place and remove flags on a tile. After understanding the core game logic, you will learn how to generate levels by placing mines in random tiles.

[How to setup Java with Visual Studio Code](https://youtu.be/BB0gZFpukJU)

![minesweeper-java-demo](https://github.com/ImKennyYip/minesweeper-java/assets/78777681/e11454a3-f8ba-4730-88c0-145f5f6c14dc)


## Homework:
You can continue working on this project if you like. One feature you can add is create an input to let players input the number of mines present in the game. To do this, you will need a JTextField. Then you can use the getText() method to get the input, check if it's a number, and use that as the number of mines. Another useful feature would be to create another JButton for "restart game". By clicking this button, your program should reset the game by setting text to "" and enabled to true for every tile. After that, your program should call setMines() again. You can also combine this feature with the input for the number of mines.
