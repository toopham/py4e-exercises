## Numerical Integration Project (Optional)

Numerical Integration

This project is optional and you are encouraged to work in a group to help each other but each person must turn in their own work.

Use numerical integration to approximate area A.

Write three functions in Python, each function takes in one parameter
where
= the number of intervals to use in the numerical integration.

Right(n) = return the approximated value of A using the right Riemann sum with n intervals.

Left(n) = return the approximated value of A using the left Riemann sum with n intervals.

Trapezoidal(n) = return the approximated value of A using the Trapezoidal Rule with n intervals.

Each function will return the approximated value of A rounded to 4 decimal places.

Name of Function Parameter(s) Return Possible Points
Right n = number of intervals. Approximated value of Area A rounded to 4 decimals using n right end points. 3
Left n = number of intervals. Approximated value of Area A rounded to 4 decimals using n left end points. 5
Trapezoidal n = number of intervals(must be even) Approximated value of Area A rounded to 4 decimals. 7
Total possible Points 15
Rules:

You can only use basic Python libraries such as math. You cannot use advanced libraries such as SciPy.

You may use helper functions that you write up yourself. For example, the add function below is a helper function to the sumOfThree function.

def add(a,b):
return a+b

def sumOfThree(x, y, z):
firstSum = add(x,y)
answer = add(firstSum, z)
return answer

print(sumOfThree(2,3,4))

Submission:
Write a file \*.py that contains these 3 functions inside this folder.
