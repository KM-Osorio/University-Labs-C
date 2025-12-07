# Advanced Data Structures & Algorithms in C 🚀

### 📖 Overview
This repository contains rigorous implementations of fundamental computer science concepts developed during my Computer Engineering studies at **PUCP**. 

Unlike standard academic exercises, these modules focus on **low-level optimization**, **manual memory management** (heap allocation), and **data persistence** without relying on high-level abstraction libraries.

### 🛠️ Key Technical Competencies
* **Memory Safety:** Strict management of `malloc`, `calloc`, and `free` to prevent memory leaks.
* **Pointer Arithmetic:** Advanced manipulation of double pointers (`**Node`) for dynamic data structures.
* **Data Persistence:** Implementation of **Binary File I/O** for efficient storage and random access (`fseek`).
* **Algorithmic Complexity:** Sorting and searching algorithms optimized for specific business logic constraints.

---

## 📂 Core Modules

### 1. Dynamic Stream Processor (Linked Lists)
*Based on: Advanced Lab 09*
A data processing engine designed to ingest and filter real-time streaming analytics.
* **Architecture:** Implements a **Singly Linked List** with self-referential structures to handle dynamic datasets.
* **Key Algorithms:**
    * [cite_start]**Insertion Sort ($O(N)$):** Ingests data and automatically sorts nodes by category code upon insertion.
    * [cite_start]**Dynamic Pruning:** Filters and removes nodes that fail specific performance metrics (e.g., "drop-off" < 3.5) in real-time[cite: 219].
    * [cite_start]**Deep Memory Cleaning:** Recursively frees memory for complex nested structures (dynamic strings within nodes)[cite: 206].

### 2. Retail Database System (Binary Files)
*Based on: Special Project 2024-1*
A transactional system for managing book inventory and client sales using direct binary access.
* [cite_start]**Persistence:** Serializes `struct` data into `.bin` files for high-speed retrieval, bypassing text parsing overhead [cite: 138-139].
* [cite_start]**Business Logic:** Implements complex discount rules (tier-based logic) and updates customer records transactionally[cite: 135].
* [cite_start]**Data Integrity:** Merges data from CSV sources into a structured binary format and performs sorted report generation [cite: 140-141].

---

### 💻 Tech Stack
* **Language:** C (C99 Standard)
* **Tools:** GCC Compiler, Valgrind (for memory leak detection), Make.
* **Paradigm:** Procedural Programming / Modular Design.

---
*Note: These implementations prioritize understanding the "under-the-hood" mechanics of data structures over using pre-built libraries.*

