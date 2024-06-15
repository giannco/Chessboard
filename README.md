# Chessboard with Knight's Tour

A interactive chessboard with a knight piece that moves randomly around the board, demonstrating the Knight's Tour problem.

## Screenshot


![Chessboard](https://github.com/giannco/Chessboard/blob/main/chessboard.png)


Screenshot of the chessboard with the knight piece

## Features

    A 8x8 chessboard with alternating white and black squares
    A knight piece that moves randomly around the board every second
    The knight piece uses the Unicode character 🐎
    The knight's movement is restricted to the possible moves of a knight in chess (L-shape moves)

## How it Works

The project uses HTML, CSS, and JavaScript to create the chessboard and animate the knight's movement. The JavaScript code creates the chessboard dynamically, places the knight piece on the starting square, and then moves the knight to a random adjacent square every second.

## Possible Moves

The knight piece can move in the following ways:

    2 squares in one direction (horizontally or vertically), then 1 square in a perpendicular direction
    1 square in one direction (horizontally or vertically), then 2 squares in a perpendicular direction

These moves are represented by the following arrays:

let possibleMoves = [

    [-2, -1], [-2, 1], [-1, -2], [-1, 2],

    [1, -2], [1, 2], [2, -1], [2, 1]

];

## License

This project is licensed under the MIT License.

## Author

[Gian Franco Marcano]

## Acknowledgments

This project was inspired by the Knight's Tour problem, a classic problem in computer science and mathematics.
