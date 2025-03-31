
# 📘 Advanced Algorithms – Homework 2

This repository contains solutions to the second homework assignment of the **Advanced Algorithms** course. The problems cover a variety of classic algorithmic techniques including **Dynamic Programming**, **Greedy Algorithms**, and **Heap-based optimization**. Each question is solved in a Jupyter Notebook, with thorough explanations and complexity analysis.

---

## 📂 Contents

| Notebook | Title | Technique | Time Complexity |
|----------|-------|-----------|-----------------|
| **Q1** | Subset Sum with No Adjacent Elements | Dynamic Programming | O(n) |
| **Q2** | Tigers in Cages (Age-Distance Constraint Matching) | DP + Sorting + Greedy | O(n³) |
| **Q3** | Oil Purchase & Sales (Max Profit with Storage Penalty) | 0/1 Knapsack DP | O(nm) |
| **Q4** | Connecting Ropes with Minimum Cost | Greedy (Min-Heap) | O(n log n) |
| **Q5** | Prize Distribution Based on Scores | Greedy (Two-Pass) | O(n) |
| **Q6** | Minimum Time to Complete Tasks (Feasibility with K Workers) | Greedy Partitioning | O(n) |

---

## ✅ Problem Summaries & Techniques

### **1. Subset Sum with No Adjacent Elements**
Select a subset of numbers from a sequence such that no two selected elements are adjacent, and the sum is maximized.

> **Technique:** Dynamic Programming  
> **Complexity:** O(n)

---

### **2. Tigers in Cages**
Assign `n` tigers to `n²` cages under constraints involving age and cage distance, minimizing discomfort based on size-capacity mismatch.

> **Technique:** DP with Prefix-Min Optimization  
> **Complexity:** O(n³)

---

### **3. Oil Purchase & Sales**
Choose a subset of oil purchase orders to maximize profit while accounting for a per-barrel storage penalty for unused oil.

> **Technique:** 0/1 Knapsack DP  
> **Complexity:** O(n × m)

---

### **4. Connecting Ropes**
Connect all ropes into one with minimum cost. Cost of connecting two ropes is the sum of their lengths.

> **Technique:** Greedy with Min-Heap (Priority Queue)  
> **Complexity:** O(n log n)

---

### **5. Prize Distribution**
Distribute a minimum number of books to participants based on scores, ensuring that those with higher scores than neighbors get more books.

> **Technique:** Greedy Two-Pass (Left-to-Right + Right-to-Left)  
> **Complexity:** O(n)

---

### **6. Minimum Time to Complete Tasks**
Check whether all tasks can be completed within a time limit `T` using `K` workers, under the constraint that each worker performs **consecutive** tasks.

> **Technique:** Greedy Partitioning (Feasibility Check)  
> **Complexity:** O(n)

---

## 📚 Dependencies

- Python 3.x
- Jupyter Notebook or JupyterLab
- Standard Python libraries: `heapq`, `collections`, etc.
