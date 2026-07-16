# Bubble Sort

## Description

Bubble Sort is a comparison-based sorting algorithm that repeatedly compares adjacent elements and swaps them if they are in the wrong order. After each pass, the largest unsorted element moves to its correct position at the end of the array. This process continues until the entire array is sorted.

## Algorithm

1. Start from the beginning of the array.
2. Compare each pair of adjacent elements.
3. If the left element is greater than the right element, swap them.
4. Continue comparing adjacent elements until the end of the unsorted portion.
5. After each pass, the largest element is placed in its correct position.
6. Repeat the process for the remaining unsorted portion until the array is sorted.

## Time Complexity

* **Best Case:** O(n²)
* **Average Case:** O(n²)
* **Worst Case:** O(n²)

> **Note:** If Bubble Sort is optimized using a swapped flag, the best-case time complexity becomes **O(n)**.

## Space Complexity

* **O(1)**
