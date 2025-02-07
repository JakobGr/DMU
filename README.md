# Roommate Matching Algorithms: Branch and Bound, Exhaustive Search, and Edmonds' Blossom

## Overview
This repository contains code implementations for solving the roommate matching problem using three different algorithms:
1. **Branch and Bound (B&B)** - A combinatorial optimization approach that efficiently finds the optimal roommate pairings while allowing for flexible constraints.
2. **Exhaustive Search** - A brute-force algorithm that evaluates all possible pairings to determine the optimal solution.
3. **Edmonds' Blossom Algorithm** - A polynomial-time algorithm for finding maximum weighted matchings in general graphs.

Each algorithm is tested on **synthetically generated datasets**, which simulate student responses to a predefined compatibility questionnaire.

## Repository Structure
- **data/** – Contains generated compatibility datasets.
- **1_Generate_Data.ipynb** – Generates synthetic student compatibility data.
- **2_Branch_and_Bound.ipynb** – Implements the Branch and Bound algorithm for roommate matching.
- **3_Exhaustive_Algorithm.ipynb** – Implements the Exhaustive Search algorithm for comparison.
- **4_Edmonds_Blossom.ipynb** – Implements Edmonds' Blossom algorithm for efficient optimal matching.
