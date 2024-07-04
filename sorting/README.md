## Bubble Sort

- It is also called as sinking sort.
- While applying this sorting algorithm on unsorted array, the largest element tends to sink at the end of the array.
- It repeatedly compares pair of adjacent elements and swap them if they are in wrong order.

## Insertion Sort

- Insertion is a simple sorting algorithm that works the way we sort playing cards in our hands.
- In Insertion sort we divide the given array into two parts - sorted part and unsorted part.
- From unsorted part, we take the first element and place it in the correct position in sorted array. This is done by shifting all the elements which are larger than first element by one position.
- It repeats till sorted array is not empty.

## Selection Sort

- In Selection sort we divide the given array into two parts - sorted and unsorted part.
- The algorithm sorts an array by repeatedly finding the minimum in an unsorted array and making it part of the sorted array.
- From unsorted array we pick minimum element and swap it with leftmost elemement of unsorted part. After swap the elements now become the part of the sorted array.
- Its repeated till unsorted array is not empty.

## Merge Sort

- Merge sort is a divide and conquer algorithm.
- Divide - In this step the algorithm takes middle point of array and divide the array into two halves. The algorithm is carried out recursively for half arrays, until there are no more half arrays to divide.
- Conquer - In this step starting from the bottom, we sort and merge the divided arrays and get the sorted arrays.

## Quick Sort

- Quick sort is a divide and conquer algorithm. It involves 3 steps -
- Pivot Selection - We pick an element and mark it as pivot. The pivot element can be first element, last element or any random element.
- Partitioning - We reorder the array such that all elements greater than pivot comes after the pivot and all elements smaller than pivot comes before the pivot. The element equal to pivot can go either side of the pivot. After this partioning the pivot is at its corrected sorted position.
- Recursion - Recursively apply the above steps on the subarray formed to the left side of pivot and on the subarray formed on the right side of the pivot.