
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Error: Cannot divide by zero."
    return a / b

def power(a, b):
    return a ** b

def get_number(prompt):
    while True:
        try:
            return float(input(prompt))
        except ValueError:
            print("Invalid input. Please enter a valid number.")

def main():
    while True:
        print("\n--- Basic Calculator Menu ---")
        print("1. Perform a Calculation")
        print("2. Exit")

        choice = input("Choose an option: ")

        if choice == "1":
            num1 = get_number("Enter first number: ")
            num2 = get_number("Enter second number: ")
            op = input("Enter operation (+, -, *, /, ^): ")

            if op == "+":
                print("Result:", add(num1, num2))
            elif op == "-":
                print("Result:", subtract(num1, num2))
            elif op == "*":
                print("Result:", multiply(num1, num2))
            elif op == "/":
                print("Result:", divide(num1, num2))
            elif op == "^":
                print("Result:", power(num1, num2))
            else:
                print("Invalid operation.")

        elif choice == "2":
            print("Goodbye!")
            break
        else:
            print("Invalid menu option. Try again.")

if __name__ == "__main__":
    main()
