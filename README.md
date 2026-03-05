# DSA 232 — Master Checklist

> 22 core topics + advanced section · 123+ patterns · 232 problems
> Track your progress by checking boxes and adding notes directly on GitHub.

**How to use:** Fork this repo, then edit this file on GitHub — check the boxes `[x]` and add your notes inline.

---

## Progress

| Metric | Count |
|--------|-------|
| Total | 232 |
| Easy | 46 |
| Medium | 148 |
| Hard | 38 |

---

## 1. Arrays & Strings
> Hashing · Prefix Sum · In-place

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 1 | - [X] [Two Sum](https://leetcode.com/problems/two-sum/) | Easy | HashMap | | 
| 2 | - [X] [Best Time to Buy & Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | Easy | Greedy / Single pass | |
| 3 | - [X] [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) | Easy | HashSet | |
| 4 | - [X] [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | Medium | Prefix & Suffix product | |
| 5 | - [X] [Maximum Subarray (Kadane's)](https://leetcode.com/problems/maximum-subarray/) | Medium | Kadane's algorithm | |
| 6 | - [ ] [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Medium | DP / track min & max | |
| 7 | - [ ] [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Medium | Binary search | |
| 8 | - [ ] [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) | Medium | Binary search | |
| 9 | - [ ] [3Sum](https://leetcode.com/problems/3sum/) | Medium | Two pointers | |
| 10 | - [ ] [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Medium | Two pointers | |
| 11 | - [ ] [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | Medium | HashSet O(n) | |
| 12 | - [ ] [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Hard | Two pointers / Monotonic stack | |

---

## 2. Strings
> Sliding Window · HashMap · Two Pointers

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 13 | - [ ] [Valid Anagram](https://leetcode.com/problems/valid-anagram/) | Easy | Frequency count | |
| 14 | - [ ] [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) | Easy | Two pointers | |
| 15 | - [ ] [Longest Substring Without Repeating Chars](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Medium | Sliding window + Set | |
| 16 | - [ ] [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/) | Medium | Sliding window | |
| 17 | - [ ] [Permutation in String](https://leetcode.com/problems/permutation-in-string/) | Medium | Fixed sliding window | |
| 18 | - [ ] [Group Anagrams](https://leetcode.com/problems/group-anagrams/) | Medium | Sorted key / freq tuple | |
| 19 | - [ ] [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard | Sliding window + two maps | |
| 20 | - [ ] [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Medium | Expand around center | |
| 21 | - [ ] [Encode and Decode Strings](https://leetcode.com/problems/encode-and-decode-strings/) | Medium | Length-prefix encoding | |
| 22 | - [ ] [Palindromic Substrings](https://leetcode.com/problems/palindromic-substrings/) | Medium | Expand around center | |

---

## 3. Two Pointers
> Opposite ends · Fast/Slow · Three pointers · Partition · Merge sorted · Prefix/Suffix

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 23 | - [ ] [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy | Slow/Fast pointer | |
| 24 | - [ ] [Move Zeroes](https://leetcode.com/problems/move-zeroes/) | Easy | Partition — two pointers in-place | |
| 25 | - [ ] [Squares of Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) | Easy | Opposite ends pointers | |
| 177 | - [ ] [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy | Merge two sorted — reverse fill | |
| 26 | - [ ] [4Sum](https://leetcode.com/problems/4sum/) | Medium | Generalized kSum — opposite ends | |
| 27 | - [ ] [Sort Colors (Dutch National Flag)](https://leetcode.com/problems/sort-colors/) | Medium | Three pointers — 3-way partition | |

---

## 4. Sliding Window
> Fixed window · Variable window · Max freq trick · Exactly K trick

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 28 | - [ ] [Maximum Average Subarray I](https://leetcode.com/problems/maximum-average-subarray-i/) | Easy | Fixed window — simple sum/avg | |
| 29 | - [ ] [Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/) | Medium | Variable — minimize length (while valid) | |
| 30 | - [ ] [Fruits Into Baskets](https://leetcode.com/problems/fruit-into-baskets/) | Medium | Variable — maximize length (at most K distinct) | |
| 31 | - [ ] [Max Consecutive Ones III](https://leetcode.com/problems/max-consecutive-ones-iii/) | Medium | Max freq trick (window - max_freq > k) | |
| 32 | - [ ] [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard | Fixed window — monotonic deque | |
| 176 | - [ ] [Count Number of Nice Subarrays](https://leetcode.com/problems/count-number-of-nice-subarrays/) | Medium | Exactly K trick — atMost(K) - atMost(K-1) | |

---

## 5. Binary Search
> Search space reduction · Search on answer

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 33 | - [ ] [Binary Search](https://leetcode.com/problems/binary-search/) | Easy | Classic template | |
| 34 | - [ ] [First Bad Version](https://leetcode.com/problems/first-bad-version/) | Easy | Left boundary search | |
| 35 | - [ ] [Find First and Last Position](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) | Medium | Left & right boundary | |
| 36 | - [ ] [Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/) | Medium | Flatten index | |
| 37 | - [ ] [Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/) | Medium | Search on answer | |
| 38 | - [ ] [Find Minimum in Rotated Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Medium | Pivot binary search | |
| 39 | - [ ] [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard | Partition binary search | |

---

## 6. Linked Lists
> Fast/Slow pointer · Dummy node · In-place reversal

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 40 | - [ ] [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy | Iterative / Recursive | |
| 41 | - [ ] [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) | Easy | Dummy node merge | |
| 42 | - [ ] [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) | Easy | Floyd's cycle detection | |
| 43 | - [ ] [Find Middle of Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) | Easy | Fast/Slow pointer | |
| 44 | - [ ] [Remove Nth Node From End](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) | Medium | Two-pass / Gap pointer | |
| 45 | - [ ] [Reorder List](https://leetcode.com/problems/reorder-list/) | Medium | Middle + Reverse + Merge | |
| 46 | - [ ] [LRU Cache](https://leetcode.com/problems/lru-cache/) | Medium | DoublyLL + HashMap | |
| 47 | - [ ] [Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard | Min-Heap / Divide & Conquer | |
| 48 | - [ ] [Reverse Nodes in K-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/) | Hard | In-place reversal | |

---

## 7. Stacks & Queues
> Valid parens · Monotonic incr/decr · Histogram · Expression eval · Collision simulation

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 49 | - [ ] [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | Easy | Stack matching — valid brackets | |
| 50 | - [ ] [Min Stack](https://leetcode.com/problems/min-stack/) | Medium | Auxiliary stack | |
| 51 | - [ ] [Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/) | Easy | Two stacks | |
| 178 | - [ ] [Online Stock Span](https://leetcode.com/problems/online-stock-span/) | Medium | Monotonic increasing stack — prev greater | |
| 52 | - [ ] [Daily Temperatures](https://leetcode.com/problems/daily-temperatures/) | Medium | Monotonic decreasing stack — next greater | |
| 179 | - [ ] [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/) | Medium | Expression evaluation — postfix stack | |
| 180 | - [ ] [Asteroid Collision](https://leetcode.com/problems/asteroid-collision/) | Medium | Collision simulation with stack | |
| 53 | - [ ] [Car Fleet](https://leetcode.com/problems/car-fleet/) | Medium | Monotonic stack | |
| 54 | - [ ] [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard | Histogram area — monotonic stack | |

---

## 8. Trees
> DFS traversals · Level BFS · Path sum · LCA · Serialize · Tree DP · BST

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 55 | - [ ] [Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) | Easy | Inorder / Preorder / Postorder DFS | |
| 56 | - [ ] [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | Easy | DFS postorder | |
| 57 | - [ ] [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | Easy | Tree DP — DFS with height | |
| 58 | - [ ] [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | Easy | Height + early exit | |
| 59 | - [ ] [Same Tree](https://leetcode.com/problems/same-tree/) | Easy | Simultaneous DFS | |
| 60 | - [ ] [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/) | Easy | Swap children DFS | |
| 61 | - [ ] [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | Easy | Same Tree nested | |
| 62 | - [ ] [Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | Medium | Level order BFS | |
| 63 | - [ ] [Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/) | Medium | BFS last of each level | |
| 181 | - [ ] [Path Sum II](https://leetcode.com/problems/path-sum-ii/) | Medium | Path sum — root to leaf DFS | |
| 64 | - [ ] [Validate BST](https://leetcode.com/problems/validate-binary-search-tree/) | Medium | BST — min/max bounds DFS | |
| 65 | - [ ] [Kth Smallest in BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | Medium | BST — in-order traversal | |
| 66 | - [ ] [Lowest Common Ancestor](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) | Medium | LCA — recursive | |
| 67 | - [ ] [Count Good Nodes](https://leetcode.com/problems/count-good-nodes-in-binary-tree/) | Medium | DFS max tracking | |
| 68 | - [ ] [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Hard | Tree DP — DFS with global max | |
| 69 | - [ ] [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Hard | Serialize / Deserialize — BFS encoding | |

---

## 9. Graphs
> DFS · BFS · Topo sort · Union-Find · Dijkstra · Bellman-Ford · Floyd-Warshall · Bipartite

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 70 | - [ ] [Number of Islands](https://leetcode.com/problems/number-of-islands/) | Medium | DFS — connected components / flood fill | |
| 71 | - [ ] [Clone Graph](https://leetcode.com/problems/clone-graph/) | Medium | BFS + visited map | |
| 72 | - [ ] [Max Area of Island](https://leetcode.com/problems/max-area-of-island/) | Medium | DFS count | |
| 73 | - [ ] [Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/) | Medium | BFS — multi-source | |
| 74 | - [ ] [Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) | Medium | DFS — boundary flood fill | |
| 75 | - [ ] [Rotting Oranges](https://leetcode.com/problems/rotting-oranges/) | Medium | BFS — shortest path unweighted | |
| 76 | - [ ] [Course Schedule I](https://leetcode.com/problems/course-schedule/) | Medium | Topological sort — cycle detection DFS | |
| 77 | - [ ] [Course Schedule II](https://leetcode.com/problems/course-schedule-ii/) | Medium | Topological sort — Kahn's BFS | |
| 78 | - [ ] [Number of Connected Components](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) | Medium | Union-Find / DFS | |
| 79 | - [ ] [Redundant Connection](https://leetcode.com/problems/redundant-connection/) | Medium | Union-Find — cycle detection | |
| 80 | - [ ] [Word Ladder](https://leetcode.com/problems/word-ladder/) | Hard | BFS — shortest path unweighted | |
| 81 | - [ ] [Network Delay Time (Dijkstra)](https://leetcode.com/problems/network-delay-time/) | Medium | Dijkstra — shortest path weighted | |
| 82 | - [ ] [Min Cost to Connect All Points (MST)](https://leetcode.com/problems/min-cost-to-connect-all-points/) | Medium | Prim's / Kruskal's MST | |
| 83 | - [ ] [Accounts Merge](https://leetcode.com/problems/accounts-merge/) | Medium | Union-Find — disjoint sets | |
| 182 | - [ ] [Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/) | Medium | Bellman-Ford — negative/limited weights | |
| 183 | - [ ] [Find the City With Smallest Number of Neighbors](https://leetcode.com/problems/find-the-city-with-the-smallest-number-of-neighbors-at-a-threshold-distance/) | Medium | Floyd-Warshall — all pairs shortest path | |
| 184 | - [ ] [Is Graph Bipartite?](https://leetcode.com/problems/is-graph-bipartite/) | Medium | Bipartite check — 2-coloring BFS/DFS | |

---

## 10. Backtracking
> Subsets · Permutations · Combinations · Grid/maze · Constraint satisfaction · Palindrome partitioning

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 84 | - [ ] [Subsets](https://leetcode.com/problems/subsets/) | Medium | Subsets — include/exclude DFS | |
| 85 | - [ ] [Subsets II (with duplicates)](https://leetcode.com/problems/subsets-ii/) | Medium | Subsets — sort + skip duplicates | |
| 86 | - [ ] [Permutations](https://leetcode.com/problems/permutations/) | Medium | Permutations — swap / visited array | |
| 87 | - [ ] [Combination Sum](https://leetcode.com/problems/combination-sum/) | Medium | Combinations — DFS with reuse | |
| 88 | - [ ] [Combination Sum II](https://leetcode.com/problems/combination-sum-ii/) | Medium | Combinations — DFS, skip duplicates | |
| 210 | - [ ] [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | Medium | Combinations — phone digit mapping | |
| 89 | - [ ] [Word Search](https://leetcode.com/problems/word-search/) | Medium | Grid / maze — DFS on grid | |
| 90 | - [ ] [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | Medium | Palindrome partitioning — backtrack + DP check | |
| 91 | - [ ] [N-Queens](https://leetcode.com/problems/n-queens/) | Hard | Constraint satisfaction — row-by-row | |
| 92 | - [ ] [Sudoku Solver](https://leetcode.com/problems/sudoku-solver/) | Hard | Constraint satisfaction — backtrack | |

---

## 11. Heaps / Priority Queue
> Top K · K-way merge · Two heaps · Interval scheduling · Dijkstra with heap

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 93 | - [ ] [Kth Largest Element in Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium | Top K — min-heap of size K | |
| 94 | - [ ] [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Medium | Top K — heap + bucket sort | |
| 95 | - [ ] [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) | Medium | Top K — max-heap of size K | |
| 96 | - [ ] [Task Scheduler](https://leetcode.com/problems/task-scheduler/) | Medium | Interval scheduling — greedy + max-heap | |
| 97 | - [ ] [Reorganize String](https://leetcode.com/problems/reorganize-string/) | Medium | Interval scheduling — max-heap greedy | |
| 98 | - [ ] [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Hard | Two heaps (max+min) | |
| 99 | - [ ] [Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard | K-way merge — min-heap | |

---

## 12. Dynamic Programming 1D
> 1D DP · 0/1 Knapsack · Unbounded Knapsack · LIS · Digit DP · Bitmask DP

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 100 | - [ ] [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy | 1D DP — Fibonacci / tree recursion | |
| 101 | - [ ] [House Robber](https://leetcode.com/problems/house-robber/) | Medium | 1D DP — linear state transition | |
| 102 | - [ ] [House Robber II (Circular)](https://leetcode.com/problems/house-robber-ii/) | Medium | 1D DP — run twice, exclude ends | |
| 103 | - [ ] [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Medium | LIS — DP / binary search O(n log n) | |
| 104 | - [ ] [Word Break](https://leetcode.com/problems/word-break/) | Medium | 1D DP with dict lookup | |
| 105 | - [ ] [Coin Change](https://leetcode.com/problems/coin-change/) | Medium | Unbounded knapsack | |
| 106 | - [ ] [Coin Change II (combinations)](https://leetcode.com/problems/coin-change-ii/) | Medium | Unbounded knapsack — count ways | |
| 107 | - [ ] [Decode Ways](https://leetcode.com/problems/decode-ways/) | Medium | String DP | |
| 108 | - [ ] [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Medium | 1D DP — track min & max | |
| 109 | - [ ] [Jump Game](https://leetcode.com/problems/jump-game/) | Medium | Greedy / DP — jump game | |
| 110 | - [ ] [Jump Game II (min jumps)](https://leetcode.com/problems/jump-game-ii/) | Medium | Greedy BFS levels — min jumps | |
| 111 | - [ ] [Partition Equal Subset Sum (0/1 Knapsack)](https://leetcode.com/problems/partition-equal-subset-sum/) | Medium | 0/1 Knapsack — subset sum | |
| 205 | - [ ] [House Robber III](https://leetcode.com/problems/house-robber-iii/) | Medium | Tree DP — house robber on tree | |
| 188 | - [ ] [Count Numbers with Unique Digits](https://leetcode.com/problems/count-numbers-with-unique-digits/) | Medium | Digit DP — count numbers with property | |
| 189 | - [ ] [Partition to K Equal Sum Subsets](https://leetcode.com/problems/partition-to-k-equal-sum-subsets/) | Medium | Bitmask DP — travelling subset problem | |

---

## 13. Dynamic Programming 2D
> Grid DP · LCS family · Interval DP · Tree DP

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 112 | - [ ] [Unique Paths](https://leetcode.com/problems/unique-paths/) | Medium | 2D DP grid — count paths | |
| 190 | - [ ] [Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) | Medium | 2D DP grid — min path cost | |
| 113 | - [ ] [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) | Medium | LCS family — classic LCS | |
| 114 | - [ ] [Edit Distance](https://leetcode.com/problems/edit-distance/) | Medium | LCS family — edit distance variant | |
| 115 | - [ ] [Maximal Square](https://leetcode.com/problems/maximal-square/) | Medium | 2D DP — min(top,left,diag) | |
| 116 | - [ ] [Interleaving String](https://leetcode.com/problems/interleaving-string/) | Medium | 2D DP — string interleaving | |
| 117 | - [ ] [Burst Balloons](https://leetcode.com/problems/burst-balloons/) | Hard | Interval DP — matrix chain style | |
| 118 | - [ ] [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | Hard | 2D DP with wildcards | |

---

## 14. Greedy
> Interval scheduling · Jump game · Activity selection · Sorted input · Huffman · Monotonic greedy

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 119 | - [ ] [Assign Cookies](https://leetcode.com/problems/assign-cookies/) | Easy | Greedy on sorted input — match greedily | |
| 186 | - [ ] [Last Stone Weight](https://leetcode.com/problems/last-stone-weight/) | Easy | Huffman / greedy tree — min cost merge | |
| 120 | - [ ] [Gas Station](https://leetcode.com/problems/gas-station/) | Medium | Net gain circular — greedy start | |
| 121 | - [ ] [Partition Labels](https://leetcode.com/problems/partition-labels/) | Medium | Last occurrence map | |
| 122 | - [ ] [Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/) | Medium | Interval scheduling — sort by end time | |
| 123 | - [ ] [Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/) | Medium | Activity selection — min-heap / sweep line | |
| 124 | - [ ] [Hand of Straights](https://leetcode.com/problems/hand-of-straights/) | Medium | Greedy + sorted map | |
| 187 | - [ ] [Monotone Increasing Digits](https://leetcode.com/problems/monotone-increasing-digits/) | Medium | Monotonic greedy — remove K digits style | |

---

## 15. Intervals
> Merge · Insert · Non-overlapping · Meeting rooms · Intersection

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 125 | - [ ] [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium | Merge intervals — sort + linear merge | |
| 126 | - [ ] [Insert Interval](https://leetcode.com/problems/insert-interval/) | Medium | Insert interval — 3-phase insertion | |
| 191 | - [ ] [Interval List Intersections](https://leetcode.com/problems/interval-list-intersections/) | Medium | Interval intersection — two pointer merge | |
| 192 | - [ ] [My Calendar I](https://leetcode.com/problems/my-calendar-i/) | Medium | Meeting rooms — overlap detection / booking | |
| 127 | - [ ] [Minimum Interval to Include Each Query](https://leetcode.com/problems/minimum-interval-to-include-each-query/) | Hard | Sort + Min-heap + offline queries | |

---

## 16. Tries
> Prefix tree · Wildcard DFS · Word search / boggle · XOR trie

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 128 | - [ ] [Implement Trie](https://leetcode.com/problems/implement-trie-prefix-tree/) | Medium | Insert / search / startsWith — basic trie | |
| 129 | - [ ] [Design Add & Search Words](https://leetcode.com/problems/design-add-and-search-words-data-structure/) | Medium | Trie + wildcard DFS | |
| 130 | - [ ] [Word Search II](https://leetcode.com/problems/word-search-ii/) | Hard | Word search / boggle — trie + grid DFS | |
| 185 | - [ ] [Maximum XOR of Two Numbers in an Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/) | Medium | XOR trie — maximum XOR of two numbers | |

---

## 17. Bit Manipulation
> Basic bits · XOR tricks · Bit masking · Bit DP · Bit arithmetic · Two's complement

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 131 | - [ ] [Single Number](https://leetcode.com/problems/single-number/) | Easy | XOR tricks — cancellation | |
| 132 | - [ ] [Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/) | Easy | Basic bits — n & (n-1) trick | |
| 133 | - [ ] [Counting Bits](https://leetcode.com/problems/counting-bits/) | Easy | Bit DP — DP with i>>1 | |
| 134 | - [ ] [Reverse Bits](https://leetcode.com/problems/reverse-bits/) | Easy | Bit arithmetic — bit shifting | |
| 135 | - [ ] [Power of Two](https://leetcode.com/problems/power-of-two/) | Easy | Basic bits — n & (n-1) == 0 | |
| 136 | - [ ] [Missing Number](https://leetcode.com/problems/missing-number/) | Easy | XOR tricks — find missing via XOR | |
| 194 | - [ ] [Single Number III](https://leetcode.com/problems/single-number-iii/) | Medium | Bit masking — XOR + mask to split groups | |
| 137 | - [ ] [Sum of Two Integers (no +)](https://leetcode.com/problems/sum-of-two-integers/) | Medium | Bit arithmetic — XOR + carry | |
| 195 | - [ ] [Divide Two Integers](https://leetcode.com/problems/divide-two-integers/) | Medium | Two's complement — bit shift division | |

---

## 18. Math & Number Theory
> Prime sieve · GCD/LCM · Modular arithmetic · Combinatorics · Geometry · Digit problems

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 138 | - [ ] [Palindrome Number](https://leetcode.com/problems/palindrome-number/) | Easy | Digit problems — reverse half | |
| 139 | - [ ] [Happy Number](https://leetcode.com/problems/happy-number/) | Easy | Digit problems — Floyd's / HashSet | |
| 196 | - [ ] [Greatest Common Divisor of Strings](https://leetcode.com/problems/greatest-common-divisor-of-strings/) | Easy | GCD / LCM — Euclidean algorithm | |
| 197 | - [ ] [Pascal's Triangle](https://leetcode.com/problems/pascals-triangle/) | Easy | Combinatorics — nCr / binomial coefficients | |
| 140 | - [ ] [Pow(x, n) — Fast Exponentiation](https://leetcode.com/problems/powx-n/) | Medium | Modular arithmetic — fast exponentiation | |
| 198 | - [ ] [Super Pow](https://leetcode.com/problems/super-pow/) | Medium | Modular arithmetic — mod inverse / fast exp | |
| 141 | - [ ] [Count Primes (Sieve)](https://leetcode.com/problems/count-primes/) | Medium | Prime sieve — Sieve of Eratosthenes | |
| 142 | - [ ] [Reverse Integer](https://leetcode.com/problems/reverse-integer/) | Medium | Digit problems — overflow handling | |
| 207 | - [ ] [Max Points on a Line](https://leetcode.com/problems/max-points-on-a-line/) | Hard | Geometry basics — GCD slope / collinear | |

---

## 19. Matrix
> DFS on grid · BFS shortest dist · Grid DP · Spiral traversal · In-place marking

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 143 | - [ ] [Rotate Image](https://leetcode.com/problems/rotate-image/) | Medium | In-place transformation — transpose + reflect | |
| 144 | - [ ] [Spiral Matrix](https://leetcode.com/problems/spiral-matrix/) | Medium | Spiral / diagonal traversal — 4-boundary | |
| 145 | - [ ] [Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/) | Medium | In-place marking — first row/col as flag | |
| 146 | - [ ] [Game of Life](https://leetcode.com/problems/game-of-life/) | Medium | In-place state encoding | |
| 193 | - [ ] [01 Matrix](https://leetcode.com/problems/01-matrix/) | Medium | BFS on grid — shortest distance to 0 | |
| 206 | - [ ] [Path With Maximum Gold](https://leetcode.com/problems/path-with-maximum-gold/) | Medium | DP / DFS on grid — max gold collection | |

---

## 20. Design
> Data structure design · O(1) operations

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 147 | - [ ] [Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/) | Medium | HashMap + Array | |
| 148 | - [ ] [Time Based Key-Value Store](https://leetcode.com/problems/time-based-key-value-store/) | Medium | HashMap + Binary search | |
| 149 | - [ ] [Design Twitter (Feed)](https://leetcode.com/problems/design-twitter/) | Medium | Heap + HashMap | |
| 150 | - [ ] [Snapshot Array](https://leetcode.com/problems/snapshot-array/) | Medium | Binary search on versions | |

---

## 21. Prefix Sum
> Range queries · Prefix + Hashmap · 2D prefix · Prefix XOR

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 151 | - [ ] [Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-immutable/) | Easy | Simple prefix sum | |
| 152 | - [ ] [Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) | Easy | Prefix sum equality | |
| 153 | - [ ] [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium | Prefix sum + hashmap | |
| 154 | - [ ] [Continuous Subarray Sum](https://leetcode.com/problems/continuous-subarray-sum/) | Medium | Prefix mod + hashmap | |
| 155 | - [ ] [Number of Submatrices That Sum to Target](https://leetcode.com/problems/number-of-submatrices-that-sum-to-target/) | Hard | 2D prefix sum | |
| 204 | - [ ] [XOR Queries of a Subarray](https://leetcode.com/problems/xor-queries-of-a-subarray/) | Medium | Prefix XOR — subarray XOR queries | |

---

## 22. Hashing
> Frequency count · Two-sum complement · Grouping · Bijection · Sliding window + map · Prefix + map

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 156 | - [ ] [Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings/) | Easy | Bijection — two-way char map | |
| 157 | - [ ] [Word Pattern](https://leetcode.com/problems/word-pattern/) | Easy | Bijection — pattern match check | |
| 199 | - [ ] [4Sum II](https://leetcode.com/problems/4sum-ii/) | Medium | Two-sum complement — hashmap count | |
| 158 | - [ ] [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium | Frequency count — sliding window + freq map | |
| 159 | - [ ] [Subarrays with K Different Integers](https://leetcode.com/problems/subarrays-with-k-different-integers/) | Hard | Sliding window + map — atMost(K) - atMost(K-1) | |

---

## 23. Queue / Deque
> BFS queue · Circular queue · Monotonic deque DP · Priority queue · Queue simulation

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 161 | - [ ] [Number of Recent Calls](https://leetcode.com/problems/number-of-recent-calls/) | Easy | BFS queue — sliding window queue | |
| 160 | - [ ] [Design Circular Queue](https://leetcode.com/problems/design-circular-queue/) | Medium | Circular queue — circular buffer array | |
| 162 | - [ ] [Dota2 Senate](https://leetcode.com/problems/dota2-senate/) | Medium | Queue simulation — greedy rounds | |
| 200 | - [ ] [Jump Game VI](https://leetcode.com/problems/jump-game-vi/) | Medium | Monotonic deque — DP + sliding window max | |

---

## 24. Sorting
> Comparison sorts · Counting/Radix · Sort + two pointer · Custom comparator · Quickselect · Cyclic sort

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 163 | - [ ] [Sort an Array](https://leetcode.com/problems/sort-an-array/) | Medium | Comparison sorts — merge sort / quick sort | |
| 201 | - [ ] [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Easy | Cyclic sort — place each number at correct index | |
| 202 | - [ ] [3Sum Closest](https://leetcode.com/problems/3sum-closest/) | Medium | Sort + two pointer — closest target | |
| 164 | - [ ] [Largest Number](https://leetcode.com/problems/largest-number/) | Medium | Custom comparator — sort by concatenation order | |
| 165 | - [ ] [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/) | Medium | Counting / bucket sort — by frequency | |
| 166 | - [ ] [Find K Closest Elements](https://leetcode.com/problems/find-k-closest-elements/) | Medium | Sort + binary search — K closest | |
| 208 | - [ ] [Kth Largest Element (Quickselect)](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium | Quickselect — O(n) avg partition select | |
| 167 | - [ ] [Maximum Gap](https://leetcode.com/problems/maximum-gap/) | Hard | Bucket / radix sort — non-comparison sort | |

---

## 25. Recursion
> Divide & conquer · Decrease & conquer · Tree recursion · Memoization

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 168 | - [ ] [Fibonacci Number](https://leetcode.com/problems/fibonacci-number/) | Easy | Tree recursion / memoization | |
| 169 | - [ ] [K-th Symbol in Grammar](https://leetcode.com/problems/k-th-symbol-in-grammar/) | Medium | Divide & conquer recursion | |
| 170 | - [ ] [Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/) | Medium | Recursive iterator / stack | |
| 171 | - [ ] [Different Ways to Add Parentheses](https://leetcode.com/problems/different-ways-to-add-parentheses/) | Medium | Divide & conquer + memo | |

---

## 26. Monotonic Stack / Queue
> Next greater element · Next smaller element · Histogram · Circular array · Remove K digits

| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 172 | - [ ] [Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/) | Easy | Next greater element — monotonic decreasing stack | |
| 173 | - [ ] [Next Greater Element II](https://leetcode.com/problems/next-greater-element-ii/) | Medium | Next greater — circular array + stack | |
| 203 | - [ ] [Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) | Medium | Next smaller element — monotonic increasing stack | |
| 174 | - [ ] [Remove K Digits](https://leetcode.com/problems/remove-k-digits/) | Medium | Monotonic greedy — remove K digits | |
| 175 | - [ ] [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard | Largest rectangle — histogram + mono stack | |
| 209 | - [ ] [Shortest Subarray with Sum at Least K](https://leetcode.com/problems/shortest-subarray-with-sum-at-least-k/) | Hard | Sliding window min/max — monotonic deque | |

---

## 27. Advanced
> String matching · Segment Tree / BIT · Advanced Graph · Advanced DP · Advanced Design · Simulation

### String Matching
| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 211 | - [ ] [Find the Index of the First Occurrence in a String](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/) | Easy | String matching — KMP / Rabin-Karp | |
| 212 | - [ ] [Repeated String Match](https://leetcode.com/problems/repeated-string-match/) | Medium | String matching — Rabin-Karp rolling hash | |
| 213 | - [ ] [Shortest Palindrome](https://leetcode.com/problems/shortest-palindrome/) | Hard | String matching — KMP failure function | |

### Segment Tree / BIT (Fenwick)
| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 214 | - [ ] [Range Sum Query - Mutable](https://leetcode.com/problems/range-sum-query-mutable/) | Medium | Segment Tree / BIT — point update, range query | |
| 215 | - [ ] [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard | Segment Tree / BIT — inversion count | |
| 216 | - [ ] [Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) | Hard | Segment Tree / merge sort — range count | |

### Advanced Graph
| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 217 | - [ ] [Critical Connections in a Network](https://leetcode.com/problems/critical-connections-in-a-network/) | Hard | Tarjan's — bridges / articulation points | |
| 218 | - [ ] [Shortest Path Visiting All Nodes](https://leetcode.com/problems/shortest-path-visiting-all-nodes/) | Hard | Bitmask BFS — TSP variant | |
| 219 | - [ ] [Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | Hard | Eulerian path — Hierholzer's algorithm | |
| 220 | - [ ] [Swim in Rising Water](https://leetcode.com/problems/swim-in-rising-water/) | Hard | A* / Dijkstra on grid — min bottleneck path | |

### Advanced DP
| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 221 | - [ ] [Minimum XOR Sum of Two Arrays](https://leetcode.com/problems/minimum-xor-sum-of-two-arrays/) | Hard | Bitmask DP — optimal assignment | |
| 222 | - [ ] [Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) | Hard | LIS 2D — sort + binary search | |
| 223 | - [ ] [Minimum Cost to Merge Stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/) | Hard | Interval DP — advanced merge cost | |
| 224 | - [ ] [Distinct Subsequences](https://leetcode.com/problems/distinct-subsequences/) | Hard | 2D DP — count subsequence matches | |

### Advanced Design
| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 225 | - [ ] [LFU Cache](https://leetcode.com/problems/lfu-cache/) | Hard | Design — HashMap + DoublyLL + freq tracking | |
| 226 | - [ ] [Design HashMap](https://leetcode.com/problems/design-hashmap/) | Easy | Design — hashing fundamentals / chaining | |
| 227 | - [ ] [Max Stack](https://leetcode.com/problems/max-stack/) | Hard | Design — DoublyLL + TreeMap / Two stacks | |
| 228 | - [ ] [Design In-Memory File System](https://leetcode.com/problems/design-in-memory-file-system/) | Hard | Design — Trie-based file system | |

### Simulation
| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 229 | - [ ] [Robot Bounded In Circle](https://leetcode.com/problems/robot-bounded-in-circle/) | Medium | Simulation — direction state machine | |
| 230 | - [ ] [Walking Robot Simulation](https://leetcode.com/problems/walking-robot-simulation/) | Medium | Simulation — grid movement + obstacles | |
| 231 | - [ ] [Design Snake Game](https://leetcode.com/problems/design-snake-game/) | Medium | Simulation — deque-based game state | |

### Union-Find Implementation
| # | Problem | Difficulty | Pattern | Note |
|---|---------|-----------|---------|------|
| 232 | - [ ] [Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/) | Medium | Union-Find — rank + path compression from scratch | |
