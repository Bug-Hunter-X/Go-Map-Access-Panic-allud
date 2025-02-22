# Go Map Access Panic

This repository demonstrates a common error in Go: accessing a map that hasn't been initialized.  Accessing a nil map will cause a runtime panic.  This example shows the problem and how to fix it.

## Bug

The file `bug.go` contains code that attempts to access an uninitialized map.  This will result in a panic when you run the program.

## Solution

The file `bugSolution.go` provides a corrected version of the code.  The solution uses the `make()` function to allocate the map before accessing it, preventing the panic.
