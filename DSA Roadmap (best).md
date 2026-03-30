# Striver's A2Z DSA — 90-Day War Plan

**April 1 – June 30, 2026 | ~454 Problems | Goal: FAANG-Ready**

> This is not a casual study plan. This is a 90-day siege. You will average 5–7 problems per day,
> spend 4–6 hours daily, and by June 30 you will have the pattern recognition to dismantle
> any coding interview thrown at you.

---

## The Philosophy

The plan is split into two halves:

**PHASE 1 — "Cover the Battlefield" (April 1 – May 17, ~47 days)**
Burn through every foundational and mid-level topic. The goal is *breadth and speed*. You are
building the pattern library your brain will rely on under interview pressure. Every major data
structure, every core algorithm, every recurring trick — you see it, you solve it, you internalize it.

**PHASE 2 — "Sharpen the Blade" (May 18 – June 30, ~44 days)**
Now you go deep. Graphs, DP, Tries, Advanced Strings, Hard-tier problems from every topic.
This is where most people plateau. You won't. You will grind the hardest problems on the sheet,
do mixed-topic timed sessions, and run mock interviews until solving hard problems feels routine.

---

## Daily Non-Negotiables (Every Single Day)

- **Minimum 5 problems solved.** No exceptions. Sick days get 3 minimum.
- **Every problem:** Attempt solo for 20–30 minutes before watching/reading the editorial.
- **Dry-run your code on paper/whiteboard** for at least 2 problems per day.
- **Write the time and space complexity** for every solution. Out loud. No handwaving.
- **If you couldn't solve it:** Re-solve it from scratch the next morning without looking.
- **Weekend long sessions:** At least one 3-hour uninterrupted deep session on Sat and Sun.

---

---

# PHASE 1: COVER THE BATTLEFIELD

**April 1 – May 17 | Foundation + Core Topics | ~300 problems**

*The topics in this phase are ordered by how much interview surface area they cover.
Arrays, Binary Search, Recursion, Linked Lists, Stacks/Queues, Trees, Strings, and the
essential technique families (Sliding Window, Two Pointer, Greedy, Heaps, Bit Manipulation, Sorting).*

---

## MONTH 1: APRIL (Weeks 1–4)

---

### Week 1 — April 1–6: Basics + Sorting + Arrays (Easy)

**Topics:** Learn the Basics (31 problems), Sorting Techniques (7 problems), Arrays Easy section

**What to do:**
- Rip through the basics section at pace — these are warmups, not learning moments.
  Pattern printing, basic math, basic hashing, basic recursion. If you already know this,
  spend no more than 1.5 days here. Don't ego-skip; do them fast but do them.
- All 7 sorting problems. You must be able to write merge sort and quicksort from memory
  by the end of this week. Understand *why* each sort works, not just the code.
- Start the Arrays section — complete all Easy-level array problems.

**Targets:**
- Basics section: DONE
- Sorting section: DONE
- Arrays easy: DONE
- You can write merge sort, quick sort, and explain their recurrences without hesitation.

**Daily volume:** 7–10 problems/day (basics are fast, use the speed to build momentum)

---

### Week 2 — April 7–13: Arrays (Medium + Hard)

**Topics:** Remaining Array problems (Medium and Hard tiers — the bulk of the 40-problem section)

**What to do:**
- This is your first real wall. Medium arrays will introduce Kadane's, Dutch National Flag,
  prefix sums, hashing tricks, subarray problems, matrix operations.
- Hard arrays: merge intervals, missing/repeating numbers, inversion count, majority elements.
  These are direct interview questions. Treat every hard problem as a mock interview question —
  set a 30-minute timer, solve on paper first, then code.
- By the end of this week, you should *own* the array topic. If someone wakes you at 3 AM and
  asks you a subarray sum problem, you should be able to classify it in seconds.

**Targets:**
- All 40 array problems: DONE
- Can articulate when to use: prefix sum vs sliding window vs two pointer vs hashing on arrays.

**Daily volume:** 5–6 problems/day

---

### Week 3 — April 14–20: Binary Search (Full) + Strings (Basic & Medium)

**Topics:** Binary Search — 1D, 2D, Search Space (32 problems), Strings Basic & Medium (15 problems)

**What to do:**
- Binary Search is the single most pattern-dense topic on the sheet. 1D search, rotated arrays,
  search space problems (min of max, max of min, capacity/allocation), 2D matrix search.
- The critical skill: learning to *identify* that a problem is binary search. Half the battle
  in interviews is recognizing "this is monotonic, I can binary search the answer."
- Strings section — palindrome checks, anagram grouping, Roman numerals, string matching basics.
  These are fast but foundational.

**Targets:**
- All 32 Binary Search problems: DONE
- All 15 Strings (Basic & Medium) problems: DONE
- Given any "minimize the maximum" or "find the minimum capacity" problem, you immediately
  think binary search on the answer.

**Daily volume:** 6–7 problems/day

---

### Week 4 — April 21–27: Linked Lists (Full)

**Topics:** Linked Lists — Single LL, Double LL, Medium, Hard problems (31 problems)

**What to do:**
- Build single and doubly linked lists from scratch. Insert, delete, reverse — you should
  be able to do these in your sleep.
- Medium: detect cycle (Floyd's), find intersection, palindrome LL, add two numbers as LL.
- Hard: reverse in groups of K, flatten a linked list, clone with random pointers.
- Linked list problems are all about pointer manipulation. Draw every problem out before coding.
  Literally sketch the nodes and arrows on paper. This is the one topic where visualization
  matters more than pattern matching.

**Targets:**
- All 31 Linked List problems: DONE
- Can reverse a linked list iteratively and recursively without thinking.
- Understand Floyd's cycle detection well enough to *prove* why it works.

**Daily volume:** 5–6 problems/day

---

### April 28–30 (Buffer / Catch-up)

Use these 3 days to:
- Catch up on anything you're behind on.
- Re-solve every problem you couldn't crack solo during weeks 1–4 (your "redo list").
- If you're on track: start pulling ahead into Week 5 material.

**End of April checkpoint: You should have ~125–130 problems done.**

---

---

## MONTH 2: MAY (Weeks 5–8 + Phase Transition)

---

### Week 5 — April 28 – May 4: Recursion & Backtracking (Full)

**Topics:** Recursion PatternWise (25 problems)

**What to do:**
- This is the "learn to think recursively" week. Subsequences, combinations, permutations,
  N-Queens, Sudoku solver, palindrome partitioning, rat in a maze.
- The sheet groups these by pattern: subsequence pattern, trying all combinations, partition
  pattern. Internalize these three meta-patterns — almost every backtracking interview question
  is a variation of one of them.
- **Mandatory exercise:** For every recursive solution, draw the full recursion tree for a
  small input. This is non-negotiable. You need to *see* the tree to understand the complexity.

**Targets:**
- All 25 Recursion problems: DONE
- Can identify "generate all X" = backtracking, "count all X" = DP (this distinction is critical).
- Write the time complexity of backtracking solutions using the branching factor and depth.

**Daily volume:** 4–5 problems/day (these take longer; don't rush)

---

### Week 6 — May 5–11: Stacks & Queues (Full) + Bit Manipulation (Full)

**Topics:** Stack & Queues — Learning, Prefix/Infix/Postfix, Monotonic Stack, Implementation (30 problems), Bit Manipulation (18 problems)

**What to do:**
- Stacks: basics, then the real meat — next greater element, stock span, largest rectangle
  in histogram, celebrity problem, LRU cache, min stack. Monotonic stack is a *direct*
  interview favorite; understand the template cold.
- Queues: implement using stacks, sliding window maximum.
- Bit Manipulation: single number problems, power set, XOR tricks, count set bits, divide
  without operators. These are quick but appear as surprise interview questions — know them.

**Targets:**
- All 30 Stack/Queue problems: DONE
- All 18 Bit Manipulation problems: DONE
- Can implement a monotonic stack from memory and explain when it applies.
- Understand XOR properties well enough to solve single-number variants instantly.

**Daily volume:** 7–8 problems/day (bit manipulation problems are short; batch them)

---

### Week 7 — May 12–17: Sliding Window, Two Pointer, Heaps, Greedy

**Topics:** Sliding Window & Two Pointer Combined (12 problems), Heaps (17 problems), Greedy (16 problems)

**What to do:**
- Sliding Window / Two Pointer: longest substring without repeating, minimum window substring,
  subarrays with K distinct. Learn the fixed-window and variable-window templates.
- Heaps: Kth largest, merge K sorted lists, top K frequent, median from data stream.
  Know when heap beats sorting (streaming data, partial ordering).
- Greedy: activity selection, job sequencing, fractional knapsack, minimum platforms.
  The key insight: greedy works when local optimal = global optimal. For every problem,
  ask yourself "why does greedy work here?" and be able to prove it informally.

**Targets:**
- All 12 Sliding Window problems: DONE
- All 17 Heap problems: DONE
- All 16 Greedy problems: DONE
- Given a substring/subarray problem, you can instantly decide: sliding window vs prefix sum vs DP.

**Daily volume:** 7–8 problems/day

---

> **END OF PHASE 1 — May 17**
>
> **Checkpoint: ~300 problems done.** You've covered Basics, Sorting, Arrays, Binary Search,
> Strings (Basic), Linked Lists, Recursion, Stacks/Queues, Bit Manipulation, Sliding Window,
> Two Pointers, Heaps, and Greedy. You now have working fluency in every fundamental data
> structure and algorithmic technique. The pattern library is built. Now we harden it.

---

---

# PHASE 2: SHARPEN THE BLADE

**May 18 – June 30 | Trees, BST, Graphs, DP, Tries, Advanced Strings + Revision | ~155+ problems**

*These are the topics that separate "good" from "unstoppable." Graphs and DP alone make up
~110 problems on the sheet. Candidates who are strong here dominate interviews.*

---

### Week 8 — May 18–24: Binary Trees (Full)

**Topics:** Binary Trees — Traversals, Medium, Hard (39 problems)

**What to do:**
- Traversals: inorder, preorder, postorder (recursive + iterative + Morris). Level order.
  Vertical order. Boundary traversal. You need all of these in your toolkit.
- Medium: diameter, height, LCA, zigzag traversal, right/left view, path sum variants.
- Hard: serialize/deserialize, construct tree from traversals, maximum path sum, burn tree
  from a node. These are elite interview questions — spend real time on them.
- **Key habit this week:** Think about every tree problem in terms of "what info do I need
  from left subtree, right subtree, and current node?" This is the universal framework.

**Targets:**
- All 39 Binary Tree problems: DONE
- Can write all 3 traversals iteratively without reference.
- Morris traversal understood and implementable.

**Daily volume:** 5–6 problems/day

---

### Week 9 — May 25–31: BST (Full) + Tries (Full) + Advanced Strings

**Topics:** BST (16 problems), Tries (7 problems), Strings Advanced (9 problems)

**What to do:**
- BST: search, insert, delete, validate, LCA in BST, Kth smallest, floor/ceil, two sum in BST.
  The key difference from BT: *use the BST property* at every step.
- Tries: implement from scratch, word search, longest common prefix, word break,
  maximum XOR. Tries look scary but the implementation is simple once you build one.
  The problems are few but every single one is a classic interview question.
- Advanced Strings: KMP, Rabin-Karp, Z-function, repeated string match, minimum characters
  for palindrome. String matching algorithms are a weak spot for most candidates — this is
  your edge.

**Targets:**
- All 16 BST problems: DONE
- All 7 Trie problems: DONE
- All 9 Advanced String problems: DONE
- Can implement a Trie with insert/search/startsWith from scratch.
- Can explain KMP failure function and when to use it.

**Daily volume:** 5–6 problems/day

---

---

## MONTH 3: JUNE (Weeks 10–13)

---

### Week 10 — June 1–7: Graphs — Core Concepts & BFS/DFS

**Topics:** Graphs (first ~25 problems) — representation, BFS, DFS, cycle detection, bipartite,
topological sort, connected components

**What to do:**
- Build graphs from scratch: adjacency list, adjacency matrix. BFS and DFS on both.
- Cycle detection in directed (DFS + recursion stack) and undirected (DFS/BFS + parent tracking).
- Topological sort: both Kahn's (BFS) and DFS-based. This is *critical* — topological sort
  appears in dependency resolution, course scheduling, build systems.
- Bipartite check, connected components, flood fill, number of islands, rotten oranges.
- **This week is about building the graph mental model.** Every graph problem boils down to:
  what are the nodes, what are the edges, BFS or DFS, and what state am I tracking?

**Targets:**
- First ~25 Graph problems: DONE
- Can write BFS, DFS, topological sort, and cycle detection from memory.
- Given any "grid" problem, you immediately think: treat cells as nodes, adjacency = 4 directions.

**Daily volume:** 4–5 problems/day (graph problems require more thinking time)

---

### Week 11 — June 8–14: Graphs — Shortest Path, MST, Advanced

**Topics:** Remaining Graphs (~28 problems) — Dijkstra's, Bellman-Ford, Floyd-Warshall,
Prim's, Kruskal's, Union-Find, strongly connected components, bridges, articulation points

**What to do:**
- Shortest path algorithms: Dijkstra (with min-heap), Bellman-Ford (negative weights),
  Floyd-Warshall (all pairs). Know which to use when — this is a favorite interview question.
- MST: Prim's and Kruskal's. Kruskal's needs Union-Find — implement Union-Find with
  rank and path compression.
- Advanced: Kosaraju's/Tarjan's for SCCs, bridges and articulation points. These are the
  hard-tier problems that most candidates skip. Don't skip them.
- **Union-Find is used everywhere** — not just graphs. MST, cycle detection, dynamic
  connectivity, accounts merge. Master it.

**Targets:**
- All 53 Graph problems: DONE
- Can implement Dijkstra's, Kruskal's + Union-Find, and topological sort under time pressure.
- Understand when Dijkstra fails (negative edges) and what to use instead.

**Daily volume:** 4–5 problems/day

---

### Week 12 — June 15–23: Dynamic Programming (Full — The Marathon)

**Topics:** Dynamic Programming — all patterns and problems (56 problems)

**This is 9 days for 56 problems. ~6 problems/day. It will be brutal. That's the point.**

**What to do (by pattern, in order):**
- **Days 1–2: 1D DP.** Fibonacci variants, climbing stairs, house robber, maximum sum non-adjacent.
  Establish the "define state → write recurrence → memoize → tabulate → space optimize" pipeline.
- **Days 3–4: 2D/Grid DP.** Unique paths, minimum path sum, triangle, cherry pickup.
  Grid DP is the most visually intuitive DP family — use it to solidify your tabulation skills.
- **Days 5–6: Subsequence/Subset DP.** Subset sum, partition equal subset, coin change,
  unbounded knapsack, target sum, rod cutting. This is the 0/1 knapsack family.
  Learn the "pick/not-pick" template — it covers an enormous number of problems.
- **Days 7–8: String DP.** Longest common subsequence, edit distance, longest palindromic
  subsequence, wildcard/regex matching, distinct subsequences. String DP = 2D table where
  rows and columns are characters. Internalize this.
- **Day 9: DP on Stocks + Miscellaneous.** Buy/sell stocks (all variants), matrix chain
  multiplication, burst balloons, palindrome partitioning, word break.

**Targets:**
- All 56 DP problems: DONE
- For every problem, you can identify: what's the state, what are the transitions,
  what's the base case.
- Can convert any top-down solution to bottom-up and space-optimize it.
- The "pick/not-pick" pattern, the "LCS" pattern, and the "gap strategy" for interval DP
  are second nature.

**Daily volume:** 6–7 problems/day (no mercy)

---

### Week 13 — June 24–30: THE FINAL WEEK — Revision, Gaps, Mock Interviews

**This week has one purpose: make sure nothing falls through the cracks and simulate real
interview pressure.**

**Day-by-day structure:**

**June 24–25 (Tue–Wed): Full Sheet Audit & Weak Spot Blitz**
- Go through the entire 454-problem sheet. Mark every problem you're not 100% confident on.
- Re-solve your weakest 15–20 problems from scratch. No hints. Timer set.
- Focus especially on: hard array problems, monotonic stack problems, tree hard-tier,
  graph shortest paths, DP string problems. These are the most frequently bombed in interviews.

**June 26–27 (Thu–Fri): Mixed Topic Timed Sessions**
- Pick 4–5 random problems from different topics. Set a 75-minute timer (simulating a
  real interview round). Solve them on paper or a whiteboard first.
- Do 2 such sessions per day. After each session, review: where did you get stuck,
  what pattern did you miss, how was your time allocation?
- Practice thinking out loud. Narrate your approach before writing code. Interviewers
  care as much about your process as your solution.

**June 28–29 (Sat–Sun): Full Mock Interviews**
- Run 2 full mock interviews each day (use Pramp, Interviewing.io, or a friend).
- Each mock: 1 easy/medium warmup (5 min), then 1 hard problem (35 min), then discussion (5 min).
- After each mock, write down: what went well, what pattern you missed, one thing to fix.
- If you don't have a mock partner, simulate it alone: pick a random hard from the sheet,
  set 40 minutes, solve on a whiteboard, explain your solution to an empty room.

**June 30 (Mon): REST + Final Review**
- Light review of your most-missed patterns. Read through your personal notes.
- Review the "pattern cheat sheet" you've been building (see below).
- Rest. You've earned it. Tomorrow you walk into any interview room as a different person.

---

---

# PATTERN CHEAT SHEET — Build This As You Go

Every week, add to this document. By June 30, this becomes your last-night-before-interview review.

| Pattern | When to Use | Key Problems |
|---|---|---|
| Two Pointer | Sorted array, pair/triplet sum, container problems | 3Sum, Trapping Rain Water, Container With Water |
| Sliding Window | Subarray/substring with constraint, fixed or variable window | Min Window Substring, Longest Without Repeating |
| Binary Search on Answer | "Minimize the max" / "maximize the min" / monotonic check | Aggressive Cows, Book Allocation, Koko Eating Bananas |
| Monotonic Stack | Next greater/smaller, histogram, stock span | Largest Rectangle Histogram, Daily Temperatures |
| BFS | Shortest path unweighted, level-order anything | Rotten Oranges, Word Ladder, Shortest Path in Grid |
| DFS + Backtracking | "Generate all X", constraint satisfaction, grid exploration | N-Queens, Sudoku, Permutations, Word Search |
| Topological Sort | Dependencies, ordering, cycle in directed graph | Course Schedule, Alien Dictionary |
| Union-Find | Dynamic connectivity, MST, grouping, cycle in undirected | Accounts Merge, Kruskal's, Number of Provinces |
| Dijkstra | Shortest path weighted (non-negative) | Network Delay, Cheapest Flights |
| DP: Pick/Not-Pick | Subsequence/subset selection, knapsack family | Subset Sum, Coin Change, 0/1 Knapsack |
| DP: LCS Pattern | Two-string comparison, edit distance family | LCS, Edit Distance, Shortest Common Supersequence |
| DP: Gap Strategy | Interval merging, matrix chain multiplication | MCM, Burst Balloons, Palindrome Partitioning |
| Trie | Prefix matching, word dictionary, XOR maximization | Word Search II, Max XOR of Two Numbers |

---

# WEEKLY PROGRESS TRACKER

*Print this. Pin it on your wall. Check off every week. If a week isn't checked off by Sunday
night, you don't sleep until it is.*

| Week | Dates | Topics | Problem Count | Done? |
|------|-------|--------|:---:|:---:|
| 1 | Apr 1–6 | Basics, Sorting, Arrays (Easy) | ~45 | ☐ |
| 2 | Apr 7–13 | Arrays (Medium + Hard) | ~25 | ☐ |
| 3 | Apr 14–20 | Binary Search, Strings (Basic) | ~47 | ☐ |
| 4 | Apr 21–27 | Linked Lists | ~31 | ☐ |
| — | Apr 28–30 | Buffer / Redo List | — | ☐ |
| 5 | Apr 28–May 4 | Recursion & Backtracking | ~25 | ☐ |
| 6 | May 5–11 | Stacks/Queues, Bit Manipulation | ~48 | ☐ |
| 7 | May 12–17 | Sliding Window, Heaps, Greedy | ~45 | ☐ |
| 8 | May 18–24 | Binary Trees | ~39 | ☐ |
| 9 | May 25–31 | BST, Tries, Adv. Strings | ~32 | ☐ |
| 10 | Jun 1–7 | Graphs (BFS/DFS/Topo) | ~25 | ☐ |
| 11 | Jun 8–14 | Graphs (SP/MST/Advanced) | ~28 | ☐ |
| 12 | Jun 15–23 | Dynamic Programming (ALL) | ~56 | ☐ |
| 13 | Jun 24–30 | Revision + Mocks | ~20 resolves | ☐ |

---

# THE RULES

1. **No passive watching.** Striver's videos are a tool, not a crutch. Watch *after* you've
   attempted the problem for 20–30 minutes. Never watch first and code along — that's
   the illusion of learning.

2. **The Redo List is sacred.** Every problem you couldn't solve solo goes on the redo list.
   Every Sunday, re-solve at least 5 from the redo list. By June 30, the redo list should be
   empty.

3. **Explain to an invisible interviewer.** For at least 2 problems per day, explain your
   approach out loud before writing a single line of code. "I'd use a monotonic stack
   because we need the next greater element, which requires maintaining a decreasing
   sequence..." This skill wins interviews.

4. **Track your time.** Write down how long each problem took. Your goal: Easy < 10 min,
   Medium < 25 min, Hard < 45 min. If you're slower, that's fine early on, but by June
   these should be your benchmarks.

5. **No cherry-picking.** Do the problems in the order the sheet presents them within each
   topic. Striver ordered them for a reason — easier problems build intuition for harder ones.

6. **Sleep.** 7+ hours. Your brain consolidates patterns during sleep. Pulling all-nighters
   to "do more problems" is anti-productive. Intensity during waking hours, rest during sleep.

---

# THREE MONTHS FROM NOW

On July 1, 2026 you will have:
- Solved 454+ curated DSA problems
- Built fluency in 13+ pattern families
- Completed multiple mock interview sessions
- A personal pattern cheat sheet refined over 90 days
- The ability to look at any interview problem and, within 2 minutes, identify the
  data structure, the technique, and the approach

**This plan is aggressive by design. You asked for maximum effort. This is it.
The only variable is whether you execute.**

---

*"The pain of discipline is nothing like the pain of disappointment." — Go build.*
