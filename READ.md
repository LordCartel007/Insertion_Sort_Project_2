sort_insertion Algorithm

Description
The sort_insertion algorithm sorts an array of integers using the insertion sort method. Insertion sort is a simple sorting algorithm that builds the final sorted array one item at a time. It is efficient for small or nearly sorted arrays.

Variables
arr: An array of integers that will be sorted.
i: An integer variable used for iterating through the array.
j: An integer variable used to find the correct position for the key.
key: An integer variable used to hold the value being inserted into the sorted portion of the array.

Algorithm Steps

1.Read the Array:

2.Begin by reading the array arr from the user.

3.Perform Insertion Sort:

4.Loop through the array starting from the second element (index 1):

5.Set key to the current element arr[i].

6.Set j to the index just before i (i - 1).

7.Move elements that are greater than key one position to the right:

8.Continue this process until the correct position for key is found or until j is less than 0.

9.Place key at the correct position in the sorted portion of the array.

10.Output the Sorted Array:

11.Print the sorted array arr.
