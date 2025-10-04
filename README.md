# Accept a list of numbers from the user
numbers = list(map(int, input("Enter numbers separated by spaces: ").split()))

# Initialize counters
even_count = 0
odd_count = 0

# Count even and odd numbers
for num in numbers:
    if num % 2 == 0:
        even_count += 1
    else:
        odd_count += 1

# Display the results
print(f"Even numbers count: {even_count}")
print(f"Odd numbers count: {odd_count}")
