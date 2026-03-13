# Numerical Methods for Linear Algebra

![The Ideal City](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Formerly_Piero_della_Francesca_-_Ideal_City_-_Galleria_Nazionale_delle_Marche_Urbino_2.jpg/700px-Formerly_Piero_della_Francesca_-_Ideal_City_-_Galleria_Nazionale_delle_Marche_Urbino_2.jpg)

*"The Ideal City" (c. 1480-1490) by Unknown (Urbino panel) — [Wikipedia](https://en.wikipedia.org/wiki/The_Ideal_City_(painting))*

Scilab implementations of core numerical linear algebra algorithms, based on *Linear Algebra: A Modern Introduction* by David Poole.

## About

Coursework for **Modelagem Matematica 3: Sistemas Lineares e Otimizacao** (Mathematical Modelling 3: Linear Systems and Optimization) at EMAp/FGV, taught by Professor Antonio Branco (2017.1).

The repository contains from-scratch implementations of iterative solvers, decomposition techniques, and eigenvalue methods -- all written in Scilab.

## Algorithms Implemented

**Iterative Methods for Linear Systems**
- Jacobi iterative method
- Gauss-Seidel iterative method

**Least Squares and Decomposition**
- Least Squares method
- Singular Value Decomposition (SVD), applied to Lena's classic test image
- Image rotation via matrix transformation

**Eigenvalue / Eigenvector Methods**
- Power method
- Shifted power method
- Inverse power method
- Inverse shifted power method

## Tech Stack

- **Language:** Scilab
- **Textbook:** *Linear Algebra: A Modern Introduction* -- David Poole

## Repository Structure

```
practical-classes/
  jacobi-iterative-method.sce
  gauss-seidel-iterative-method.sce
  least-square-method.sce
  single-value-decomposition-lena.sce
  rotate-lena.sce
  eigen-power-method.sce
  eigen-power-method-shifted.sce
  eigen-inverse-power-method.sce
  eigen-inverse-power-method-shifted.sce
  lena.csv
```

## How to Run

1. Install [Scilab](https://www.scilab.org/) (open-source alternative to MATLAB).
2. Open any `.sce` file in the Scilab console or editor.
3. Execute the script. Input matrices and parameters can be adjusted directly in the source files.

## Notes

- Course content and code comments are in Portuguese.
- The SVD and rotation scripts use `lena.csv`, a CSV representation of the classic Lena test image.
