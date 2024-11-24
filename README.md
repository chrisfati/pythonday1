# pythonday1
num1 = float(input("Enter first number:"))

num2 = float(input("Enter second number:"))

operation = float(input("Enter operation number:"))

if operation == "+":
    result = num1 + num2
    print(f"{num1} + {num2} = {result}")
    
elif operation == "-":
    result = num1 - num2
    print(f"{num1} - {num2} = {result}")
    
elif operation == "*":
    result = num1 * num2
    print(f"{num1} * {num2} = {result}")
    
elif operation == "/":
    if num2 != 0:
        result = num1 / num2
        print(f"{num1} / {num2} = {result}")
        
    else:
        print("Division by zero is not allowed.")
        
else:
    print("Invalid operation entered.")
