## Prerequisites:
- Python installed on your local machine (Python 3.x recommended).
- Pip for installing Python packages.

## Installation Steps:

### 1. Clone the Repository
Start by cloning the repository to get the project files: `git clone https://github.com/BGoodes/Knight-tour.git`.

### 2. Install dependencies
The program requires the following libraries: `pygame`, `tkinter`, and `playsound`. You can install them using pip:

```sh
pip install pygame
pip install playsound
```
The library `tkinter` usually comes bundled with Python on Windows. If it's not installed, you can install it using your distribution's package manager.

## Usage:
After running the `main.py` script, the graphical user interface will open displaying a chessboard. The knight's starting position is randomly selected. The program will then attempt to solve the Knight's Tour, visually displaying the knight's moves on the chessboard.

### Interface and Interaction:
- The knight is represented by an image `knight.png` on the chessboard.
- Each move of the knight is followed by the playing of a sound.
- The knight's path is highlighted on the chessboard.
- If the knight moves to a square that has already been visited or makes an invalid move, the square will turn red indicating an error.

### Ending the Simulation:
- The simulation runs automatically and stops when the knight has either visited all squares (successful tour) or when an error has occurred.
- A dialog box will pop up at the end of the simulation displaying the total number of squares successfully visited by the knight.
- To close the program, simply close the graphical interface window.

