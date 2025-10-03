import math

def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Error! Division by zero."
    return a / b

def factorial(n):
    if n < 0:
        return "Error! Factorial of negative number doesn't exist."
    return math.factorial(n)

def is_prime(n):
    if n <= 1:
        return False
    for i in range(2, int(math.sqrt(n)) + 1):
        if n % i == 0:
            return False
    return True

# Main Program
while True:
    print("\n--- Math Calculator ---")
    print("1. Addition")
    print("2. Subtraction")
    print("3. Multiplication")
    print("4. Division")
    print("5. Factorial")
    print("6. Prime Check")
    print("7. Exit")

    choice = input("Enter your choice (1-7): ")

    if choice in ['1', '2', '3', '4']:
        a = int(input("Enter first number: "))
        b = int(input("Enter second number: "))

        if choice == '1':
            print("Result:", add(a, b))
        elif choice == '2':
            print("Result:", subtract(a, b))
        elif choice == '3':
            print("Result:", multiply(a, b))
        elif choice == '4':
            print("Result:", divide(a, b))

    elif choice == '5':
        n = int(input("Enter a number: "))
        print("Factorial:", factorial(n))

    elif choice == '6':
        n = int(input("Enter a number: "))
        print("Prime:", is_prime(n))

    elif choice == '7':
        print("Exiting... Goodbye!")
        break

    else:
        print("Invalid choice! Please enter between 1-7.")
