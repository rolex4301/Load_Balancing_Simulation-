# Efficient Load Balancing Using Zig-Zag Scheduling Algorithm

This repository contains the implementation of a **load balancing scheduling algorithm** inspired by the **LOOK disk scheduling algorithm**, developed to efficiently distribute jobs across multiple machines. The project includes the **Zigzag Scheduling Algorithm**, which closely approximates the **Sorted Balanced Algorithm** while offering significantly better computational efficiency.

---

## Features

- **Zigzag Scheduling Algorithm**:
  - Efficient load balancing with **O(n)** time complexity.
  - Approximates the performance of the Sorted Balanced Algorithm (**O(n²)**) with an approximation factor of **1.5**.
  - Uses a novel zigzag pattern for assigning jobs to machines.

- **Python-based Simulator**:
  - Simulates and analyzes the performance of the proposed algorithm.
  - Compares with existing approaches like the **Sorted Balanced Algorithm**.

- **Theoretical Guarantees**:
  - Achieves an approximation factor consistently better than **2**, outperforming traditional methods.

---

## Files in Repository

- `Efficient_Load_Balancing.ipynb`: 
  - The Jupyter Notebook implementation of the proposed algorithm.
  - Includes detailed explanations, performance comparisons, and visualizations.

