### Programming Assignment 2 

This is the second assignment of "R Programming" (rprog-010) course at Coursera, submitted on Jan 10, 2015

### How to use the function?

1. Create a test matrix, e.g. 3x3 matrix
```R
TestMatrix <- matrix(c(9, -6, -1, 3, -9, -8, 5, 7 ,1), nrow=3, ncol=3)
```
2. Call the function, it should return the inverse of the test matrix for the first time.
If you call it the second time, it should return the cached value.
```R
cacheSolve(makeCacheMatrix(TestMatrix))
```