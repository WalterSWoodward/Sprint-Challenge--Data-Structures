
# Sprint Challenge #2: Data Structures

## Self Study Questions:

1. What are the order of insertions/removals for the following data structures?
    * Stack: Last In First Out
    * Queue: First In First Out
2. What is the retreival time complexity for the following data structures?
    * Linked List: O(n) since the computer needs to traverse the Linked List linearly
    (one node at a time) in order to find the desired node. 
    * Hash Table: O(1) since the execution time of a hash table is independent of its n value. 
    * Binary Search Trees: O(log n), which is second to O(1) in speed.
3. What are some advantages to using a Hash Table over an array in JavaScript?
    * Hash tables are generally considered better in terms of performance because their time 
    complexity for insertion, deletion, and searching are all constant O(1), while array time 
    complexity for those same categories are all constant O(n) with the exception of insertion,
    and deletions made from the beginning or end of an array.
