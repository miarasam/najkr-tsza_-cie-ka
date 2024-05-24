# Matrix Path Minimization

This Julia program generates a matrix of given dimensions (m, n) where each element is filled with a random value within a specified range. It then calculates the path with the smallest sum from the bottom row to the top row, moving only diagonally. The program outputs the original matrix, a matrix showing the minimal sums to each point, the path taken, and the total minimal sum required to traverse from the bottom to the top.

## Getting Started

### Prerequisites

- Julia 1.0 or higher
- Basic understanding of matrix operations

### Installation

Clone the repository to your local machine:

``` bash
git clone https://github.com/yourusername/matrix-path-minimization.git
cd matrix-path-minimization

### Usage
To use the function process_matrix, call it with the desired number of rows, columns, and range for random values. For example:
process_matrix(10, 10, 100)
This will generate a 10x10 matrix with values ranging from 1 to 100.

### Function Description
function process_matrix(wiersz::Int, kolumna::Int, przedzial::Int)

Parameters
wiersz (Int): Number of rows in the matrix.
kolumna (Int): Number of columns in the matrix.
przedzial (Int): Range for random values in the matrix.
Process
Matrix Initialization:

Generates a wiersz x kolumna matrix with random values within the specified range.
Displays the initial matrix.
Minimal Path Calculation:

Calculates the minimal path sums moving from the bottom to the top, considering only diagonal movements.
Constructs a matrix showing the minimal sums to each point.
Identifies the minimal path and its corresponding sum.
Output:

Displays the matrix with minimal sums to each point.
Displays the matrix indicating the path taken.
Prints the total minimal sum required for the path.

Example Output
For process_matrix(10, 10, 100):

Initial Matrix:

Matrix with Minimal Sums:

Path Matrix:

Total Minimal Sum:

Contributing
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgments
Inspiration from dynamic programming and pathfinding algorithms.
Julia documentation and community for guidance.
