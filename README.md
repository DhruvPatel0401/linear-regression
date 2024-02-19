# Linear Regression Implementation in Python

This Python script demonstrates how to perform linear regression using gradient descent. The script includes functions to compute the error for a given line, perform gradient descent steps, and run the gradient descent algorithm to optimize the line parameters (slope and y-intercept).

## Prerequisites

- Python 3.x
- NumPy library (`numpy`)

## Installation

1. Clone or download the repository to your local machine.

2. Install the required dependencies using pip:

    ```bash
    pip install numpy
    ```

## Usage

1. Place your data in a CSV file named `data.csv` in the same directory as the script. The CSV file should have two columns: x-values and corresponding y-values.

2. Run the script using the following command:

    ```bash
    python main.py
    ```

3. The script will output the initial error, run the gradient descent algorithm, and print the optimized parameters (slope and y-intercept) along with the final error.

## File Structure

- `main.py`: Main Python script containing the implementation of linear regression using gradient descent.
- `data.csv`: CSV file containing the input data points for the regression.

## Customization

You can customize the script by modifying parameters such as the initial guess for the slope and y-intercept, learning rate, and number of iterations in the `run()` function.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
