# Aim:
Study Of For Loop In Python

## Theory:
A for loop in Python is used to iterate over a sequence (such as a list, tuple, string, dictionary, set, or range) and execute a block of code repeatedly — once for each item in that sequence.
The range() function generates a sequence of numbers.
Break: Stops the loop completely.
Continue: Skips the current iteration.
Multiplying two 3x3 Matrix: for i in range(3): # rows of a
for j in range(3): # rows of b
for k in range(3):
result[i][j] += a[i][k] * b[k][j]
for row in result:
print(row)
## Algorithms:
A) Print Numbers from 1 to 5

Start

Write a for loop using syntax:
for i in range(1, 6):

Inside the loop, print the value of i using:
print(i)

End

B) Print Even Numbers from 2 to 10

Start

Write a for loop with step value 2:
for i in range(2, 11, 2):

Print each value of i:
print(i)

End

C) Alternative Method to Print Even Numbers

Start

Use loop from 1 to 10:
for i in range(1, 11):

Check condition:
if i % 2 != 0:

If true, skip using:
continue

Else print the number:
print(i)

End

D) Add First n Numbers Using for Loop

Start

Take input from user:
n = int(input("Enter value of n: "))

Initialize total:
total = 0

Use loop from 1 to n:
for i in range(1, n + 1):

Add each number to total:
total = total + i

Print total:
print(total)

End

E) Print a 3×3 Matrix

Start

Define matrix:
matrix = [[1,2,3],[4,5,6],[7,8,9]]

Use nested loop:

for i in range(3):
    for j in range(3):

Print each element using indexing:
print(matrix[i][j], end=" ")

End

Alternative Method:

Start

Iterate directly through rows:
for row in matrix:

Print row:
print(row)

End

F) Multiplication of Two 3×3 Matrices

Start

Define matrices A and B:
A = [[...],[...],[...]]
B = [[...],[...],[...]]

Initialize result matrix with zeros:
result = [[0,0,0],[0,0,0],[0,0,0]]

Use three nested loops:

for i in range(3):
    for j in range(3):
        for k in range(3):

Multiply and store result:
result[i][j] += A[i][k] * B[k][j]

Print result matrix

End

G) Generate Permutations of Three Numbers

Start

Define list:
nums = [1,2,3]

Use three nested loops:

for i in nums:
    for j in nums:
        for k in nums:

Check condition:
if i != j and j != k and i != k:

Print permutation:
print(i, j, k)

End

H) Create Patterns Using for Loop
1) Right Angle Triangle

Start

Loop from 1 to 9:
for i in range(1, 10):

Print pattern:
print("* " * i)

End

2) Reverse Triangle

Start

Loop from 10 to 1:
for i in range(10, 0, -1):

Print pattern:
print("* " * i)

End

3) Pyramid Pattern

Start

Set number of rows:
rows = 5

Loop from 1 to rows:
for i in range(1, rows + 1):

Print spaces and stars:
print(" " * (rows - i) + "* " * i)

End

I) Print All Prime Numbers in Range 2 to 50

Start

Loop from 2 to 50:
for num in range(2, 51):

For each number, check divisibility:

for i in range(2, num):

If divisible (num % i == 0), use:
break

Else (if loop completes), print number using:

else:
    print(num)

End
Conclusion:

Hence for loop was successfully studied in Python and different operations were performed using it.
