# CSCI693

### 1. General Research Problem

A well-documented gap exists between the study of theoretical computer science and the practice of software engineering. University algorithm courses often emphasize worst-case asymptotic complexity, mathematical proofs, and the implementation of highly specialized or complex data structures. In contrast, working software engineers often prioritize code simplicity, maintainability, and average-case performance on real-world data, frequently relying on a small set of "good enough" general-purpose tools provided by standard libraries.

This project seeks to bridge this gap by conducting a large-scale empirical analysis of public data. The goal is to move beyond anecdotal evidence and quantify how foundational algorithms and data structures are actually used "in the wild." By analyzing massive codebases, competitive programming solutions, and real-world network graphs, we can identify which theoretical concepts are most critical in practice and where common pitfalls lie. The ultimate aim is to provide data-driven insights that can inform both practical software development and computer science education.

### 2. Primary Research Questions

This study will address three primary research questions, each targeting a different facet of the theory-vs-practice divide:

* **RQ1: Data Structures in Practice:** In practice, how often are theoretically efficient but complex data structures (e.g., AVL trees, Fibonacci heaps) actually implemented or used in popular open-source projects versus their simpler, general-purpose counterparts (e.g., hash maps, dynamic arrays)?

* **RQ2: Algorithmic Problem-Solving:** By analyzing solutions to competitive programming problems, can we identify common logical errors or sub-optimal algorithmic approaches that contestants frequently make on problems related to specific domains like dynamic programming or graph theory?

* **RQ3: Graph Structures in the Wild:** What is the real-world distribution of graph structures? By analyzing networks like social media connections or software dependency graphs, are they more likely to be scale-free, small-world, or another topology, and what does this imply for practical algorithm choice?

### 3. Methodology & Data Sources

This research will be conducted by analyzing three distinct, publicly available datasets, with a specific methodology for each research question.
