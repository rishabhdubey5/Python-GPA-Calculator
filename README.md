# Python-GPA-Calculator
Our goal is to make a python script that takes in an array of grades as input, processes these inputs and computes the weighted average and sum and then outputs the current grade.

**Explanation of the code**
First, we have declared a function name as gpa_calculator with grades as its parameter.
Then, we had declared variables such as points to count the points as grades are entered.
Declared an iterable variable i starting with 0
Given a condition that the list of grades should not be empty. If the grades are not entered, then we will not calculate the GPA. Hence it will return None.
If grades are entered, then we will move to the iteration. The iteration i will start from 0 and will go up to the length of the list. For example, if the grades = [ ‘A’, ‘B’, ‘A’, ‘C’] then the length will be 4 hence the loop will iterate up to 4.

A = 4.0, 
A- = 3.67, 
for B+ = 3.33, 
B = 3.0, 
B- = 2.67,
for C+ = 2.33, 
C = 2.0,
C- = 1.67, 
D+ = 1.33,
 D = 1.0
 F = 0.0

Now the iteration stops thus the final value of points becomes 13.0
To calculate the GPA, we have the formula as points/len(grades). 
In our case, it becomes 13.0/4 = 3.25
Thus we get to print the GPA as 3.25.
