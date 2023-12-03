# 105Torus 🍩

Welcome to **105torus**.

A fascinating exploration into the mathematics of complex shapes within the curriculum.

This project delves into solving 4th-degree polynomial equations, which are crucial in rendering shapes like toruses.

## Language and Tools 🛠️

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

- **Language:** Python
- **Binary Name:** 105torus

## Project Overview 📜

The objective is to solve 4th degree equations of the form: a4x^4 + a3x^3 + a2x^2 + a1x^1 + a0 = 0, using iterative algorithms. The project focuses on three methods:

- The bisection method,
- Newton’s method,
- The secant method.

### Usage

`./105torus opt a0 a1 a2 a3 a4 n`


#### DESCRIPTION
- `opt`: Method option (1 for bisection, 2 for Newton, 3 for secant).
- `a[0-4]`: Coefficients of the equation.
- `n`: Precision (the application of the polynomial to the solution should be smaller than 10^-n).

### Examples

#### Example 1

`Input: ./105torus 1 -1 0 6 -5 1 6`<br>

`Output: Bisection method iterations and solution.`<br>

#### Example 2

`Input: ./105torus 2 -1 0 6 -5 1 12`<br>

`Output: Newton’s method iterations and solution.`<br>


*Note: Precision in calculations is crucial for the accuracy of the solution.*

## Installation and Usage 💾

1. Clone the repository.
2. Compile the program using the provided Makefile.
3. Run the program: `./105torus opt a0 a1 a2 a3 a4 n`.
4. For detailed guidelines, refer to `105torus.pdf`.

## License ⚖️

This project is released under the MIT License. See `LICENSE` for more details.
