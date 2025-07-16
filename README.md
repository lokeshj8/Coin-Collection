## 🪙 Coin Collection

A C++ project that solves the classic **Coin Collection Problem** using **Dynamic Programming** and lays the foundation for simple **text-based animation**.  

You start at the top-left corner of a grid and aim to collect the **maximum coins** by reaching the bottom-right corner. You can only move **right** or **down**.

---

## 🎯 Problem Statement

Given a 2D grid of non-negative integers, find the maximum number of coins that can be collected while moving from `(0,0)` to `(n-1,m-1)` using only **right** and **down** directions.

---

## 🧠 Solution Approach

We use **Dynamic Programming** to store the maximum coins that can be collected up to each cell.

### Transition Formula:
dp[i][j] = max(dp[i-1][j], dp[i][j-1]) + grid[i][j]

---

## 🛠 Features

- ✅ Efficient DP-based solution.
- ✅ Easy-to-read C++ code.
- ✅ Terminal-based animation to show coin collection progress.
- ✅ Highlights current cell during path traversal.
- ✅ Shows final coin count and optimal path.
- 🧩 Clean and modular code (easy to add GUI or visuals later).

---

## 🖼️ Example Grid

```cpp
vector<vector<int>> grid = {
    {0, 3, 1, 1},
    {2, 0, 0, 4},
    {1, 5, 3, 1}
};
---

💡 Sample Output
[0]  3   1   1
 2   0   0   4
 1   5   3   1

Collecting coins...
Maximum coins collected: 12
---
👨‍💻 Author
Lokesh Jejappagari
📧 jlokesh2002@gmail.com



