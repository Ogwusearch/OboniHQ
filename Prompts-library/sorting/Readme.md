
# Sorting Algorithms Documentation

This document covers **10 common sorting algorithms**, their characteristics, and how to use AI prompts to generate implementations in multiple programming languages.  

---

## 📚 List of Sorting Algorithms

| #  | Algorithm        | Type                  | Time Complexity (Avg) | Space Complexity | Stable |
|----|-----------------|---------------------|---------------------|-----------------|--------|
| 1  | Bubble Sort      | Comparison-based     | O(n²)               | O(1)            | Yes    |
| 2  | Selection Sort   | Comparison-based     | O(n²)               | O(1)            | No     |
| 3  | Insertion Sort   | Comparison-based     | O(n²)               | O(1)            | Yes    |
| 4  | Merge Sort       | Divide & Conquer     | O(n log n)          | O(n)            | Yes    |
| 5  | Quick Sort       | Divide & Conquer     | O(n log n)          | O(log n)        | No     |
| 6  | Heap Sort        | Heap-based           | O(n log n)          | O(1)            | No     |
| 7  | Counting Sort    | Non-comparison       | O(n + k)            | O(k)            | Yes    |
| 8  | Radix Sort       | Non-comparison       | O(nk)               | O(n + k)        | Yes    |
| 9  | Bucket Sort      | Non-comparison       | O(n + k)            | O(n)            | Yes    |
| 10 | Shell Sort       | Comparison-based     | O(n log n)–O(n²)    | O(1)            | No     |

> Notes:  
> - `n` = number of elements, `k` = range of values  
> - Stability indicates whether equal elements maintain their relative order  

---

## ⚡ AI Prompt Templates for Sorting

### 1. Minimal Template
```

Write a [language] function called {function_name} that sorts an array using {algorithm_name}.
Include simple comments explaining each step.

```

### 2. Advanced Template
```

Write a reusable [language] function {function_name} that implements {algorithm_name}.

* Validate inputs
* Support ascending/descending order
* Include step-by-step comments
* Include a small test example

```

### 3. Production Template
```

Write a fully optimized [language] {algorithm_name} function:

* Consider time and space complexity
* Include error handling
* Include optional logging/debug hooks
* Provide unit test examples
* Include detailed documentation and comments

```

---

## 🔧 How to Use

1. Select the algorithm you need from the list above.  
2. Copy the corresponding prompt from `minimal.md`, `advanced.md`, or `production.md`.  
3. Replace placeholders (`{language}`, `{function_name}`, `{algorithm_name}`) with your specific use case.  
4. Paste the prompt into your AI tool to generate the code.  
5. Optionally, refine the generated code with additional constraints or optimizations.  

---

## 💡 Tips

- For **small arrays or nearly sorted data**, prefer **Insertion Sort**.  
- For **large datasets**, prefer **Merge Sort** or **Quick Sort**.  
- For **integer or fixed-range data**, consider **Counting, Radix, or Bucket Sort**.  
- For **memory-sensitive applications**, Heap Sort or in-place Quick Sort is preferred.  
- Always test edge cases (empty array, single-element array, duplicate values).  

---

## 🖥 Supported Languages

- Python  
- JavaScript / TypeScript  
- Java  
- C / C++  
- Go  
- Rust  

> Additional languages can be added by modifying the `{language}` placeholder in your AI prompts.

---

This document is part of the **AI Prompt Library for Software Engineering**, specifically focused on **sorting algorithms**. Use it alongside `minimal.md`, `advanced.md`, and `production.md` prompt files for maximum productivity.
```

---

If you want, I can also **create the actual `.md` files (`minimal.md`, `advanced.md`, `production.md`) filled with prompts for all 10 sorting algorithms**, ready to drop into your folder.

Do you want me to do that next?

