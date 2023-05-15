# Game of Life

The Game of Life is a cellular automaton created by British mathematician John Conway. It is a zero-player game, meaning that its evolution is determined solely by its initial state. The Game of Life is played on a two-dimensional grid, where each cell can be either alive or dead. The game follows a set of rules that dictate the birth, survival, and death of cells, creating fascinating patterns and behavior.

## Rules of the Game

1. Any live cell with fewer than two live neighbors dies, as if by underpopulation.
2. Any live cell with two or three live neighbors lives on to the next generation.
3. Any live cell with more than three live neighbors dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

## How to Play

1. Install Jupyter Notebook: The Game of Life is implemented in Python Notebook .ipynb, so make sure you have jupyter installed on your computer. You can download Jupyter from the official website: [https://www.anaconda.com/](https://www.anaconda.com/)

2. Clone the Repository: Clone this repository to your local machine using the following command:
   ```
   git clone https://github.com/salimhammadi15/Game_of_life.git
   ```

3. Navigate to the Directory: Move into the project directory:
   ```
   cd game-of-life
   ```

4. Run the Game: Execute the game by running the the Jupyter Notebook:

5. Customize the Initial State (Optional): If you want to modify the initial state of the game, you can open the `game_of_life.py` file and modify the `grid` variable. Change the values to 1 for live cells and 0 for dead cells. You can experiment with different patterns and configurations.

6. Explore the Game: The Game of Life will start running, and you will see the grid evolving over time. Each generation is displayed, and you can observe how the cells are born, survive, and die according to the rules.

7. Terminate the Game: To stop the game, press Ctrl+C in the terminal or command prompt.

## Contributing

If you would like to contribute to the development of the Game of Life, you can follow these steps:

1. Fork the Repository: Click on the "Fork" button at the top right corner of the repository page. This will create a copy of the repository in your GitHub account.

2. Clone Your Fork: Clone the repository from **your** GitHub account to your local machine using the following command:
   ```
   git clone https://github.com/salimhammadi15/Game_of_life.git
   ```

3. Make Changes: Create a new branch and make your desired changes in the codebase.

4. Test Your Changes: Run the game and ensure that your modifications work correctly.

5. Commit and Push: Commit your changes and push them to your forked repository:
   ```
   git add .
   git commit -m "Your commit message"
   git push origin your-branch-name
   ```

6. Create a Pull Request: Go to the original repository on GitHub and click on the "New Pull Request" button. Fill out the details and submit the pull request. Your changes will be reviewed by the project maintainers.

## License

The Game of Life is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

This implementation of the Game of Life was inspired by John Conway's original rules and cellular automaton concept.
