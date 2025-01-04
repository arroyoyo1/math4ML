# math4ML

## Overview
This repository consists of four Python assignments focused on linear algebra concepts, matrix operations, eigenvalue problems, and real-world applications like the PageRank algorithm. The assignments progressively explore key mathematical methods such as matrix identifiaction, the Gram-Schmidt process, transformations, and eigenvector computations.

Below is a brief overview of each assignment, with a description of the key concepts and functions involved.

## Identifying special matrices
In this assignment, there's a function to test if a 4×4 matrix is singular, i.e., whether its inverse exists. The function should use the method of converting the matrix to echelon form and determine if the matrix is singular by checking for zeros in the leading diagonal, which would indicate the matrix does not have an inverse.

## 2. Gram-Schmidt Process
The Gram-Schmidt process is a method for orthonormalizing a set of vectors in an inner product space. This assignment focuses on applying the Gram-Schmidt process to generate an orthonormal basis from a given set of vectors. It helps build a foundation for understanding orthogonality in linear algebra.

## 3. Reflection of a Bear
In this assignment, the goal is to calculate the reflection of vectors in a mirror defined by a given set of basis vectors. The process uses the Gram-Schmidt orthonormalization from the previous assignment to construct a reflection matrix and apply it to vectors.

## 4. PageRank Algorithm
This assignment applies the PageRank algorithm, originally developed by Larry Page and Sergey Brin, to rank a set of websites based on their connectivity. The problem models a simplified version of the web with a set of six websites and computes the PageRank using matrix operations and eigenvalue problems.

## How to Run the Code
1. Clone or download this repository to your local machine.
2. Ensure that you have the required Python libraries installed. You can install them using pip
```
  pip install numpy
```
3. Each assignment is contained in a separate Python script or Jupyter notebook. You can run each notebook individually to test and verify the results.
4. To execute the functions, simply import them into your Python environment or Jupyter notebook and call them with the appropriate arguments.

## Conclusion
This project provides an in-depth exploration of linear algebra through the application of real-world problems, including matrix transformations, orthonormalization, and the PageRank algorithm. It is designed to help users understand key mathematical concepts and apply them in computational tasks using Python.
