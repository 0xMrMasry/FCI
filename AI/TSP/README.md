```markdown
# TSP AI Project

This project implements two algorithms for solving the Traveling Salesman Problem (TSP): the nearest neighbor method and the 2-opt method. It provides a graphical user interface (GUI) for visualizing and interacting with the TSP solutions.

## Requirements

- Python 3.x
- PyQt5
- Matplotlib
- NumPy

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/0xMrMasry/FCI.git
    ```

2. Install the required dependencies:

    ```bash
    pip install PyQt5 matplotlib numpy
    ```

## Usage

Run the `main.py` file to launch the GUI application:

```bash
python main.py
```

The GUI window will appear, allowing you to:

- Add cities by left-clicking on the map.
- Remove cities by right-clicking on them.
- Clear all cities by clicking the "Clear all" button.
- Compute the TSP solution using the nearest neighbor method by clicking the "Nearest neighbor method" button.
- Compute the TSP solution using the 2-opt method by clicking the "2-opt method" button.
- Clear the route displayed on the map by clicking the "Clear route" button.

You can also set delays (in seconds) between each step of the algorithms using the input fields provided.

## Credits

This project was developed by [Abdullah Elmasry](https://github.com/0xMrMasry) as part of the AI course at Faculty of Computers and Information - Damanhur University. Special thanks to [Mona Alhussiny](https://github.com/monaalhussiny) for her contribution.

## License

This project is licensed under the MIT License .
```
