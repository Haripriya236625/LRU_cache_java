# LRU Cache Implementation in Java

## Overview
This project implements a Least Recently Used (LRU) Cache using:

- Java
- HashMap
- Doubly Linked List

The implementation supports **O(1)** time complexity for both `get()` and `put()` operations.

# Features
- O(1) lookup using HashMap
- O(1) insertion and deletion using Doubly Linked List
- Automatic eviction of least recently used items
- Configurable cache capacity

# Time Complexity

| Operation | Complexity |
|-----------|------------|
| get() | O(1) |
| put() | O(1) |

# Data Structures Used
- HashMap
- Doubly Linked List

# Sample Output
```
Initial Cache:
(3,30) (2,20) (1,10)

Access key 2: 20
(2,20) (3,30) (1,10)

After inserting key 4:
(4,40) (2,20) (3,30)
```

# Concepts Demonstrated
- HashMap
- Doubly Linked List
- LRU Eviction Policy
- Object-Oriented Programming
- Time Complexity Optimization
