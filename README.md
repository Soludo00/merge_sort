# Merge Sort for Divide and Conquer

## Overview

In this project I implemented Merge Sort, which is a sorting algorithm based on the divide and conquer approach.

The main idea behind merge sort is to repeatedly divide the array into smaller parts, sort those parts, and then merge them back together in sorted order.

Unlike some other sorting algorithms, merge sort guarantees a consistent running time and works well even for larger lists of numbers.


## How the Algorithm Works

Merge sort works in three main steps:

1. Divide 
   The array is split into two halves.

2. Conquer
   Each half is recursively sorted using the same merge sort algorithm.

3. Merge
   The two sorted halves are merged together to form one fully sorted array.

This process continues until the subarrays contain only one element, because a single element is already considered sorted.



## Time Complexity

The time complexity of Merge Sort is O(n log n).

This happens because:

- The array is divided about log n times
- Each level of merging processes n elements

So the total work done is proportional to n log n.

One advantage of merge sort is that its time complexity remains the same in the best case, average case, and worst case.


## Implementation

The algorithm is implemented in C++.

The program creates a sample array of numbers and then sorts it using merge sort.

Source file:

src/merge_sort.cpp


## What I Learned

While implementing merge sort I learned more about:

- how divide and conquer algorithms work
- how recursion can break large problems into smaller ones
- how the merge step combines sorted subarrays
- why merge sort has a consistent O(n log n) runtime

## Program Output

Below is a screenshot of the program running in VS Code.

![Merge Sort Program Output](MergeSort.png)