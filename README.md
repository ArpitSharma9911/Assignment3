# Assignment3
This repository contains Python scripts for basic programming practice.  

## 📌 Task 1: Calculate Factorial Using a Function 
### Problem Statement:  
Write a Python program that:  
1.   Defines a function named factorial that takes a number as an argument and calculates its factorial using a loop or recursion.
2.   Returns the calculated factorial.
3.   Calls the function with a sample number and prints the output.

### Code: 
def factorial(n):
    if n<2:
        return 1
    else:
        return n*factorial(n-1)
n=int(input("Enter number to find factorial of: "))
print("Factorial of",n,"is: ", factorial(n))

### Example Output:  
Enter number to find factorial of: 10
Factorial of 10 is:  3628800

## 📌 Task 2: Using the Math Module for Calculations
### Problem Statement:  
Write a Python program that:  
1.   Asks the user for a number as input.
2.   Uses the math module to calculate the:
o   Square root of the number
o   Natural logarithm (log base e) of the number
o   Sine of the number (in radians)
3.   Displays the calculated results.


### Code: 
import math

def sqrt(n):
    return math.sqrt(n)

def log(n):
    return math.log(n)

def sin(n):
    return math.sin(n)

x=float(input("Enter any number: "))
print ("Square root of",x,"is:",sqrt(x))
print ("Log of",x,"is:",log(x))
print ("sin of",x,"is:",sin(x))

### Example Output:  
Enter any number: 30
Square root of 30.0 is: 5.477225575051661
Log of 30.0 is: 3.4011973816621555
sin of 30.0 is: -0.9880316240928618
