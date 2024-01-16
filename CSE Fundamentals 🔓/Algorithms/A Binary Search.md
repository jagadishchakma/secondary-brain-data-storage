- Binary search is defined as a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(log$_2^n$) 
### Conditions for when to apply Binary Search in a Data Structure
To apply binary search algorithm:
- The data structure must be sorted.
- Access to any element of the data structure takes constant time.
### Binary Search Algorithm
In this algorithm:
- Divide the search space into two halves by finding the middle idnex.
- Compare the middle element of the search space with the key.
- If the key is found at middle element, the process is terminated.
- If the key is not found at middle element, choose which half will be used as the next search space.
	- If the key is smaller than the middle element, then the left side is used for next search.
	- If the key is larger than the middle element, then the right side is used for next search.
- The process is continued until the key is found or the total search space is 