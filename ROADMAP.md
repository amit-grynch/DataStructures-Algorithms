# DSA Roadmap: Study in This Order

Follow the steps from top to bottom. Each step uses what you learned in the steps before it, so don't skip ahead.
Every topic is tagged **[DS]** (Data Structure) or **[Algo]** (Algorithm), and marked **Must-do** or **Later** (learn after you finish the must-do path).

For each step: understand the concept → implement it yourself → solve 10 to 20 problems (easy first, then medium).

---

## Stage 1: Foundations

**Step 1. Programming language basics**
Pick one language (C++, Java or Python) and get comfortable with loops, functions, arrays, strings and classes.

**Step 2. Time and space complexity (Big-O)** · Must-do
O(1), O(log n), O(n), O(n log n), O(n²), O(2ⁿ). Count loops and estimate how fast a solution is. Also learn best/average/worst case and the space used by recursion (call stack). You'll use this in every step that follows.

**Step 3. Basic math for DSA** · Must-do
Modulo, GCD/LCM, prime check, Sieve of Eratosthenes, fast power.

**Step 4. Arrays [DS]** · Must-do
Traversal, insert/delete, reverse, rotate, find max/min. 2D arrays (matrices): spiral traversal, rotate matrix, set matrix zeroes.
Classic array algorithms: **Kadane's algorithm** (maximum subarray sum), **Dutch National Flag** (sort 0s, 1s and 2s), **Moore's Voting** (majority element).

**Step 5. Linear Search and Binary Search [Algo]** · Must-do
Binary search on sorted arrays, first/last occurrence, search in a rotated array, and later "binary search on the answer".

**Step 6. Basic Sorting [Algo]** · Must-do
Bubble, Selection and Insertion sort. Understand how they work and why they are O(n²). Also learn **Counting Sort** (a non-comparison sort) and what a **stable** sort means.

**Step 7. Strings [DS]** · Must-do
Character manipulation, palindromes, anagrams, frequency counting, reverse words.

---

## Stage 2: Core problem-solving techniques

**Step 8. Hashing: HashMap and HashSet [DS]** · Must-do
Frequency counting, O(1) lookups, two-sum style problems, map vs set.

**Step 9. Prefix Sum [Algo]** · Must-do
Range sum queries, subarray sum equals K.

**Step 10. Two Pointers [Algo]** · Must-do
Pair sum in a sorted array, remove duplicates, container with most water, 3-sum.

**Step 11. Sliding Window [Algo]** · Must-do
Fixed size and variable size windows, longest substring without repeating characters, minimum window substring.

---

## Stage 3: Recursion mindset (the most important stage)

**Step 12. Recursion [Algo]** · Must-do
Base case, call stack, recursion tree. Print subsets, permutations, power set.
Take your time here. Trees, graphs and DP all depend on it.

**Step 13. Divide and Conquer [Algo]** · Must-do
The idea: split the problem into smaller parts, solve each part recursively, then combine the results.
Learn it through **Merge Sort** and **Quick Sort** (implement both), then count inversions, fast power (x^n in O(log n)), and maximum subarray using divide and conquer. Binary search is also a divide and conquer algorithm. Understand O(n log n), and how to find the time complexity of recursive code using recurrence relations.

**Step 14. Backtracking [Algo]** · Must-do
Combination sum, N-Queens, Sudoku solver, word search, rat in a maze.

---

## Stage 4: Linear data structures

**Step 15. Linked List [DS]** · Must-do
Singly, doubly, circular. Reverse a list, merge two sorted lists, remove the Nth node from the end.
**Fast and slow pointers**: find the middle, detect a cycle and find where it starts, check if a list is a palindrome.

**Step 16. Stack [DS]** · Must-do
Implement with array and linked list. Balanced parentheses, min stack, infix to postfix conversion and evaluation, monotonic stack (next greater element, largest rectangle in histogram).

**Step 17. Queue and Deque [DS]** · Must-do
Queue, circular queue, deque, implement a queue using stacks (and a stack using queues), sliding window maximum (monotonic deque).

---

## Stage 5: Trees

**Step 18. Binary Tree [DS] + Tree Traversals [Algo]** · Must-do
Preorder, inorder, postorder (recursive and iterative), level order (BFS). Height, diameter, balanced tree check, views, lowest common ancestor, build a tree from inorder + preorder traversals.

**Step 19. Binary Search Tree (BST) [DS]** · Must-do
Search, insert, delete, validate a BST, kth smallest, floor and ceil.

**Step 20. Heap / Priority Queue [DS]** · Must-do
Implement a min heap and max heap from scratch, heapify, heap sort, top-K elements, merge K sorted lists, median of a stream.

---

## Stage 6: Greedy

**Step 21. Greedy Algorithms [Algo]** · Must-do
Activity selection, merge intervals, jump game, fractional knapsack, minimum platforms.

---

## Stage 7: Graphs

**Step 22. Graph basics [DS]** · Must-do
Adjacency list and matrix, directed/undirected, weighted/unweighted.

**Step 23. BFS and DFS [Algo]** · Must-do
Connected components, number of islands, flood fill, multi-source BFS (rotting oranges), cycle detection in undirected and directed graphs, bipartite check.

**Step 24. Topological Sort [Algo]** · Must-do
Kahn's algorithm (BFS) and DFS-based. Course schedule problems.

**Step 25. Shortest Path [Algo]** · Must-do
BFS for unweighted graphs, Dijkstra, then Bellman-Ford and Floyd-Warshall (know when to use each).

**Step 26. Disjoint Set Union / Union-Find [DS]** · Must-do
Union by rank, path compression, cycle detection, number of provinces.

**Step 27. Minimum Spanning Tree [Algo]** · Must-do
Kruskal (uses DSU) and Prim (uses heap).

---

## Stage 8: Dynamic Programming

**Step 28. Dynamic Programming [Algo]** · Must-do
Learn in this order:
1. Recursion → Memoization (top-down) → Tabulation (bottom-up) → Space optimization
2. 1D DP: Fibonacci, climbing stairs, house robber
3. Grid DP: unique paths, minimum path sum
4. Knapsack family: 0/1 knapsack, subset sum, coin change, unbounded knapsack
5. Subsequence and string DP: LCS, longest increasing subsequence, edit distance
6. Partition / interval DP: matrix chain multiplication, palindrome partitioning

---

## Stage 9: Finishing topics

**Step 29. Bit Manipulation [Algo]** · Must-do
AND, OR, XOR, shifts. Check/set/clear a bit, count set bits, single number, subsets using bitmask.

**Step 30. Trie [DS]** · Must-do
Insert, search, prefix search, word dictionary.

---

## Stage 10: Advanced (Later, once everything above feels comfortable)

**Step 31. Segment Tree and Fenwick Tree [DS]** · Later
Range sum/min queries with updates.

**Step 32. String algorithms [Algo]** · Later
KMP, Rabin-Karp, Z-algorithm.

**Step 33. Advanced graphs [Algo]** · Later
Strongly connected components (Kosaraju/Tarjan), bridges and articulation points.

**Step 34. Advanced DP [Algo]** · Later
DP on trees, DP with bitmasks, DP on stocks.

**Step 35. Design problems [DS]** · Later
LRU cache, LFU cache, design a HashMap.

---

## Quick reference: the same topics split by type

**Data Structures, in study order:** Arrays → Strings → HashMap/HashSet → Linked List → Stack → Queue/Deque → Binary Tree → BST → Heap → Graph → Union-Find → Trie → Segment/Fenwick Tree

**Algorithms, in study order:** Big-O → Linear/Binary Search → Basic Sorting → Kadane's Algorithm → Prefix Sum → Two Pointers (incl. fast & slow) → Sliding Window → Recursion → Divide and Conquer (Merge/Quick Sort) → Backtracking → Tree Traversals → Greedy → BFS/DFS → Topological Sort → Shortest Path → MST → Dynamic Programming → Bit Manipulation → String Algorithms

---

## Mentor tips

- Focus on **patterns**, not problem count. Ask "which technique does this use?" for every problem.
- **Dry run on paper** before coding, and state time and space complexity after coding.
- **Re-solve** problems you got wrong after 3 days and again after 2 weeks.
- Good practice sources: LeetCode (filter by topic tag, Easy → Medium), NeetCode 150, Striver's A2Z DSA sheet, GeeksforGeeks for theory.
