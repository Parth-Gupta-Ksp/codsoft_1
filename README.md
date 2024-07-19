print("Welcome to the Simple Calculator!")

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

print("\nChoose an operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")
choice = input("Enter the number corresponding to your choice (1/2/3/4): ")

if choice == "1":
    result = num1 + num2
    print(f"\nResult: {num1} + {num2} = {result}")
elif choice == "2":
    result = num1 - num2
    print(f"\nResult: {num1} - {num2} = {result}")
elif choice == "3":
    result = num1 * num2
    print(f"\nResult: {num1} * {num2} = {result}")
elif choice == "4":
    if num2 == 0:
        print("Error: Division by zero!")
    else:
        result = num1 / num2
        print(f"\nResult: {num1} / {num2} = {result}")
else:
    print("\nInvalid operation!")
