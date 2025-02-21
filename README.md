operator = input("Please enter the operator (+, -, *, /): ")
num1 = float(input("please enter the first number"))
num2 = float(input("Please enter the second number: "))
if operator == "+":
  print(num1 + num2)
elif operator == "-":
 print(num1 - num2)
elif operator == "/":
 print(num1/num2)
elif operator == "*":
 print(num1*num2)
else:
 print("wrong operator try agin")
