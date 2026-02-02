# program-86
# Define the list
numbers = [4, 2, 7, 1, 8, 3, 6]

# Initialize flag
f = 0  

# Input the number to search
x = int(input("Enter the number to be found: "))

# Linear search
for i in range(len(numbers)):
    if x == numbers[i]:
        print("Successful search, the element is found at position", i)
        f = 1
        break

# If not found
if f == 0:
    print("Oops! Search unsuccessful")
output
Enter the number to be found: 7
Successful search, the element is found at position 2
Enter the number to be found: 9
Oops! Search unsuccessful
