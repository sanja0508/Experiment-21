# Experiment-21

Aim: To implement and demonstrate three sorting algorithms in C++:
Selection Sort using pointers
Bubble Sort using array elements
Quick Sort using array elements

Software Required: Visual Studio

Theory: Sorting is a fundamental operation in computer science and programming, involving the arrangement of data elements in a specific order—typically ascending or descending. Efficient sorting is crucial for optimizing performance in various applications such as searching, data analysis, and algorithm design. 
Sorting algorithms are broadly classified into two categories: comparison-based and non-comparison-based. 
In this experiment, we focus on three comparison-based algorithms: Selection Sort, Bubble Sort, and Quick Sort.
Selection Sort: Selection Sort is a simple, intuitive algorithm that divides the array into a sorted and an unsorted region. It repeatedly selects the minimum (or maximum) element from the unsorted region and swaps it with the first unsorted element, thereby expanding the sorted region one element at a time.
Mechanism:
Traverse the array to find the smallest element.
Swap it with the element at the current position.
Move to the next position and repeat until the entire array is sorted.
Characteristics:
In-place sorting (no extra memory required).
Time complexity: O(n²) for all cases (best, average, worst).
Stable only if implemented carefully.
Suitable for small datasets or educational purposes.

Bubble Sort: Bubble Sort is another elementary sorting technique that works by repeatedly swapping adjacent elements if they are in the wrong order. With each pass, the largest unsorted element "bubbles up" to its correct position at the end of the array.
Mechanism:
Compare adjacent elements.
Swap them if they are out of order.
Repeat the process until no swaps are needed.
Characteristics:
Simple to implement and understand.
Time complexity: O(n²) in worst and average cases; O(n) in best case (already sorted).
Stable sort.
Inefficient for large datasets.

Quick Sort: Quick Sort is a highly efficient, recursive divide-and-conquer algorithm. It selects a pivot element and partitions the array such that elements less than the pivot are placed on the left and those greater on the right. It then recursively applies the same logic to the subarrays.
Mechanism:
Choose a pivot (commonly the last element).
Partition the array around the pivot.
Recursively sort the left and right partitions.
Characteristics:
Time complexity: Best and average case: O(n log n)
Worst case: O(n²) (when pivot selection is pool)
In-place but not stable.
Performs well on large datasets.
Can be optimized using techniques like randomized pivoting and tail recursion.

Conclusion: In this experiment, we implemented and analyzed three sorting algorithms: Selection Sort using pointers, Bubble Sort using array elements, and Quick Sort using array elements. These algorithms illustrate different strategies for sorting data:
Selection Sort and Bubble Sort are simple and intuitive, making them suitable for small datasets and educational purposes.
Quick Sort, on the other hand, is significantly more efficient for larger datasets due to its divide-and-conquer approach.
Understanding and implementing these algorithms enhances algorithmic thinking and strengthens problem-solving skills in programming. 
This experiment also highlights the importance of choosing the right sorting technique based on the size and nature of the dataset.

