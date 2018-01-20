# Simple-calculator.py

num1=eval(input("Enter your first number, Please! "))
num2=eval(input("Enter your second number, Please! "))
total=0

sample=input("Please select the calculation: \n1) [+]\n2) [*]\n3) [-]\n4) [/]\n ")

if sample is ("1"):
  total= num1 + num2
  print("The result is ",total, "\nThank you!" )
elif sample is ("2"):
  total= num1 * num2
  print("The result is ",total, "\nThank you!" )
elif sample is ("3"):
  total= num1 - num2
  print("The result is ",total, "\nThank you!")  
elif sample is ("4"):
  total= num1 / num2
  print("The result is ",total, "\nThank you!")  
  
else:
  print(" Please select again! ")

