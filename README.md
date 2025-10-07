Aim:

To implement sorting algorithms in C++:
- Bubble Sort using pointers.
- Insertion Sort.
- Bubble Sort using array indexing.

Apparatus:

- C++ Programming Language  
- Standard C++ compiler (GCC, g++, etc.)  
  
Program Explanation:

Program 1: Bubble Sort using Pointers  
- Uses pointers to traverse and compare elements of the array.  
- Swaps values by manipulating memory addresses.  
- Implements the bubble sort logic to sort the array in ascending order.

Program 2: Insertion Sort  
- Iterates through the array, growing a sorted portion one element at a time.  
- Inserts the current element into its correct position within the sorted portion.  
- Uses array indexing for element comparison and shifting.

Program 3: Bubble Sort using Array Indexing  
- Uses traditional array indexing to implement bubble sort.  
- Iterates through the array multiple times, swapping adjacent elements if out of order.  
- Sorts the array in ascending order.

Algorithm:

Bubble Sort using Pointers:  
1. Initialize pass counter.  
2. Loop until all passes are completed.  
3. Compare adjacent elements using pointer arithmetic.  
4. Swap values if the left element is greater than the right.  
5. Increment pass counter and move pointer forward.

Insertion Sort:  
1. Iterate from the second element to the end of the array.  
2. Store the current element as `key`.  
3. Compare `key` with elements before it.  
4. Shift elements larger than `key` one position ahead.  
5. Insert `key` at its correct sorted position.

Bubble Sort using Array Indexing:  
1. Loop over the array multiple times.  
2. For each pair of adjacent elements, compare and swap if needed.  
3. Reduce the range for each subsequent pass as the largest elements settle at the end.  
4. Repeat until the entire array is sorted.

Key Concepts:

- Sorting Algorithms: Techniques to reorder elements into ascending or descending order.  
- Bubble Sort: Simple comparison-based sorting that repeatedly swaps adjacent elements.  
- Insertion Sort: Builds the sorted array one item at a time by inserting elements into their correct position.  
- Pointers: Used in the first program to manipulate array elements directly by memory address.  
- Array Indexing: Access elements directly via indices in the array.  
- Time Complexity: Both Bubble Sort and Insertion Sort generally run in O(n²) time in the worst case.

Conclusion:

These programs demonstrate basic sorting techniques implemented in C++:

- Bubble Sort implemented in two ways: using pointers and array indexing, showing versatility in approach.  
- Insertion Sort offering an alternative method that can be efficient for nearly sorted data.  

Understanding these fundamental sorting algorithms helps build a foundation for learning more advanced and efficient sorting methods used in software development.

