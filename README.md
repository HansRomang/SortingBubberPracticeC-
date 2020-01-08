
What do we have here?

Here's a simple bubble sort algorithm for C#. The logic is:

-We have an unsorted array.
-We need to check the current index of the array with the element after our current index.
-If the element after our current index is GREATER than our current index, we swap these elements.
-We then loop this process until the entire array is complete.

This is not an efficient algorithm (O(n^2)), however it's some good practice. The difficulty for figuring this out lied in understanding that I essentially needed a temporary holder for the swapping of elements. 
