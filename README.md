# Euler_Method_Matlab
Done Using Matlab!
Simplest and oldest numerical computing formula.

Algorithm:
Start
Define function
Get the values of x0, y0, h and xn
*Here x0 and y0 are the initial conditions
h is the interval
xn is the required value
n = (xn – x0)/h + 1
Start loop from i=1 to n
y = y0 + h*f(x0,y0)
x = x + h
Print values of y0 and x0
Check if x < xn
If yes, assign x0 = x and y0 = y
If no, goto 9.
End loop i
Stop
