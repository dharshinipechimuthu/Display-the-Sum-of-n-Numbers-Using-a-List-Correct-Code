# Display-the-Sum-of-n-Numbers-Using-a-List-Correct-Code
numbers = []
num = int(input("How many numbers: "))

for n in range(num):
    x = int(input("Enter number: "))
    numbers.append(x)

print("Sum of numbers in the given list is:", sum(numbers))

Output:
How many numbers: 4
Enter number: 5
Enter number: 10
Enter number: 15
Enter number: 20
Sum of numbers in the given list is: 50
