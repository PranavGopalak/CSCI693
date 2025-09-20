# CSCI693

## 1. General Research Problem  
There is a well-recognized gap between the teaching of theoretical computer science and the practice of software engineering. Coursework in algorithms and data structures often emphasizes asymptotic complexity, formal proofs, and advanced structures like AVL trees or Fibonacci heaps. In contrast, practicing developers frequently prioritize simplicity, maintainability, and the efficiency of “good enough” solutions, typically relying on standard library data structures such as hash maps and arrays.

Competitive programming sits somewhere in between: it rewards mastery of algorithmic theory under artificial time constraints, yet does not necessarily reflect how engineers design systems in real projects. This raises a key question: **How do the choices of data structures differ between competitive programming environments and real-world software engineering?**

By empirically comparing open-source repositories with competitive programming submissions, this project seeks to shed light on the actual usage of data structures across these contexts. The results can inform both CS education and professional practice by identifying which structures matter most in each domain.

---

## 2. Primary Research Question  
**RQ1:** How does the usage of data structures in real-world software projects (e.g., GitHub repositories) differ from their usage in competitive programming contests?  

**Sub-questions include:**  
- Which “advanced” structures (e.g., balanced trees, priority queues, union-find) appear in competitive programming but are rarely found in real-world projects?  
- Conversely, which “simple” or library-provided structures (e.g., hash maps, arrays, vectors) dominate in real projects but may be under-represented in contests?  
- What factors (e.g., time pressure, problem framing, ecosystem libraries) might explain these differences?

---

## 3. Methodology & Data Sources  

### Data Sources  
- **Competitive Programming Submissions:** Publicly available datasets from platforms like Codeforces, AtCoder, or Kattis.  
- **Real-World Software Projects:** Open-source repositories on GitHub, filtered to ensure relevance and quality (e.g., belonging to known organizations such as Mozilla, Google, Microsoft, or exceeding thresholds for stars/forks).

### Data Collection & Processing  
- **Language Filtering:** Focus on a small set of common languages (e.g., C++, Java, Python) to reduce complexity of parsing.  
- **Data Structure Detection:** Use static code analysis and keyword heuristics (e.g., identifying usage of `std::map` vs. `std::unordered_map` in C++) to classify data structure usage.  
- **Normalization:** Adjust for project size and submission length to make usage comparable.  

### Analysis  
- Compare frequencies of different data structures across the two domains.  
- Identify patterns of “theory-heavy” structures (heaps, balanced trees) vs. “practical” structures (hash maps, arrays).  
- Evaluate how the contest framing vs. software engineering context drives these choices.  

---

## 4. Expected Contribution  
- **For Education:** Provide evidence-based recommendations on which data structures deserve more or less emphasis in curricula, bridging the gap between academic preparation and industry practice.  
- **For Practice:** Highlight the contexts where theoretically optimal structures may add unnecessary complexity, and where they genuinely provide real benefits.  
- **For Research:** Contribute to the empirical understanding of how theory translates into practice across domains.  
