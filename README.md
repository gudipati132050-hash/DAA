# DAA-PRACTICALS
      Pratical-01
  Summary: 

In this practical, different sorting algorithms—Bubble Sort, Selection Sort, Merge Sort, Quick Sort, and Insertion Sort—were implemented using Python. The algorithms were tested with user-provided input, and the sorted output and execution time were observed. Their time and space complexities were also studied. The practical helped in understanding the working process, efficiency, and differences between simple sorting algorithms and divide-and-conquer sorting algorithms.

Conclusion:

The practical was successfully completed, and all the sorting algorithms produced the correct sorted output. Bubble Sort, Selection Sort, and Insertion Sort are simple and suitable for small datasets, but they generally require more time for large datasets. Merge Sort and Quick Sort are more efficient for larger datasets because they use the divide-and-conquer approach. Thus, the practical provided a clear understanding of sorting techniques and the importance of time and space complexity in selecting an appropriate sorting algorithm.


     practical-2
Summary:
     
The programs implement Linear Search and Binary Search to find a target number in a list. Both programs take numbers and a target value as input, display whether the target is found, return its index, and measure the execution time. The Linear Search program checks each element one by one and has O(1) best-case and O(n) average/worst-case time complexity. � The Binary Search program repeatedly checks the middle element and reduces the search range; it works by comparing the target with the middle value. �
linearsearch.py
binarysearch.py

Conclusion:

Linear Search is simple and can be used for any list, but it may take more time for large datasets. Binary Search is generally faster because it reduces the search range in every step, but it requires the list to be sorted. Therefore, Linear Search is suitable for small or unsorted lists, while Binary Search is more efficient for large sorted lists.

       practical-3
Summary
The program implements Heap Sort using a Max Heap. It first builds a max heap from the input array using the heapify() function. The largest element is then repeatedly moved to the end of the array, and the remaining elements are heapified again. The program also measures the execution time and displays the sorted list. �
maxheap.py

Conclusion
The Heap Sort algorithm successfully sorts the given list of integers in ascending order. The program demonstrates the use of a Max Heap and reports O(n log n) time complexity for the best, average, and worst cases. �

       PRACTICAL-4
Summary
The factorial of a number was implemented using both iterative and recursive methods. The iterative method calculates the factorial using a for loop, while the recursive method calculates it by repeatedly calling the same function with a reduced value. Both methods have O(n) time complexity. The iterative method uses O(1) space, whereas the recursive method uses O(n) space because of recursive function calls. The execution time of both methods was also measured and compared. �

Conclusion
Thus, the factorial of a given number was successfully calculated using both iterative and recursive methods. Both methods produce the same result, but the iterative method is more space-efficient, while the recursive method is simpler and demonstrates the concept of recursion. Therefore, the iterative approach is generally preferable when memory efficiency is important.

     PRACTICAL-5
Summary
The Knapsack Problem was implemented using Dynamic Programming to find the maximum value within a given weight capacity. DP stores solutions to smaller subproblems and uses them to build the final optimal solution.

Conclusion
Dynamic Programming provides an efficient and optimal solution to the Knapsack Problem, reducing repeated calculations and improving performance compared with the recursive approach.


                              practical-7
summary Greedy Approach: Fails when larger coin choices bypass optimal smaller combinations (e.g., target 6 with coins [1, 3, 4]).Recursion & Memoization: Top-down technique that caches repeated subproblem values to avoid redundant tree branches.Tabulation (Bottom-Up DP): Iteratively builds a 1D array where each index tracks the optimal result for sub-amounts up to the target.Complexity: Achieves an efficient (O(N \times C)) time complexity and O(N) space complexity (where N is the target amount and C is coin types) conclusion Optimal Substructure: The optimal solution for a target amount directly relies on the optimal solutions of smaller remaining sub-amounts.Core Paradigm: It stands as a benchmark model for the unbounded knapsack problem where items (coins) are indefinitely reusable.Efficiency: Tabulation eliminates recursion stack overhead, providing optimal scalability for larger target inputs.


             practical_8

Summary
Breadth-First Search (BFS) and Depth-First Search (DFS) are fundamental graph traversal algorithms used to visit all the vertices of a graph.

BFS explores the graph level by level. It uses a queue (FIFO) and is useful for finding the shortest path in an unweighted graph.

DFS explores as deep as possible before backtracking. It uses a stack (LIFO) or recursion and is useful for tasks such as cycle detection, connected components, and topological sorting.

For a graph with V vertices and E edges, both BFS and DFS generally have a time complexity of O(V + E).

The choice between BFS and DFS depends on the problem requirements and the structure of the graph.

Conclusion
BFS and DFS are efficient and widely used techniques for traversing graphs. BFS is preferable when level-wise exploration or the shortest path in an unweighted graph is required, while DFS is suitable when deep exploration and backtracking are needed. Understanding both algorithms provides a strong foundation for solving graph-related problems in computer science.



