# Algo-Dump

![C++](https://img.shields.io/badge/C++-126%20files-blue?logo=cplusplus)
![Java](https://img.shields.io/badge/Java-3%20files-red?logo=openjdk)
![C](https://img.shields.io/badge/C-3%20files-lightgrey?logo=c)
![License](https://img.shields.io/badge/License-MIT-green)

A collection of **130+ algorithm implementations** covering sorting, dynamic programming, number theory, cryptography, backtracking, and more. Primarily in C++ with select Java and C implementations.

---

## Algorithms

### Sorting & Searching

| Algorithm | File | Complexity |
|-----------|------|------------|
| Merge Sort | `mergeSort.cpp` | O(n log n) |
| Quick Sort / Partition | `quick.cpp` | O(n log n) avg |
| Binary Search | `binaryB.cpp` | O(log n) |
| Inversion Count (Merge Sort) | `inversionCount.cpp` | O(n log n) |

### Dynamic Programming

| Problem | File(s) | Technique |
|---------|---------|-----------|
| 0/1 Knapsack | `knap.cpp` ... `knap5.cpp`, `knapIt.cpp` | Memoization, tabulation |
| Longest Common Subsequence | `lcs.cpp`, `lcsI.cpp` | 2D DP table |
| Longest Increasing Subsequence | `lis.cpp` | DP / binary search |
| Edit Distance | `edit.cpp`, `edit2.cpp` | 2D DP table |
| Subset Sum | `subsetSum.cpp`, `subsetRet.cpp`, `subsetok.cpp` | Recursion + DP |
| Word Break | `wordBreak.cpp` | DP + dictionary lookup |
| Min Sum Path | `minsum.cpp` | Grid DP |
| Matrix Sum | `matrixsum.cpp` | Grid traversal |

### Number Theory

| Algorithm | File(s) |
|-----------|---------|
| Prime Number (multiple methods) | `prime.cpp`, `primeB.cpp`, `primeE.cpp`, `primesW.cpp` |
| Sieve of Eratosthenes (Segmented) | `segSieve.cpp` |
| Euler's Totient Function | `etf.cpp`, `etf2.cpp`, `etfS.cpp`, `swgEtf.cpp` |
| GCD / Extended Euclidean | `gcdB.cpp`, `gcdExx.cpp`, `exEuclid.cpp` |
| LCM Sum | `lcmSum.cpp` |
| Modular Exponentiation | `power.cpp`, `mod.cpp` |
| Factorial (log N) | `factorial.cpp`, `factB.cpp`, `factN.cpp`, `divFact.cpp` |
| Fibonacci (Matrix Exponentiation) | `fib.cpp`, `fibo.cpp`, `fibSum.cpp` |

### Backtracking & Constraint Satisfaction

| Problem | File(s) |
|---------|---------|
| N-Queens | `nqueens.cpp`, `nqeen.cpp` |
| Sudoku Solver | `sudoku.cpp` |
| Rat in a Maze | `rat.cpp` |
| Permutation Generation | `permute.cpp`, `printPerm.cpp`, `returnPerm.cpp` |
| Subset Generation | `printSub.cpp`, `returncode.cpp`, `returnallcode.cpp` |
| Keypad Combinations | `keypad.cpp`, `keypadf.cpp` |

### Cryptography & Ciphers

| Cipher | File(s) |
|--------|---------|
| Caesar Cipher | `ceaser.cpp` |
| Hill Cipher | `ceaser.cpp` |
| Playfair Cipher | `ceaser.cpp`, `play.java` |
| Vigenere Cipher | `vignere.cpp` |
| Rabin-Karp String Matching | `rk.cpp` |

### String Algorithms

| Algorithm | File(s) |
|-----------|---------|
| Pattern Matching | `pattern.cpp`, `patternS.cpp` |
| Non-Repeating Characters | `nonrepating.cpp` |
| String Operations | `string.cpp`, `printCode.cpp` |

### Data Structures

| Structure | File |
|-----------|------|
| Linked List | `linked.cpp` |
| Stack | `stack.cpp` |
| Queue | `queue.cpp` |
| 3D Array | `3darray.cpp` |

### C++ STL

| Topic | File |
|-------|------|
| Map | `map.cpp`, `unordrered_map.cpp` |
| Set | `set.cpp` |
| Pair | `pair_class.cpp` |
| Vector & STL | `stl.cpp`, `vectorstl.cpp` |

### Theory of Computation

| Algorithm | File(s) |
|-----------|---------|
| Thompson NFA Construction | `thompson.c`, `thompson.cpp` |

---

## Documentation

The `docs/` folder contains supplementary PDF guides:

| Guide | File |
|-------|------|
| Java Competitive Programming Tricks | `docs/java tricks cp.pdf` |
| Pointers | `docs/pointers.pdf` |
| Recursion | `docs/recursion.pdf` |

---

## How to Run

```bash
# Compile and run any C++ file
g++ -o solution <filename>.cpp
./solution

# For Java files
javac <filename>.java
java <classname>

# For C files
gcc -o solution <filename>.c
./solution
```

---

## Repository Structure

```
Algo-Dump/
├── docs/                  # PDF guides (recursion, pointers, Java tricks)
├── *.cpp                  # 126 C++ implementations
├── *.java                 # 3 Java implementations
├── *.c                    # 3 C implementations
├── LICENSE
└── README.md
```

---

## License

MIT License

---

## Topics

`algorithms` `data-structures` `dynamic-programming` `backtracking` `number-theory` `cryptography` `competitive-programming` `cpp` `sorting-algorithms` `graph-algorithms` `recursion` `knapsack` `sieve-of-eratosthenes` `nqueens` `sudoku-solver` `string-algorithms`
