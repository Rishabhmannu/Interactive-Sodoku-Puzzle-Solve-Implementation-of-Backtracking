# Interactive Sudoku Puzzle Solver

An interactive web-based Sudoku solver built with HTML, CSS, and JavaScript. This project visually demonstrates the implementation of the backtracking algorithm to solve Sudoku puzzles in real-time.

## Features

- **Interactive Grid:** Allows users to input numbers directly into the 9x9 Sudoku grid.
- **Backtracking Algorithm:** Automatically solves the puzzle based on the user's input using the backtracking algorithm.
- **Validation:** Displays a message if the puzzle is unsolvable or if the board configuration is invalid.
- **Reset Option:** Users can clear the board and start over with new inputs.
- **Real-Time Solution:** The solving process is visualized, showing how the algorithm fills in the grid step by step.

## Demo

![Sudoku Solver Demo](demo/sudoku_solver.gif) <!-- Add a gif or image showing the solver in action -->

## How to Run

### 1. Clone the Repository

```bash
git clone git@github.com:Rishabhmannu/Interactive-Sodoku-Puzzle-Solver.git
cd Interactive-Sodoku-Puzzle-Solver
```

## 2. Run the Application

- Open `index.html` using Live Server or any web server running on localhost.
- Alternatively, you can directly open `index.html` in your browser, but using a live server ensures that all functionalities work smoothly.

## 3. Interact with the Application

- **Input Numbers:** Click on any cell in the grid and type a number to input your puzzle.
- **Solve the Puzzle:** After entering the numbers, click the "Solve" button to run the backtracking algorithm.
- **Reset the Board:** If you want to start over, click the "Clear" button to reset the board.

## 4. View the Solution

- The solver will fill in the grid based on your input, solving the puzzle.
- If no valid solution exists, a message will display stating "Invalid Board."

## Project Structure

- **index.html**: Contains the HTML structure of the application.
- **styles.css**: Defines the styles and layout for the application.
- **sudoku.js**: Contains the JavaScript logic for the Sudoku solver, including the implementation of the backtracking algorithm.

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**

## Contributing

Contributions are welcome! If you have ideas for improvements or find bugs, feel free to open an issue or submit a pull request.


## Acknowledgments

Thanks to the open-source community for providing tools and libraries that made this project possible.
