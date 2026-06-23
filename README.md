# Java Class Assignment 2: BST vs. Hash Table Performance Analysis

## 🎯 About the Project
This project is an empirical performance study designed to compare how efficiently two different data structures handle large volumes of data. Specifically, it measures and analyzes the execution times of a **Binary Search Tree (BST)** and a **Hash Table (HT)** written in Java.

The program guides the user through an automated benchmark process:
* **Dataset Initialization:** The user specifies the amount of data to test. The program then generates a massive set of random, large integer keys.
* **Indexing Performance (Insertion):** It inserts all generated keys into both the BST and the Hash Table, measuring exactly how many seconds each structure takes to store the data.
* **Retrieval Performance (Search):** It generates another set of random keys to search for within both completed structures, timing the total duration of the look-up operations.
* **Comparative Summary:** Finally, it presents a clear breakdown of the insertion times, search times, and the total combined time for each structure, demonstrating their real-world efficiency gaps.
