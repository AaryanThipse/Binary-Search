# Binary-Search<br>
Binary Search is defined as a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(log N). <br>
![Binary-Search-GeeksforGeeks](https://user-images.githubusercontent.com/124968304/234263125-a326fc7d-4271-4790-8e31-b31a6c494591.gif)<br>
# Conditions for when to apply Binary Search in a Data Structure:<br>
To apply binary search in any data structure, the data structure must maintain the following properties:<br>

1.The data structure must be sorted.<br>
2.Access to any element of the data structure takes constant time.<br>
# When to use Binary Search?<br>
1.When searching a large dataset as it has a time complexity of O(log n), which means that it is much faster than linear search.<br>
2.When the dataset is sorted.<br>
3.When data is stored in contiguous memory.<br>
4.Data does not have a complex structure or relationships.<br>
# How to Implement Binary Search?<br>
The basic steps to perform Binary Search are:<br>

1.Set the low index to the first element of the array and the high index to the last element.<br>
2.Set the middle index to the average of the low and high indices.<br>
*If the element at the middle index is the target element, return the middle index.<br>
*Otherwise, based on the value of the key to be found and the value of the middle element, decide the next search space.<br>
*If the target is less than the element at the middle index, set the high index to middle index – 1.<br>
*If the target is greater than the element at the middle index, set the low index to middle index + 1.<br>
3.Perform step 2 repeatedly until the target element is found or the search space is exhausted.<br>
The Binary Search Algorithm can be implemented in the following two ways<br>

1.Iterative Binary Search Algorithm<br>
2.Recursive Binary Search Algorithm<br>

