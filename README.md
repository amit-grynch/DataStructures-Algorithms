# DataStructures-Algorithms

My Java practice code for data structures, algorithms and LeetCode problems.

## Modules

- `DataStructureExplorer`: data structure practice and coding patterns (two pointers, sliding window).
- `AlgorithmsExplorer`: algorithm practice.
- `LeetCodeJourney`: LeetCode solutions, grouped by difficulty and topic.

## Study roadmap

I follow the study order in **[ROADMAP.md](ROADMAP.md)**: 35 steps across 10 stages, from Big-O and arrays through recursion, trees, graphs and dynamic programming, with the advanced topics saved for last.

| Stage | Topics | Steps |
|---|---|---|
| 1. Foundations | Big-O, math, arrays, searching, basic sorting, strings | 1 to 7 |
| 2. Core techniques | Hashing, prefix sum, two pointers, sliding window | 8 to 11 |
| 3. Recursion mindset | Recursion, divide and conquer, backtracking | 12 to 14 |
| 4. Linear data structures | Linked list, stack, queue and deque | 15 to 17 |
| 5. Trees | Binary tree, BST, heap | 18 to 20 |
| 6. Greedy | Greedy algorithms | 21 |
| 7. Graphs | BFS/DFS, topological sort, shortest path, DSU, MST | 22 to 27 |
| 8. Dynamic Programming | 1D, grid, knapsack, string and interval DP | 28 |
| 9. Finishing topics | Bit manipulation, trie | 29 to 30 |
| 10. Advanced (later) | Segment/Fenwick tree, string algorithms, advanced graphs and DP, design | 31 to 35 |

### Proposed layout for new code

Existing code stays where it is. New work can go into one package per roadmap stage, so the folders read in the same order as the roadmap (package names can't start with a digit, hence the `stage` prefix):

```
Roadmap/src/com/roadmap/
├── stage01_foundations/        # complexity, math, arrays, search, sorting, strings
├── stage02_techniques/         # hashing, prefixsum, twopointers, slidingwindow
├── stage03_recursion/          # recursion, divideconquer, backtracking
├── stage04_linear/             # linkedlist, stack, queue
├── stage05_trees/              # binarytree, bst, heap
├── stage06_greedy/
├── stage07_graphs/             # bfsdfs, toposort, shortestpath, dsu, mst
├── stage08_dp/
├── stage09_finishing/          # bits, trie
└── stage10_advanced/           # segmenttree, stringalgos, advgraphs, advdp, design
```

Each stage package gets one sub-package per step (for example `stage02_techniques.slidingwindow`), holding the from-scratch implementation plus the practice problems for that step.
