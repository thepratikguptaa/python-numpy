# NumPy Learning Notebooks

This project contains a collection of Jupyter notebooks designed to help learn the fundamentals of the NumPy library.

## What is NumPy?

NumPy (Numerical Python) is a fundamental open-source library for the Python programming language. It is used for scientific computing and is a core part of the data science ecosystem.

The main feature of NumPy is its powerful N-dimensional array object, called an `ndarray`. These arrays are more efficient than standard Python lists for numerical operations, especially on large datasets. This is because NumPy arrays are stored in a continuous block of memory and many of its operations are performed by pre-compiled C code, which makes them much faster.

Key features of NumPy include:

*   **N-dimensional arrays (`ndarray`)**: A grid of values, all of the same data type, which allows for efficient storage and manipulation of data.
*   **Mathematical Functions**: A large collection of high-level mathematical functions to perform operations on these arrays, such as linear algebra, Fourier transforms, and random number generation.
*   **Broadcasting**: A powerful mechanism that allows NumPy to perform arithmetic operations on arrays of different shapes.
*   **Interoperability**: It is the foundation for many other scientific and data science libraries in Python, such as Pandas, Scikit-learn, SciPy, and TensorFlow.

NumPy is widely used in various fields:

*   **Data Science and Machine Learning**: For data manipulation, analysis, and building machine learning models.
*   **Image and Signal Processing**: To represent and manipulate images and signals as arrays of pixels or samples.
*   **Scientific Research**: In fields like physics, chemistry, and biology to analyze large datasets and perform simulations.
*   **Finance**: For tasks like portfolio optimization and financial analysis.

## What is uv?

`uv` is an extremely fast Python package and project manager, written in Rust. It's a drop-in replacement for `pip`, `pip-tools`, and `virtualenv`, but 10-100x faster.

## Installation

To run the notebooks in this project, you need to have Python and `uv` installed.

First, install `uv`:

```bash
pip install uv
```

Then, create a virtual environment and install the required packages:

```bash
uv venv
uv pip install numpy matplotlib
```

## Usage

To use these notebooks, you'll need a code editor that supports Jupyter notebooks, like VS Code with the Python and Jupyter extensions.

1.  Clone this repository to your local machine.
2.  Navigate to the project directory in your terminal.
3.  Activate the virtual environment:

    ```bash
    .venv/bin/activate
    ```

4.  Open the project in your code editor (e.g., `code .` for VS Code).
5.  Open any of the `phase-*.ipynb` notebooks and start learning!

## Project Structure

The project is organized as follows:

```
├───array1.npy
├───array2.npy
├───array3.npy
├───numpy-dark-logo.npy
├───numpy-logo.npy
├───phase-1.ipynb
├───phase-2.ipynb
├───phase-3.ipynb
├───phase-4.ipynb
├───README.md
└───.venv
```

*   **`phase-1.ipynb`**: Covers the basics of NumPy, including creating arrays, array attributes, and basic array operations.
*   **`phase-2.ipynb`**: Covers array indexing and slicing in NumPy.
*   **`phase-3.ipynb`**: Covers array manipulation, including reshaping, stacking, and splitting arrays.
*   **`phase-4.ipynb`**: Covers broadcasting in NumPy.
*   **`*.npy`**: These are data files created with NumPy.
*   **`README.md`**: This file, providing an overview of the project.
