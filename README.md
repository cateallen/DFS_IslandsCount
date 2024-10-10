# DFS Islands Count

This project demonstrates the **Depth-First Search (DFS)** algorithm by solving the problem of counting the number of islands in a 2D grid. An island is defined as a group of `1`s (land) connected horizontally or vertically in a grid, surrounded by water (`0`s).

## Table of Contents
- [Overview](#overview)
- [Usage](#usage)
- [Algorithm](#algorithm)
- [Installation](#installation)
- [Running the Program](#running-the-program)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is an example of a popular algorithmic problem where the goal is to count the number of islands in a given grid using **DFS**. The grid is a matrix made up of `1`s (representing land) and `0`s (representing water), and the solution involves exploring each piece of land and marking it as visited.

## Algorithm

- The **DFS** algorithm is used to explore each piece of land. If a `1` (land) is found, DFS recursively visits all adjacent land tiles (up, down, left, right), marking them as visited. Each unvisited piece of land starts a new DFS traversal, indicating a new island has been found.

- The algorithm efficiently traverses the grid and counts the number of separate islands.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/cateallen/DFS_IslandsCount.git
   cd DFS_IslandsCount
   ```

2. Make sure you have **Python** installed. This project uses Python, so you’ll need Python 3.x. You can check if Python is installed by running:
   ```bash
   python --version
   ```

3. Install any necessary dependencies (if required):
   ```bash
   pip install -r requirements.txt
   ```

## Running the Program

The script `IslandsProgram.py` contains the implementation of the DFS algorithm.

To run the program:
```bash
python IslandsProgram.py
```

You can modify the grid in the program to test different scenarios. For example, a grid might look like this:

```python
grid = [
    [1, 1, 0, 0, 0],
    [1, 1, 0, 1, 1],
    [0, 0, 0, 1, 1],
    [0, 1, 0, 0, 0]
]
```

The output will be the number of islands found in the grid.

## Usage

This project can be useful for understanding how to apply **DFS** in grid-based problems and can serve as a base for other similar problems, such as:
- Flood fill algorithm
- Maze solving
- Connected component counting in graphs

## Contributing

Feel free to fork the repository and submit pull requests. Any improvements to the code, optimizations, or additional features are welcome.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

