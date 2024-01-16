- Linear search is defined as a sequential search algorithm that starts at one end and goes through each element of a list until the desired element is found, otherwise the search continues till the end of the data set.
![linear search](https://media.geeksforgeeks.org/wp-content/cdn-uploads/Linear-Search.png)
### How Does Linear Search Algorithm Work?
In linear search algorithm,
- Every element is considered as a potential match for the key, and checked for the same.
- If any element is found equal to the key, the search is successful and the index of that element is returned.
- If no element is found equal to the key, the search yields "No Match Found".
### Complexity Analysis Of Linear Search
**Time Complexity:**
- **Best Case:** In the best case, the key might be present at the first index. So the best case complexity is O(1).
- **Worst Case:** In the worst case, the key might be present at the last index, opposite to the end from which the search has started in the list. So, the worst case complexity is O(N) where N is the size of the list.
- **Average Case:** O(N).
- 
