# Q.18-c-
def factorial(n):
  if n==0:
    return 1
  else:
       return n * factorial(n-1)
 number = int(input("enter a number:  "))
 print("the factorial of", number ,"is:" factorial(number) )
