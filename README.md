# CS 300 Portfolio Project – Course Management System

## Description
C++ course management system for an academic advising application. Implements and compares multiple data structures (vector, hash table, and binary search tree) for loading, searching, and sorting course data efficiently.

---

## Overview
This project was developed as part of CS 300 to simulate an academic advising system for a university. The program reads course data from a file, stores it using appropriate data structures, and allows users to print and search for course information.

The system demonstrates how different data structures impact performance when handling real-world data.

---

## Features
- Load course data from a CSV file
- Store course information with prerequisites
- Display all courses in alphanumeric order
- Search for a specific course by course number
- Validate prerequisites during data loading
- Menu-driven user interface

---

## Data Structure Used (Final Implementation)
- Hash Table (`unordered_map`)
  - Fast course lookup (O(1) average case)
  - Efficient storage and retrieval of course data

---

## Other Data Structures Analyzed
### Vector
- Simple implementation
- Requires sorting for ordered output
- Linear search performance (O(n))

### Binary Search Tree (BST)
- Maintains sorted order naturally
- Performance depends on tree balance
- Can degrade to O(n) in worst case

### Hash Table (Recommended)
- Fastest search performance
- Requires sorting only when displaying data
- Best overall choice for advising system requirements

---

## Runtime Analysis Summary
- **Vector**
  - Load: O(n)
  - Search: O(n)
  - Sort: O(n log n)

- **Hash Table**
  - Load: O(n)
  - Search: O(1) average
  - Sort: O(n log n)

- **BST**
  - Insert: O(log n) average, O(n) worst
  - Search: O(log n) average, O(n) worst

---

## Files Included
- `main.cpp` – Complete program implementation
- Course data input file (CSV format)
- README documentation

---

## Reflection

### What was the problem you were solving in the projects for this course?
The goal was to build an academic advising system that could store, manage, and retrieve course information efficiently using different data structures.

### How did you approach the problem?
I analyzed multiple data structures (vector, hash table, BST) to determine which would best handle searching, sorting, and storing course data efficiently.

### How did you overcome roadblocks?
I broke the project into smaller parts, tested each function individually, and used debugging output to identify issues with file parsing and data handling.

### How has this project expanded your approach to software design?
It taught me to consider performance and scalability before implementation and to choose data structures based on system requirements.

### How has your coding style evolved?
My code is now more modular, readable, and maintainable. I use clear function separation and consistent formatting to improve structure and adaptability.

## How to Run
1. Compile using a C++ compiler:
2. Run the executable:
3. Follow the menu prompts to load and interact with course data.

---

## Author
Victoria Sheff  
CS 300 – April 2026
