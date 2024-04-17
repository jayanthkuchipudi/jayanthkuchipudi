def factorial(n):
    """Calculate the factorial of a number using recursion."""
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
num = 90
print(f"The factorial of {num} is {factorial(num)}")
