# Aim:
Study Of For Loop In Python

## Theory:
Types of loops: for, while, nested.
A for loop in Python is a control flow statement that is used to execute a block of code repeatedly for a fixed number of times or over a sequence (such as list, tuple, string, or range).
The range() function is commonly used with for loop.
Syntax:
for variable in range(start, stop, step):
    statements
A nested for loop is a loop inside another loop.
The continue statement skips the current iteration.
The break statement terminates the loop.

## Algorithms:
A)Print numbers from 1 to 5

1)Start
2)Use for loop from 1 to 5 using range(1,6).
3)Print value of i.
4)End

B)Print even numbers from 2 to 10

1)Start
2)Use for loop from 2 to 10 with step 2.
3)Print each number.
4)End

C)Alternative method:
1)Start
2)Loop from 1 to 10.
3)If number is not divisible by 2, use continue.
4)Else print the number.
5)End

D)Add first n numbers using for loop

1)Start
2)Input value of n from user.
3)Initialize total = 0.
4)Loop from 1 to n.
5)Add each number to total.
6)Print total.
7)End

E)Print a matrix

1)Start
2)Define a 3×3 matrix.
3)Use nested for loop.
4)Print each element using indexing.
5)End

Alternative method:
1)Start
2)Iterate directly through each row of matrix.
3)Print row.
4)End

F)Multiplication of Two 3×3 Matrices

1)Start
2)Define matrix A and B.
3)Initialize result matrix with zeros.
4)Use three nested loops.
5)Multiply corresponding elements and store in result.
6)Print result matrix.
7)End

G)Generate permutations of three numbers

1)Start
2)Define list of three elements.
3)Use three nested loops.
4)Check condition that all three elements are different.
5)Print the permutation.
6)End

H)Create patterns using for loop

Right angle triangle:
1)Start
2)Loop from 1 to 9.
3)Print "* " multiplied by i.
4)End

Reverse triangle:
1)Start
2)Loop from 10 to 1 (decreasing).
3)Print "* " multiplied by i.
4)End

Pyramid pattern:
1)Start
2)Set number of rows.
3)Loop from 1 to row.
4)Print spaces and stars accordingly.
5)End

I)Print all prime numbers in range

1)Start
2)Loop from 2 to 50.
3)For each number, check divisibility from 2 to number-1.
4)If divisible, break.
5)Else print the number.
6)End

Conclusion:

Hence for loop was successfully studied in Python and different operations were performed using it.
