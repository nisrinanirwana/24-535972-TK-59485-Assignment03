Assignment03-Arrays

University: Universitas Gadjah Mada

Name: Nisrina Puspita Nirwana

Student ID: 24/535972/TK/59485
Overview

This repository contains the solutions for Assignment 03, which focuses on implementing a dynamic array and comparing search algorithms in C++.

The repository includes:

problem2.cpp — Implementation of a dynamic resizable array (DynArray) using a struct and manual memory management.

problem3.cpp — Implementation and comparison of Linear Search and Binary Search on sorted arrays.


Problem 2 — Dynamic Array

Implements a dynamic array without using STL containers.

Key features:

Automatic capacity doubling when the array becomes full

Manual memory management using new[] and delete[]

Operations implemented:

initArray

freeArray

pushBack

insertAt

removeAt

getAt

setAt

printDynArr

The main() function demonstrates resizing, insertion, deletion, and element access.


Problem 3 — Search Algorithms

Implements and compares two search algorithms:

Linear Search — sequential search through the array

Binary Search — iterative search on a sorted array

Testing is performed on arrays of size:

n = 10

n = 100

n = 1000

Each test searches for:

an existing element

a non-existing element

Both algorithms should return consistent results.


Compilation
g++ -std=c++17 -Wall -Wextra -o problem2 problem2.cpp
g++ -std=c++17 -Wall -Wextra -o problem3 problem3.cpp


Running
./problem2
./problem3


Time Spent

Approximate time spent completing the assignment: ~10 hours
