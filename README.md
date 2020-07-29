title: "DATA STRUCTURE AND ALGORITHM"
ADT: "Matrix Data Type"
---

# Implementation of the Matrix Abstract Data Type

### Methods to be implemented 
- numRows()     -       Returns the number of rows of the Matrix ADT
- numCols()     -       Returns the number of columns of the Matrix ADT
- dimension()   -       Returns the dimension of the Matrix ADT
- getitem(row, col) -   Returns the element at a particular (row, col) of the Matrix ADT
- setitem(row, col, scalar) -   Sets scalar at a particular (row, col) position of the Matrix ADT
- scaleBy(scale)    -   Returns a new Matrix scaled by (scale)
- transpose()   -       Returns a transpose a matrix 
- add(rhsMatrix)-       Adds a matrix to the rhsMatrix and returns it
- subtract(rhsMatrix) - Subtracts a matrix to the rhsMatrix and returns it
- multiply(rhsMatrix) - Multiplies a matrix to the rhsMatrix and returns it


### How the Matrix ADT can be used 
matrixA = Matrix(2, 2)      -       This creates a 2 x 2 matrix object
matrixB = Matrix(2, 2)      -       This creates a 2 x 2 matrix object

matrixA.numRows()   -   Returns 2
matrixB.numCols()   -   Returns 2

matrixB.dimension() -   Returns the dimension of a matrix
matrix[1][0]        -   Returns the value at row 1 and col 0
matrix[1][1] = 5    -   Sets the value 5 at the position (1, 1)

etc...