
# ree-handling

**Console application for efficient player management using a balanced binary tree structure.**

---

## Table of Contents

- [About](#about)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Build and Run](#build-and-run)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [License](#license)

---

## About

**PlayerManager** is a **console-based Java application** that manages player records efficiently using a data structure known as a **treap** — a combination of a binary search tree and a heap.

Players are organized based on their **signup time**, while a randomly assigned **priority** ensures the structure remains balanced. This allows fast **insertion**, **deletion**, and **querying**, even as the dataset grows large.

The application supports several operations:

- **Inserting a new player**
- **Deleting a specific player**
- **Finding the player with the k-th best ranking**
- **Listing players registered within a specific date range**
- **Deleting all players with a particular signup date**
- **Finding the best-ranked player before a given date**

These features simulate realistic scenarios where **performance and data integrity** are essential.

---

## Getting Started

### Prerequisites

- **Java Development Kit (JDK)** version **11** or higher  
- A **Java IDE** such as **IntelliJ IDEA** or **Eclipse**  
- **File system support** for reading and writing serialized data  

---

### Build and Run

1. **Clone or open the project** in your chosen IDE  
2. **Compile and run** the `Main` class  
3. On first launch, a **data file is automatically created** if it does not already exist  
4. Use the **console menu** to manage players and perform operations  

---

## Features

- **Player Insertion**: Adds a player based on signup time, assigning a random priority to maintain balance  
- **Player Deletion**: Removes a player while preserving the tree structure  
- **k-th Best Player Retrieval**: Finds the player with the k-th best (lowest) ranking using efficient traversal  
- **Range Query**: Lists all players who signed up within a specified date range  
- **Bulk Deletion by Date**: Deletes all players registered on a particular date by splitting and merging the tree  
- **Best Ranking Before Date**: Finds the highest-ranked player registered before a given date  
- **Balanced Tree Structure**: Ensures efficient performance for large datasets through randomized balancing  

---

## Technologies Used

- **Java SE 11**  
- **Object Serialization**  
- **Custom Treap Data Structure**  
- **Scanner** and **File I/O**

---

## License

This project was developed **for academic and educational purposes**.  
It is **not licensed for commercial use**.
