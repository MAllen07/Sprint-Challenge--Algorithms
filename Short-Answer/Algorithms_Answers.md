#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I
a) runtime = (n * n * n)/(n * n) = n
this algorithm has a runtime of 0(n)

b) runtime = n * n * n * 10
this algorithm has a runtime of 0(n**3)

c) this algorithm has a runtime of 0(n)

## Exercise II

you can use  binary search, which is O(log n) 
Step 1: find the midpoint of the building by dividing the total number of floors in half 
Step 2: compare midpoint to f if equal return index of f if midpoint > f, f must be in left sub-array if midpoint < f, f must be in right sub-array
Step 3: repeat on subsequent sub-arrays until midpoint == f


