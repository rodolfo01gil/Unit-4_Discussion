# Unit 4 Discussion: Binary Search Trees

## Overview

This project demonstrated how Binary Search Trees (BSTs)
organized and searched data using recursive operations.

A BST was created to store numerical values, perform
searches, and display values in ascending order.

## Learning Objectives

The project demonstrated how to:

- Create a Binary Search Tree.
- Insert values recursively.
- Search for existing and missing values.
- Perform in-order traversal.
- Handle empty trees and duplicate values.
- Understand how tree structure affects performance.

## Implementation

Two classes were used: Node and BST.

The Node class stored a value and references to its
left and right children.

The BST class managed insertion, searching, and
in-order traversal.

Values smaller than the current node were inserted
into the left subtree, while larger values were
inserted into the right subtree.

Duplicate values were ignored.

## Tree Structure

The following values were inserted:

50, 30, 70, 20, 40, 60, 80

The resulting tree was:

             50
           /    \
         30      70
        /  \    /  \
      20   40  60   80

## In-Order Traversal

The program performed an in-order traversal by
visiting the left subtree, current node, and
right subtree.

Output:

[20, 30, 40, 50, 60, 70, 80]

This demonstrated how BST ordering produced
sorted results.

## Search Testing

The following searches were performed:

- 30: True
- 80: True
- 25: False
- 90: False

Existing values were found successfully, while
missing values returned False.

## Edge Cases

The program tested several edge cases:

1. Searching an empty tree returned False.
2. Traversing an empty tree returned an empty list.
3. Inserting a duplicate value did not change the tree.
4. Searching a single-node tree returned True
   when the value existed.

These tests demonstrated that the recursive methods
handled basic boundary conditions.

## Performance

The BST used comparisons to determine which
subtree to search.

Balanced BST operations generally required
O(log n) time for insertion and searching.

An unbalanced BST could require O(n) time.

In-order traversal required O(n) time because
every node was visited.

## Real-World Application

Binary Search Trees could be used to organize
numerical records, such as product identification
numbers in an inventory system.

The BST structure allowed records to be searched
using comparisons rather than scanning every value.

## Conclusion

This project improved my understanding of recursive
algorithms, tree structures, and data organization.

The implementation demonstrated how insertion order
affected tree structure and why balanced trees
were important for maintaining efficient searches.
