PALLAWI KUMARI 25070123083
AIM : FOR LOOPS IN PYTHON
Theory: A for loop in Python is used to iterate (loop) over a sequence of items, executing a block of code once for each item.

Advantage of for loop over while loop.

A for loop is easier to use when you know how many times you want to repeat something.
It automatically handles iteration over sequences like lists, strings, and ranges.
It reduces the chance of creating an infinite loop by mistake.
The code is usually shorter and more readable than a while loop.
It requires less manual setup (no need to update the loop variable manually)

 1.Algorithm to Print a Range of Numbers

Start
1.Input or define the starting number (start).
2.Input or define the ending number (end).
3.Define the step value (how much the number should increase each time).
4.Use a for loop with range(start, end, step).
5.Print the current number inside the loop.
6.Repeat until the number reaches the end limit (end value is not included).
7.Stop


 2.Algorithm to Find Sum of First n Numbers

1.Start
2.Input the value of n from the user.
3.Initialize a variable total = 0 (to store the sum).
4.Start a loop from 1 to n using range(1, n+1).
5.For each value of i, add i to total.
6.Print the current value of total (this shows the running sum).
7.Repeat steps 5–6 until the loop ends.
8.Stop

 3.Algorithm to Print a 3×3 Matrix

1.Start
2.Create three lists l1, l2, and l3 representing rows of the matrix.
3.Combine these lists into a single list a to form a 3×3 matrix.
4.Use an outer loop with variable i from 0 to 2 (to access each row).
5.Inside the outer loop, use an inner loop with variable j from 0 to 2 (to access each column element).
6.Print the element at position a[i][j].
7.After printing one row, move to the next line using print().
8.Repeat until all rows and columns are printed.
9.Stop

Another method to print matrix

1.Start
2.Create three lists l1, l2, and l3 representing rows of the matrix.
3.Combine the three lists into a single list a (matrix).
4.Use a for loop to iterate through each element (row) in list a.
5.In each iteration, assign the current row to the variable row.
6.Print the value of row.
7.Repeat until all rows are printed.
8.Stop

4. Algorithm for Matrix Multiplication

1.Start
2.Input or define two matrices:
3.Matrix A of order m × n
4.Matrix B of order n × p
(Number of columns in A must equal number of rows in B.)
5.Create an empty result matrix C of order m × p and initialize all elements to 0.
6.Use an outer loop to iterate through rows of matrix A (index i).
7.Use a second loop to iterate through columns of matrix B (index j).
8.Initialize C[i][j] = 0.
9.Use a third loop to iterate through columns of A / rows of B (index k).
10.Multiply A[i][k] and B[k][j] and add the result to C[i][j].
11.Repeat until all rows and columns are processed.
12.Print the result matrix C.

 5.Algorithm to Print All Possible Combinations of Three Digits

1.Start
2.Assign three digits to variables d1, d2, and d3.
3.Store the digits in a list d.
4.Use an outer loop with index i from 0 to 2.
5.Use a second loop with index j from 0 to 2.
6.Use a third loop with index k from 0 to 2.
7.Inside the loops, check the condition:
 d[i] is not equal to d[j]
 d[i] is not equal to d[k]
 d[j] is not equal to d[k]
(This ensures all three digits are different.)
8.If the condition is true, print the combination d[i], d[j], d[k].
9.Repeat until all possible index combinations are checked.
10.Stop

6. Algorithm to Print a Right-Angle Triangle

1.Start
2.Decide the number of rows for the triangle (here 12).
3.Use a for loop with a variable i starting from 12 down to 1 (step -1).
4.In each iteration, print the character @ repeated i times.
5.After printing, move to the next line automatically (because print() does it).
6.Repeat step 4–5 until i reaches 1.
7.Stop

7. Algorithm to Print a Pyramid Pattern

1.Start
2.Set the number of rows for the pyramid (row = 6).
3.Use a for loop with variable i from 1 to row (inclusive).
4.In each iteration:
Print spaces: " " * (row - i) → to center the stars.
Print stars: "* " * i → number of stars increases with each row.
5.After printing spaces and stars, move to the next line automatically.
6.Repeat step 4 until all rows are printed.
7.Stop

CONCLUSION :The for loop in Python efficiently repeats a block of code over a sequence, handling iterations automatically.
