# Dereferencing a Null Pointer in C++

This repository demonstrates a common C++ error: dereferencing a null pointer.  The `bug.cpp` file contains the problematic code, which attempts to write to memory pointed to by a null pointer. This leads to undefined behavior, often resulting in a segmentation fault (crash).

The solution, in `bugSolution.cpp`, addresses the problem by checking for a null pointer before dereferencing.