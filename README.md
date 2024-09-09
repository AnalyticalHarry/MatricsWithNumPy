# NumPy Matrices Overview

NumPy is a powerful library in Python for numerical computing. It provides support for matrices and a wide range of operations that can be performed on them. This document provides an overview of important matrix operations and concepts using NumPy.

## Overview

Matrices are fundamental data structures in numerical computing. They are essentially 2-dimensional arrays with rows and columns, and are used extensively in various fields such as machine learning, data analysis, and scientific computing.

NumPy offers a rich set of functionalities to create, manipulate, and perform operations on matrices. Understanding these operations is crucial for efficient data processing and mathematical computations.

## Topics

1. **Creating Matrices**
   - **From Lists**: Create matrices using nested lists.
   - **Using `np.array()`**: Convert lists or tuples into NumPy arrays.
   - **Predefined Matrices**: Use functions like `np.zeros()`, `np.ones()`, and `np.eye()`.

2. **Matrix Operations**
   - **Basic Arithmetic**: Perform element-wise addition, subtraction, multiplication, and division.
   - **Matrix Multiplication**: Use `np.dot()` or the `@` operator for matrix multiplication.
   - **Transpose**: Use `.T` to get the transpose of a matrix.
   - **Inverse**: Compute the inverse using `np.linalg.inv()`.

3. **Matrix Properties**
   - **Shape and Size**: Use `.shape` and `.size` to get matrix dimensions and number of elements.
   - **Reshaping**: Change matrix dimensions with `.reshape()`.
   - **Flattening**: Convert a matrix into a 1D array with `.ravel()` or `.flatten()`.

4. **Matrix Functions**
   - **Determinant**: Calculate the determinant using `np.linalg.det()`.
   - **Eigenvalues and Eigenvectors**: Use `np.linalg.eig()` to compute eigenvalues and eigenvectors.
   - **Singular Value Decomposition (SVD)**: Decompose matrices using `np.linalg.svd()`.

5. **Advanced Operations**
   - **Broadcasting**: Apply operations across dimensions of different sizes.
   - **Masked Operations**: Use boolean masks to perform operations on selected elements.
   - **Matrix Indexing and Slicing**: Access and modify matrix elements using indexing and slicing.

6. **Special Matrices**
   - **Identity Matrix**: Create an identity matrix using `np.eye()`.
   - **Diagonal Matrix**: Create a diagonal matrix using `np.diag()`.
   - **Random Matrices**: Generate matrices with random values using `np.random.rand()` or `np.random.randn()`.


```python
MIT License

Copyright (c) 2024 Hemant Thapa

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

