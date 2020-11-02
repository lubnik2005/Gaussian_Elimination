# Simple Gaussian Elimination

This is a simple script that calculates the solution in decimal form of a system of linear equations using the Gaussian Elmination method.

## Usage
```matlab
n = 4;
A = [ 
    pi -sqrt(2) -1 1 0;
    exp(1) -1 1 2 1;
    1 1 -sqrt(3) 1 2;
    -1 -1 1 -sqrt(5) 3;
];
disp(Gaussian_Elimination(A,n));
```