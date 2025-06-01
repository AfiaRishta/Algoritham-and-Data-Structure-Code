# CSE2ALG Lexicon Builder (Part 1 & Part 2)

**Student:** Afia Zahin Rishta  
**Course:** CSE2ALG (Algorithms & Data Structures)  
**Semester:** 2025 S1  

---

## 📖 Project Overview

This repository contains a complete, two-part solution for building and analyzing a lexicon of words extracted from large text files. It demonstrates:

- **Part 1**: Correctness-focused implementation of custom sorting algorithms, hash tables, neighbor detection, CSV parsing, and basic statistical analysis.
- **Part 2**: Performance-optimized lexicon builder using:
  - **Hash Table** for O(1) average insert/lookup
  - **Pattern-Map** for O(n·ℓ) neighbor linking
  - **Heap Sort** for O(n·log n) alphabetical ordering
  - **Skip List** as a dynamic, O(log n) alternative

Key achievements:
- **Perfect sample-output matching** for provided test files (`s1.txt`, `s2.txt`).
- **18× speedup** (30 s → 1.7 s) on a 5.5 MB dataset via pattern-map optimization.
- **Skip List variant** that produces correct output in milliseconds on small samples and supports efficient incremental updates.
- A concise video walkthrough and written report (PDF) detailing design choices, Big-O analyses, and performance comparisons.

---

## 📂 Repository Structure

