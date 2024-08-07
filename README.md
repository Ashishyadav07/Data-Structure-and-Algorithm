## Data Structure

Data Structure is a particular way of organising data in a computer so that it can be use effectively. The main idea is to reduce the space and time complexity of different task.

There are two types of Data Structure 

i) Linear Data Structure - Data structure in which data elements are arranged sequentially or linearly, where each element is attached to its previous and next adjacent elements.

Static Data Structure -  Static data structure has a fixed memory size. It is easier to access the elements in a static data structure. 
   
   - Array

Dynamic Data Structure -  In dynamic data structure, the size is not fixed. It can be randomly updated during the runtime which may be considered efficient concerning the memory (space) complexity of the code. 

   - Linked List
   - Stack
   - Queue

ii) Non Linear Data Structure - Data structures where data elements are not placed sequentially or linearly are called non-linear data structures. In a non-linear data structure, we can’t traverse all the elements in a single run only. 
   
   - Tree
   - Graph

## Algorithm

Algorithm is a set of instruction to perform a task or to solve a given problem.

## Analysis of Algorithm

Analysis of algorithm deals in finding best algorithm which runs fast and takes in less memory.

## Time Compelxity

- It is the amount of time taken by algorithm to run.
- The input processed by an algorithm helps in determining the time complexity.

## Space Complexity

- It is the amount of memory or space taken by algorithm to run.
- The memory required to process the input by an algorithm helps in determining the space complexity.

## Asymptomatic Analysis

- Asymptomatic analysis helps in evaluation performance of an algorithm in terms of input size and its increase.
- Using asymptomatic analysis we don't measure actual running time of algorithm.
- It helps in determining how time and space taken by algorithm increases with input size.

## Asymptomatic Notation

- Asymptomatic notation are the mathemcatical tools used to describe the running time of an algorithm in terms of input size.
- Asymptomatic notation helps in determining best case, average case and worst case.

## Types of Asymptomatic Notations

- There are three notation for performing runtime analysis of algorithm.

. Omega Notation
. Big O Notation
. Theta Notation

### Omega Notation

- It is the formal way to express the lower bound of an algorithm's running time.
- Lower bound means for any given input this notation determines best amount of time an algorithm can take to complete.

### Big O Notation

- It is the formal way to express the upper bound of an algorithm's running time.
- Upper bound means for any given input this notation determines longest amount of time an algorithm can take to complete.

### Theta Notation

- It is the formal way to express the both upper bound and lower bound of an algorithm's running time.
- By lower and upper bound means for any given input time this notation determines average amount of time an algorithm can take to complete.

## Rules of Big O Notation

- It is a single processor.
- It performs sequential execution of statement.
- Assignment operation takes 1 unit of time. Example int x = 5;
- Return statement takes 1 unit of time. Example return return x;
- Arithmetical operation takes 1 unit of time. Example x + y;
- Logical operation takes 1 unit of time.
- Other small/single operation takes 1 unit of time.
- Drop lower order items
- Drop constant multipliers.

Example - T = 3n² + 6n + 1 ==> O(n²)

