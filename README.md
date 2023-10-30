# Conway's Game of Life

This is a Python implementation of Conway's Game of Life using the Pygame library. Conway's Game of Life is a cellular automaton that simulates the evolution of a grid of cells based on a simple set of rules. Cells can be in one of two states, alive or dead, and they evolve over generations according to these rules.

## Prerequisites
- Python 3.x
- Pygame library

## Installation

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/yourusername/conways-game-of-life.git
   ```

2. Install the Pygame library if you haven't already:

   ```shell
   pip install pygame
   ```

## Usage

To run the Conway's Game of Life simulation, follow these steps:

1. Navigate to the project directory:

   ```shell
   cd conways-game-of-life
   ```

2. Run the `conways_game_of_life.py` script:

   ```shell
   python conways_game_of_life.py
   ```

## Controls

- **Left Mouse Button**: Click on a cell to toggle its state (alive or dead).
- **Spacebar**: Start or pause the simulation.
- **'c' Key**: Clear the grid, reset all cells to the dead state, and pause the simulation.
- **'g' Key**: Generate a random pattern of cells on the grid.
- **'Esc' Key**: Quit the simulation.

## Rules

The simulation follows these rules:

1. Any live cell with 2 or 3 live neighbors survives.
2. Any dead cell with exactly 3 live neighbors becomes a live cell.
3. All other live cells die in the next generation.

## Customization

You can customize various parameters in the `conways_game_of_life.py` script:

- `WIDTH` and `HEIGHT`: Set the dimensions of the simulation window.
- `TILE_SIZE`: Adjust the size of each cell on the grid.
- `FPS`: Control the frames per second for the simulation speed.
- `update_freq`: Set the generation update frequency.
- `gen(num)`: Modify the initial random pattern generation.

## Contributions

Feel free to contribute to this project by adding features, fixing bugs, or improving the code. You can submit pull requests to the GitHub repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Pygame](https://www.pygame.org/) for the graphics and game development library.
- [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) for the fascinating cellular automaton concept.
