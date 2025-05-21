# 0/1 Knapsack Problem Analysis

This project analyzes the performance of various algorithms for solving the 0/1 Knapsack Problem, including Brute Force, Branch and Bound, Dynamic Programming, and Greedy Heuristic. It includes optimizations like parallel processing, caching, and data persistence, making it suitable for advanced computational studies.

## Features
- Generates knapsack instances with customizable parameters (e.g., item count, cost/weight correlation, granularity).
- Implements four knapsack algorithms with performance tracking (runtime and steps).
- Uses parallel processing to speed up experiments.
- Saves results to CSV files and generates plots for analysis.
- Visualizes performance trends using Seaborn.

## Requirements
- Python 3.8+
- Libraries: `matplotlib`, `seaborn`, `pandas`, `torch` (optional for GPU), `sentence-transformers` (if using similarity models)
- Install dependencies using:
  ```bash
  pip install -r requirements.txt
