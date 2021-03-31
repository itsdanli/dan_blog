---
layout: post
title:  "Data Structures Notes"
date:   2021-02-27
---

# Abstract Data Types vs. Data Structures

> Abstract data type is an abstraction of a data structure which provides only the interface to which a data structure must adhere to. It does not give details on how something should be implemented or in what programming language.

Abstraction (ADT) | Implementation (DS)
--- | ---
List | Dynamic Array, Linked List
Queue | Linked List based Queue, Array based Queue, Stack based Queu
Map | Tree Map, Hash Map / Hash Table
Vehicle | Golf Cart, Bicycle, Smart Car

1. Computational Complexity
> How much time does this algorithim need to finish?
> How much space does this alogirthm need for its computation?
- Big-O Notation: gives upper bound of complexity in worst case as input size becomes arbitrarily large

2. Static and Dynamic Arrays
> Fundamental building block for all other data structures
- Static Array
    - Fixed length container containing n elements indexable from range [0, n-1]
    - Contiguous chunks of memory -- meaning addresses are adjacent in static array, not like swiss cheese
    - Array indexing is zero-based
- Dynamic Array
    - One way to implement a dynamic array is to first implement static array
