# Selection Sort in Java

## Description
This program demonstrates the implementation of **Selection Sort** in Java.
Selection sort repeatedly selects the **smallest or largest element** from the unsorted part of the array and places it in its correct position.

## How It Works (Ascending Order)
- Reads the size of the array
- Stores elements in an array
- Finds the **minimum element** in the unsorted part
- Swaps it with the first unsorted position
- Repeats the process until the array is sorted in ascending order

## How It Works (Descending Order)
- Reads the size of the array
- Stores elements in an array
- Finds the **maximum element** in the unsorted part
- Swaps it with the first unsorted position
- Repeats the process until the array is sorted in descending order

## Input Format
<array_size>
<array_elements>

## Sample Input
5
64 25 12 22 11

## Output (Ascending Order)
11 12 22 25 64

## Output (Descending Order)
64 25 22 12 11

## Time Complexity
- Best Case: O(n²)
- Average Case: O(n²)
- Worst Case: O(n²)

## Space Complexity
O(1)

## Characteristics
- In-place sorting
- Not stable
- Not adaptive

## File Name
Ssort.java
