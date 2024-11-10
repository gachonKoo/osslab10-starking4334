import sys

if len(sys.argv) < 2:
    print("Usage: python script.py <number>")
    sys.exit(1)

try:
    number = int(sys.argv[1])
except ValueError:
    print("Please enter a valid integer.")
    sys.exit(1)
    
for i in range(1, number + 1):
    if number % i == 0:
        print(i, end=" ")

print()
