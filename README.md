~~ 🚀 Data Structures & Algorithms Showcase: 
Daily tracking of DSA problems, C++ implementation, and core concepts.

📌 Day 7: 1D Array Basics, Traversals & Comparison Techniques-
~~ 🧠 Concepts Used:
1. **Array Size Computation:** Calculating element count dynamically using `sizeof(arr) / sizeof(arr[0])`.
2. **Min/Max Index Tracking:** Storing element indices instead of values to perform an in-place swap using temporary variables.
3. **Frequency Calculation via Brute-Force:** Counting element occurrences using nested loops to isolate unique elements (frequency = 1).
4. **Intersection of Two Sets:** Comparing two independent arrays via nested linear search to find matching elements.

~~ 🛠️ Skills Learnt:
* Iterating over contiguous memory blocks in linear time (N).
* Performing in-place swaps on array elements using index manipulation.
* Comparing multi-array data structures to locate common elements.

~~ 💡 Key Takeaways:
* **Tracking Indices vs Values:** When tasked with modifying an array (like swapping max and min), track the indices (`min_idx`, `max_idx`) rather than just the minimum and maximum values.
* **Nested Array Searching:** Comparing two arrays of sizes $N$ and $M$ using nested loops operates in $O(N \times M)$ time complexity, serving as a baseline for future optimization using hash maps or two pointers.

