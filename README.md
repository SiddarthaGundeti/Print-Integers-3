# Print-Integers-3

Question Explanation:

The program is designed to print all integers from a given integer N down to 1 in descending order.

Logical Approach:

Read Input:
Read the integer N.

Print Integers in Descending Order:
Initialize a loop that continues as long as N is greater than 0.
In each iteration of the loop, print the current value of N.
After printing, decrement N by 1 (i.e., N -= 1) to move to the next lower integer.
The loop exits when N becomes 0 or less.

Output:
Each iteration prints the current value of N, starting from the initial value down to 1.

Example for Clarity:

If the input N is 5:
The loop starts with N = 5. It prints 5 and decrements N to 4.
In the next iteration, it prints 4 and decrements N to 3.
This continues until N is decremented to 0, with the numbers 5, 4, 3, 2, 1 being printed in each iteration.
The output will be:

5

4

3

2

1

