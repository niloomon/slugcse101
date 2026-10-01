---
title: "CSE 101: Data Structures and Algorithms"
subtitle: "University of California, Santa Cruz"
---

**************************************************
### | [Learning Outcomes](#learning-outcomes) | [Slides](#slides) | [Worksheets](#worksheets) |

**************************************************
<div class="hero">
<div class="hero-figure">
<img src="images/slug-bst.png" alt="Slugs BST" />
</div>
<div class="hero-text">
<h1 id="learning-outcomes">Course-Level Outcomes</h1>
<p>By the end of the course, students should be able to:</p>
<details class="outcome">
<summary>Apply systematic problem-solving techniques and recursive reasoning to algorithm design and implementation.</summary>
<ul>
<li>Recall and apply problem-solving techniques: understand the problem with a toy example, develop an initial solution, create and run test cases, improve efficiency, and repeat.</li>
<li>Identify problems that can be solved using recursion and formulate and implement recursive solutions.</li>
<li>Convert recursive code to non-recursive code using stacks.</li>
</ul>
</details>

<details class="outcome">
<summary>Understand fundamental data structures, their implementation, applications, and performance implications.</summary>
<ul>
<li>Explain the purpose and importance of selecting appropriate data structures and algorithms for time and memory efficiency.</li>
<li>Explain the strengths, limitations, and applications of arrays, linked lists, stacks, binary heaps/priority queues, binary search trees, AVL trees, hash tables, and graph representations, including matrices and adjacency lists.</li>
<li>Explain algorithms used to manipulate and query these data structures efficiently.</li>
<li>Explain the differences between abstract data types (ADTs) and data structures.</li>
</ul>
</details>

<details class="outcome">
<summary>Understand and analyze algorithm efficiency and performance.</summary>
<ul>
<li>Explain asymptotic analysis and compare functions asymptotically using Big-O, Big-Omega, and Big-Theta.</li>
<li>Understand worst-case, best-case, average-case, and amortized analysis.</li>
<li>Analyze a given algorithm and identify upper and lower bounds for its time and memory requirements using Big-O, Big-Omega, and Big-Theta.</li>
</ul>
</details>

<details class="outcome">
<summary>Select, design, and implement appropriate data structures based on problem constraints, data characteristics, and performance requirements.</summary>
<ul>
<li>Evaluate the suitability of data structures and algorithms based on data mutability, access patterns, and performance requirements.</li>
<li>Identify or design the best data structure for a given problem based on constraints, the nature of the data, including sorted or unsorted and static or dynamic data, how the data is manipulated or accessed, and efficiency requirements such as memory limits, time limits, and query rates.</li>
<li>Design and implement a dictionary-like data structure using arrays of linked lists to index large data sets for quick query responses.</li>
<li>Implement BST and AVL trees, along with a special range search algorithm for fast handling of range search queries.</li>
</ul>
</details>

<details class="outcome">
<summary>Understand and evaluate algorithms for sorting and searching in linear data structures for static data.</summary>
<ul>
<li>Recall the key properties of common sorting algorithms and explain their differences in runtime, memory usage, and stability.</li>
<li>Explain when sorting and binary search are appropriate, and evaluate their suitability based on data mutability and access patterns.</li>
</ul>
</details>

<details class="outcome">
<summary>Understand and evaluate tree-based data structures, including BST, AVL, and heap, and their application to dynamic data.</summary>
<ul>
<li>Understand and apply binary search trees to support efficient searching, dynamic updates, ordered access, and range queries.</li>
<li>Understand and apply fundamental algorithms for traversing and manipulating tree-based data structures.</li>
<li>Compare AVL trees with unbalanced BSTs in terms of time complexity and performance guarantees.</li>
<li>Explain the structure and array-based implementation of heaps, evaluate their performance in common operations, and apply them to problems such as priority queues and heap sort.</li>
</ul>
</details>

<details class="outcome">
<summary>Understand and apply graph data structures and algorithms to model relationships, compute shortest paths, and analyze algorithmic efficiency based on graph properties.</summary>
<ul>
<li>Represent data and relationships as a graph, choose an appropriate representation, such as a matrix or adjacency list, and justify the choice.</li>
<li>Explain major graph algorithms, including BFS, DFS, Dijkstra, and Bellman-Ford, their applications, the types of graphs they apply to, such as weighted, unweighted, positive-weight, or negative-weight graphs, their output, such as a path or tree, and their efficiency.</li>
<li>Implement and apply BFS to find the shortest path between two nodes. A hash table is also used in this project.</li>
</ul>
</details>

<details class="outcome">
<summary>Develop problem-solving strategies and coding practices essential for technical interviews and robust algorithm design.</summary>
<ul>
<li>Develop familiarity with coding interview questions involving fundamental data structures and algorithms, such as linked lists, stacks, recursion, and BSTs.</li>
<li>Evaluate algorithm correctness by identifying and testing edge and corner cases.</li>
</ul>
</details>
</div>
</div>


::: {.two-col}

::: {.col}

# Slides


| Topic | PowerPoint Online | 
| ----- | ----------------- 
| Course Introduction | [PPT](https://1drv.ms/p/c/6e432cb3cc755285/IQCvW4RY1hmZRanJ7YodnFQ3AUVLC4nicC7BzPE1mgTQ0v0) | 
| Linked Lists (and Recursion)| [PPT](https://1drv.ms/p/c/6e432cb3cc755285/IQBa3Km6JX8SSLrjFOW_pPUhAciYJOBm8iemHo30LISxCZs) |
| Stacks and Recursion | [PPT](https://1drv.ms/p/c/6e432cb3cc755285/IQBKD_e5wOlcRJNOde7qzABMAXFYJqKLre2LV0gLWVgIOU0) | 
| Asymptotic Analysis & Big-O | [PPT](https://1drv.ms/p/c/6e432cb3cc755285/IQCccZ-i1nOISaI602wrARU1Af5FATGypazm-6cgiGzJux4) | 
| Simple Sorting Algorithms | [PPT](https://1drv.ms/p/c/6e432cb3cc755285/IQAwUCrGoLyrTLjyhbMIDa06AfBj1lYqjxGFcUXRBWKZzAo) |
| Binary Search and BST | [PPT](https://1drv.ms/p/c/6e432cb3cc755285/IQALZfVlurVlRofb-0MxLnxlAX5St9f16TRq82r3jjfzrgE?e=fGQJNs) | 
| Balanced Trees - AVL | [PPT](https://1drv.ms/p/c/6e432cb3cc755285/IQDNLxWe1LAWRZhxzEReRUfqAepIrlh_aOFvPxKLbHxoa5g?e=eXN8kt) | 
| Priority Queues - Heap | [PPT](https://1drv.ms/p/c/6e432cb3cc755285/IQC0ejw67KXyQ6GFFWvPxfHGAQXmlVD7_aYmxITcK6Zgewo?e=5lZr4H) | 
| Advanced Sorting Algorithms | [MergeSort](https://1drv.ms/b/c/6e432cb3cc755285/IQAd_Wg0-kUlTqGVN_3xQogzAczb7asjjdmkVON1GSsH6R0?e=3FaFYc)  -  [QuickSort](https://1drv.ms/p/c/6e432cb3cc755285/IQDkzEnmqTd0Q7P2TOF3mTCzAasWFo6cr1vroebLgcNglhA?e=bTLcFZ) | 
| Graphs | [Graph Theory](https://1drv.ms/p/c/6e432cb3cc755285/IQBNaB7ANnBvRrGsY5lmoqqHASzFvk-M4jYwpep9IOMbRZE?e=WubeMC)  -  [BFS](https://1drv.ms/p/c/6e432cb3cc755285/IQB7uYhQv8-wR5fC_6kc-fWqASh-8xctucZcJjKLQXkXPAQ?e=hvjr0Q)  -  [DFS](https://1drv.ms/p/c/6e432cb3cc755285/IQCYZDQjdpsZS5UTSbtjmcK6AQkgrJn9AQ-u55kZ_tuHRfk?e=rOEgvi) | 
| Hashing | [PPT](https://1drv.ms/p/c/6e432cb3cc755285/IQDbL1rPt6nzQZi7a5Nh9IPpAVjw73iL-xcCGsszY-WPHjY?e=kbliIl) | 

:::

::: {.col}

# Worksheets


| Topic | Worksheet |
| ----- | --------- |
| Asymptotic analysis practice | [Google Doc](https://docs.google.com/document/d/142dBhZu7qZFsBzS_y7oPFJFFbTp6R4t84TL2aVdPO9w?usp=drive_fs) |
| HW0 Worksheet | [Google Doc](https://docs.google.com/document/d/1oZ8pD1-TGLcxir5Sxp9PzIxMNMemT80bCc1NQtr6iFE?usp=drive_fs) |
| Test1 Worksheet | Coming Soon |
| HW1 Worksheet| [Google Doc](https://docs.google.com/document/d/1wFs85B5o-bOrLnxu4E7erQytv0uqKTrT6UfTQdwsUlE?usp=drive_fs) |
| HW2 Worksheet | [Google Doc](https://docs.google.com/document/d/1Y-vhI3Y-JUb4FAnxrZbRV0V8U0fbQBqmYvnhX-Oq0Wc/edit?usp=sharing) |
| Test2 Worksheet | [Google Doc](https://docs.google.com/document/d/1-ttdnPwfFI6SfsC1-SlCr8DLYaC7ixA3us7VK5Iqiqo/view?usp=sharing) |
| HW3 Worksheet | [Part 1 - BST](https://docs.google.com/document/d/1N6nnjzLiRm4GpjLLD8B1dOL0F3JTNQvb2kdNvQRBaJs?usp=drive_fs)  -  [Part 2 - AVL](https://docs.google.com/document/d/1WgsQB1A87nxOZM7FT-hURIh-bAFQUJfNMLXCxb-g7xA?usp=drive_fs) |
| Test3 Worksheet | Coming Soon |
| HW4 Worksheet | [Google Doc](https://docs.google.com/document/d/1dpFGbSYzDhPuMk0Ge_cx7jt2xSvjsKbZr7QI_PIu-Ow?usp=drive_fs) |
| Dijkstra's Worksheet | [PDF](https://drive.google.com/file/d/1aWM0wQ-Fv086btnLcraVp18pfPozfs1l/view?usp=drive_link) |

:::

:::

**************************************************
**************************************************

<!--
To preview this page in Safari, run  ./show
To publish it on the web, run        ./update

Put public PDF exports in materials/slides/ and public worksheets in
materials/worksheets/. Replace "Coming soon" with markdown links, for example:
[PDF](materials/slides/L01-algorithm-analysis.pdf)
[worksheet](materials/worksheets/W01-asymptotic-analysis.pdf)

For editable PPTX files, keep the active file in OneDrive and paste the
"Anyone with the link can view" PowerPoint Online link in the PowerPoint column.
-->
