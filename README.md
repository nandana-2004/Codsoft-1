#CALUCULATOR

print("Choose an operator to perform:")
print("1.ADD")
print("2.SUB")
print("3.MUL")
print("4.DIV")

operation = input()

if operation == "1":
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))
    print("The sum is " +str(num1 + num2))
elif operation == "2":
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))
    print("The difference is " + str(num1 - num2))
elif operation == "3":
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))
    print("The product is " + str(num1 * num2))
elif operation == "4":
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))
    print("The result is " + str (num1 / num2))
else:
    print("Invalid ")
