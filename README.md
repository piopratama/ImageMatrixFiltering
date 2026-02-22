# Matrix Filtering – Digital Image Processing

[![DOI](https://zenodo.org/badge/493962051.svg)](https://doi.org/10.5281/zenodo.18732246)

This project implements fundamental spatial filtering techniques using matrix-based convolution concepts.  
The system allows users to manually create an input matrix and apply different filtering methods to observe how each operator transforms the data.

Developed for coursework in Digital Image Processing.

Author:  
I Wayan Pio Pratama


------------------------------------------------------------
OVERVIEW
------------------------------------------------------------

The application demonstrates how filtering operations work mathematically on matrices without relying on external image processing libraries.

Users can:

- Define input matrix dimensions
- Define kernel dimensions
- Select filtering method
- Use predefined edge detection masks
- Apply custom convolution masks
- View resulting output matrix


------------------------------------------------------------
IMPLEMENTED FILTERS
------------------------------------------------------------

1. Median Filter
2. Mean Filter
3. Robert Cross Operator
4. Gradient Filtering
5. Sobel Operator


------------------------------------------------------------
ALGORITHMS USED
------------------------------------------------------------

Median Filter:
- Sorts values inside the kernel window
- Selects middle value (odd case)
- Averages two middle values (even case)

Mean Filter:
- Computes average of all values inside kernel window

Edge Detection (Robert, Gradient, Sobel):
- Applies Gx and Gy masks
- Performs convolution
- Computes magnitude using:

  magnitude = sqrt(Gx^2 + Gy^2)

All operations are implemented manually using JavaScript matrix calculations.


------------------------------------------------------------
TECHNOLOGY STACK
------------------------------------------------------------

- HTML
- JavaScript
- jQuery
- Bootstrap

No external image processing libraries are used.
All filtering logic is implemented from scratch.


------------------------------------------------------------
HOW TO RUN
------------------------------------------------------------

1. Open the HTML file in a web browser.
2. Set input matrix row and column.
3. Click "Create".
4. Select filtering type.
5. Set kernel size if required.
6. Click "Create" kernel.
7. Click "Process".
8. View output matrix.


------------------------------------------------------------
ACADEMIC PURPOSE
------------------------------------------------------------

This project was built to help students understand:

- Spatial filtering concepts
- Convolution mechanics
- Edge detection operators
- Differences between linear and non-linear filters
- Matrix-based image processing fundamentals


------------------------------------------------------------
CITATION
------------------------------------------------------------

If you use this software in academic work, please cite:

Pratama, I. W. P. (2026). Matrix Filtering – Digital Image Processing [Software]. https://doi.org/10.5281/zenodo.18732246


------------------------------------------------------------
LICENSE
------------------------------------------------------------

This project is intended for academic and educational use.
