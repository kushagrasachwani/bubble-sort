# Bubble-sort
Bubble sort is a simple sorting algorithm that works by repeatedly swapping adjacent elements if they are in the wrong order. The algorithm gets its name from the way smaller elements "bubble" to the top of the list.
# Algoritm
Here is a detailed explanation of how the bubble sort algorithm works:

1. Start by iterating through the list of elements to be sorted, comparing each element to its adjacent element.
2. If an element is greater than its adjacent element, swap the two elements.
3. Continue iterating through the list, comparing and swapping adjacent elements, until no more swaps are needed. This indicates that the list is now sorted.
4. Repeat steps 1-3 until the entire list is sorted.
# Explation Example
Let's take an example to illustrate how bubble sort works. Consider the following list of integers:

[5, 2, 8, 3, 6]

We start by comparing the first two elements (5 and 2) and swapping them because 2 is smaller than 5:

[2, 5, 8, 3, 6]

Next, we compare the second and third elements (5 and 8) and do not need to swap them because they are already in the correct order:

[2, 5, 8, 3, 6]

We continue iterating through the list, comparing and swapping adjacent elements until we reach the end of the list. After the first iteration, the largest element (8) is at the end of the list:

[2, 5, 3, 6, 8]

We repeat the process starting from the first element again. This time, we swap the second and third elements (5 and 3):

[2, 3, 5, 6, 8]

After the second iteration, the second largest element (6) is at the end of the list:

[2, 3, 5, 6, 8]

We repeat the process again, starting from the first element. This time, we do not need to swap any elements because the list is already sorted.

The final sorted list is:

[2, 3, 5, 6, 8]
# Application 
1. Bubble sort can be useful in situations where the data set to be sorted is small or nearly sorted. It is simple to implement and does not require any additional data structures.

2. One application of bubble sort is in sorting small lists or arrays of data. Bubble sort has a time complexity of O(n^2), which means that it is not efficient for large data sets. However, for small data sets, the overhead of more efficient algorithms may outweigh the benefits.

3. Bubble sort can also be used as a teaching tool to introduce students to the concept of sorting algorithms. Its simplicity makes it easy to understand and implement, and it can be a good starting point for learning more advanced sorting algorithms.

4. Bubble sort can be used as a component of other sorting algorithms, such as cocktail sort and gnome sort. These algorithms build on the basic principles of bubble sort to create more efficient and effective sorting methods.
# Screenshot
![p3](https://user-images.githubusercontent.com/126184012/234287739-e0b5e033-64fc-4ca8-b963-7f6343d3ac96.png)
