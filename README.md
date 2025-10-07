# Implement---Searching-Algorithms
To study and implement different searching algorithms such as Linear Search and Binary Search using C++.

## Aim 

To understand how searching techniques work to find a specific element from a list or array and compare their efficiency.

## 📘 Theory  
Searching is a process used to find the location of a specific element in a collection of data such as an array or list.  
There are two common searching methods:

### **1. Linear Search**
- It checks each element one by one until the required element is found or the list ends.  
- It is simple but not efficient for large datasets.  
- **Time Complexity:** O(n)

### **2. Binary Search**
- Works only on **sorted arrays**.  
- Repeatedly divides the array into two halves and checks the middle element.  
- Much faster than linear search.  
- **Time Complexity:** O(log n)

| Algorithm | Works On | Speed | Efficiency |
|------------|-----------|--------|-------------|
| Linear Search | Unsorted or Sorted | Slow | Less Efficient |
| Binary Search | Sorted Only | Fast | More Efficient |

Searching algorithms are used in real-world applications like **databases, dictionaries, and file systems** for quick data retrieval.

## Procedure 

## Procedure
1. **Understand the Algorithm**  
   - Linear Search: Check each element one by one.  
   - Binary Search: Divide the sorted array into halves and compare with the target key.

2. **Prepare the Environment**  
   - Open an IDE or online compiler.  
   - Create a new file for your program.

3. **Input the Data**  
   - Take the number of elements in the array from the user.  
   - Input the array elements.  
   - For Binary Search, ensure the array is sorted.

4. **Implement the Algorithm**  
   - **Linear Search**:  
     1. Start from the first element.  
     2. Compare each element with the target key.  
     3. If found, display its position.  
     4. If not, continue to the next element until the end.  
   - **Binary Search**:  
     1. Find the middle element of the array.  
     2. Compare it with the target key.  
     3. If matched, return the position.  
     4. If the key is smaller, search the left subarray; if larger, search the right subarray.  
     5. Repeat until the key is found or the subarray size is zero.

5. **Display the Result**  
   - Print the index or position of the found element.  
   - If not found, display a "Not Found" message.

6. **Test the Program**  
   - Test with multiple cases: key at the beginning, middle, end, or not present.  
   - Verify correctness.

7. **Analyze Complexity (Optional)**  
   - Linear Search: Best case O(1), Worst case O(n).  
   - Binary Search: Best case O(1), Worst case O(log n).



---

## ✅ Conclusion  
In this experiment, we learned how **Linear Search** and **Binary Search** work to find an element in an array.  
Linear Search is easy but slow for large data, while Binary Search is faster but requires sorted input.  
This experiment helped us understand the importance of choosing the right searching method based on data and application type.
