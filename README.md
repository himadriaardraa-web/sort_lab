# 🔢 Sort Lab — Algorithm Performance & Data Analytics

> An interactive web-based analytics tool for experimenting with sorting algorithms, collecting performance data, visualizing results, and understanding how algorithm performance changes with dataset size.

🌐 **Live Demo:**  
https://himadriaardraa-web.github.io/sort_lab/


---

## 📌 About the Project

**Sort Lab** is an interactive sorting algorithm visualization and performance analysis project developed as part of my journey in **Computer Science and Data Analytics**.

The project combines **Data Structures & Algorithms with data analysis** by treating every sorting operation as an experiment.

Instead of studying sorting algorithms only through theoretical Big-O notation, Sort Lab collects real execution data such as:

- Execution time
- Number of comparisons
- Number of swaps/writes
- Array size
- Sorting algorithm
- Sorting order

The collected data can then be analyzed to understand performance patterns and relationships between input size and execution time.

---

## 🎯 Project Objective

The main objective is to understand how algorithms behave in real-world execution by:

1. Generating or entering datasets
2. Running different sorting algorithms
3. Collecting performance metrics
4. Recording experimental results
5. Visualizing performance
6. Comparing algorithm behavior
7. Exporting results as CSV for further analysis

This project helped me connect **programming and DSA concepts with practical data analysis**.

---

## ✨ Key Features

### 🎲 Dataset Generation

Generate random arrays with different sizes or provide custom input data.

This allows controlled experiments using different datasets.

---

### 🔢 Sorting Algorithms

Select and execute different sorting algorithms and observe how they process the data.

The project can be extended with algorithms such as:

- Bubble Sort
- Selection Sort
- Insertion Sort
- Heap Sort
- Shell Sort
- Merge Sort
- Quick Sort

---

### 🎬 Sorting Visualization

The sorting process is displayed visually so that users can observe how elements are compared, moved, and arranged.

This makes algorithm behavior easier to understand while also providing a visual representation of the experiment.

---

## 📊 Performance Metrics

Sort Lab records measurable information from each experiment.

| Metric | Description |
|---|---|
| Array Size | Number of elements processed |
| Comparisons | Number of element comparisons |
| Swaps / Writes | Number of element movements |
| Execution Time | Time taken by the algorithm |
| Algorithm | Sorting algorithm used |
| Sorting Order | Ascending or descending |

These metrics form the project's experimental dataset.

---

## 📈 Data Analysis

The collected metrics can be used to study questions such as:

- How does execution time change as array size increases?
- Which algorithms perform more comparisons?
- How many swaps are required?
- How does algorithm behavior change with different inputs?
- Does practical performance follow theoretical complexity?

### 📁 CSV Export

The run log can be exported as a **CSV file**.

This allows the collected performance data to be opened in:

- Microsoft Excel
- Google Sheets
- Python
- R
- Other data-analysis tools

The exported data can also be used for further visualization and analysis.

## 🏗️ Project Workflow

```text
                ┌─────────────────┐
                │   Create Array  │
                │ Random / Custom  │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Select Sorting  │
                │    Algorithm    │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Select Order    │
                │ Ascending /     │
                │ Descending      │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Visualize Sort  │
                └────────┬────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ Performance Metrics  │
              │                      │
              │ Comparisons          │
              │ Swaps / Writes       │
              │ Execution Time       │
              └──────────┬───────────┘
                         │
                         ▼
                ┌─────────────────┐
                │   Run Log /     │
                │ Performance Data│
                └────────┬────────┘
                         │
              ┌──────────┴──────────┐
              ▼                     ▼
       ┌─────────────┐       ┌─────────────┐
       │ Scaling     │       │ CSV Export  │
       │ Analysis    │       │             │
       └─────────────┘       └─────────────┘
