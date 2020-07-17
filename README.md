# Determinant-of-a-Matrix

Determinant of a Matrix is a special number that is defined only for square matrices (matrices which have same number of rows and columns). Determinant is used at many places in calculus and other matrix related algebra, it actually represents the matrix in term of a real number which can be used in solving system of linear equation and finding the inverse of a matrix.

How to calculate?
The value of determinant of a matrix can be calculated by following procedure –
For each element of first row or first column get cofactor of those elements and then multiply the element with the determinant of the corresponding cofactor, and finally add them with alternate signs. As a base case the value of determinant of a 1*1 matrix is the single value itself.
Cofactor of an element, is a matrix which we can get by removing row and column of that element from that matrix.

| a, b |
| c, d | ------> a * d - b * c

Input:
2
4
1 0 2 -1 3 0 0 5 2 1 4 -3 1 0 5 0
3
1 2 3 4 5 6 7 10 9

Output:
30
12

Explanation:
Testcase 1: Determinant of the given matrix is 30.
