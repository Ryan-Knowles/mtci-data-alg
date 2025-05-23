# Big O Cheatsheet

Source: https://www.bigocheatsheet.com/

## Big O Complexity Chart

![Big O Complexity Chart](./big_o_complexity_chart.png)

## Common Data Structure Operations

| Data Structure     | Time Complexity |           |           |           |           |           |           |           | Space Complexity |
| ------------------ | --------------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- | ---------------- |
|                    | Average         |           |           |           | Worst     |           |           |           | Worst            |
|                    | Access          | Search    | Insertion | Deletion  | Access    | Search    | Insertion | Deletion  |                  |
| Array              | O(1)            | O(n)      | O(n)      | O(n)      | O(1)      | O(n)      | O(n)      | O(n)      | O(n)             |
| Stack              | O(n)            | O(n)      | O(1)      | O(1)      | O(n)      | O(n)      | O(1)      | O(1)      | O(n)             |
| Queue              | O(n)            | O(n)      | O(1)      | O(1)      | O(n)      | O(n)      | O(1)      | O(1)      | O(n)             |
| Singly-Linked List | O(n)            | O(n)      | O(1)      | O(1)      | O(n)      | O(n)      | O(1)      | O(1)      | O(n)             |
| Doubly-Linked List | O(n)            | O(n)      | O(1)      | O(1)      | O(n)      | O(n)      | O(1)      | O(1)      | O(n)             |
| Skip List          | O(log(n))       | O(log(n)) | O(log(n)) | O(log(n)) | O(n)      | O(n)      | O(n)      | O(n)      | O(n log(n))      |
| Hash Table         | N/A             | O(1)      | O(1)      | O(1)      | N/A       | O(n)      | O(n)      | O(n)      | O(n)             |
| Binary Search Tree | O(log(n))       | O(log(n)) | O(log(n)) | O(log(n)) | O(n)      | O(n)      | O(n)      | O(n)      | O(n)             |
| Cartesian Tree     | N/A             | O(log(n)) | O(log(n)) | O(log(n)) | N/A       | O(n)      | O(n)      | O(n)      | O(n)             |
| B-Tree             | O(log(n))       | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(n)             |
| Red-Black Tree     | O(log(n))       | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(n)             |
| Splay Tree         | N/A             | O(log(n)) | O(log(n)) | O(log(n)) | N/A       | O(log(n)) | O(log(n)) | O(log(n)) | O(n)             |
| AVL Tree           | O(log(n))       | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(n)             |
| KD Tree            | O(log(n))       | O(log(n)) | O(log(n)) | O(log(n)) | O(n)      | O(n)      | O(n)      | O(n)      | O(n)             |

## Array Sorting Algorithms

| Algorithm      | Time Complexity |                |                | Space Complexity |
| -------------- | --------------- | -------------- | -------------- | ---------------- |
|                | Best            | Average        | Worst          | Worst            |
| Quicksort      | Ω(n log(n))     | Θ(n log(n))    | O(n^2)         | O(log(n))        |
| Mergesort      | Ω(n log(n))     | Θ(n log(n))    | O(n log(n))    | O(n)             |
| Timsort        | Ω(n)            | Θ(n log(n))    | O(n log(n))    | O(n)             |
| Heapsort       | Ω(n log(n))     | Θ(n log(n))    | O(n log(n))    | O(1)             |
| Bubble Sort    | Ω(n)            | Θ(n^2)         | O(n^2)         | O(1)             |
| Insertion Sort | Ω(n)            | Θ(n^2)         | O(n^2)         | O(1)             |
| Selection Sort | Ω(n^2)          | Θ(n^2)         | O(n^2)         | O(1)             |
| Tree Sort      | Ω(n log(n))     | Θ(n log(n))    | O(n^2)         | O(n)             |
| Shell Sort     | Ω(n log(n))     | Θ(n(log(n))^2) | O(n(log(n))^2) | O(1)             |
| Bucket Sort    | Ω(n+k)          | Θ(n+k)         | O(n^2)         | O(n)             |
| Radix Sort     | Ω(nk)           | Θ(nk)          | O(nk)          | O(n+k)           |
| Counting Sort  | Ω(n+k)          | Θ(n+k)         | O(n+k)         | O(k)             |
| Cubesort       | Ω(n)            | Θ(n log(n))    | O(n log(n))    | O(n)             |
