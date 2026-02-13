# Data Structure Optimization Project

2025-1 Data Structure Final Project

## Overview

This project demonstrates the optimization of a symmetric difference calculation algorithm by comparing two Abstract Data Type (ADT) implementations: Binary Search Tree (BST) and Min Heap. The goal is to improve either time complexity or memory space usage.

## Problem Solved

**Problem 1269: Symmetric Difference**
- Calculate the symmetric difference between two sets (elements that are in either set but not in both)
- Original implementation uses BST for set operations
- Optimized implementation uses Min Heap with heapsort for better performance

## Implementations

### Original Code (referal.c)
- Uses Binary Search Tree (BST) for set representation
- Time Complexity: O(n log n) for insertions and searches
- Space Complexity: O(n) for tree nodes

### Optimized Code (1269-202411965.c)
- Uses Min Heap with heapsort for sorting arrays
- Time Complexity: O(n log n) for sorting, O(n) for merging
- Space Complexity: O(n) for heap and arrays

## Performance Comparison

| Metric | BST Implementation | Min Heap Implementation | Improvement |
|--------|-------------------|------------------------|-------------|
| Time | 284ms | 104ms | 2.73x faster |
| Space | 13524kb | 3468kb | 3.9x less memory |

**Summary**: Min Heap implementation takes 180ms less time and saves 10074kb memory space compared to BST.

## How to View

Open `index.html` in any web browser to see:
- Side-by-side code comparison
- Performance metrics table
- Complete implementation details

## Technologies Used

- C programming language
- HTML/CSS for project showcase
- Binary Search Tree ADT
- Min Heap ADT
- Heapsort algorithm

## Project Structure

- `referal.c` - Original BST-based implementation
- `1269-202411965.c` - Optimized Min Heap implementation
- `index.html` - Interactive project showcase
- `README.md` - This documentation
- `report-pdf` - Full report of the project

## References

Based on lecture materials and problem sets from 2025-1 Data Structure course. Refer to course PDF for detailed problem specifications.

refer pdf for details explanation. 

