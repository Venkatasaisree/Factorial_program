# Factorial_program
def recur_factorial(n):
   """Function to return the factorial
   of a number using recursion"""
   if n == 1:
       return n
   else:
       return n*recur_factorial(n-1)
num = 7
if num > 0:
   print("The factorial of",num,"is",recur_factorial(num))
   
elif num == 0:
   print("The factorial of 0 is 1")
else:
  print("Sorry, factorial does not exist for negative numbers")
