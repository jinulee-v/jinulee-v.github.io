---
title: "SymBa: Symbolic Backward Chaining for Structured Natural Langauge Reasoning"
collection: publications
category: preprints
permalink: /publication/2024-symba
date: 2024-02-20
venue: 'arXiv'
paperurl: "https://arxiv.org/abs/2402.12806"
---

*Abstract*. While Large Language Models (LLMs) have demonstrated remarkable reasoning ability, providing a structured, explainable proof to ensure explainability, i.e. structured reasoning, still remains challenging. Among two directions of structured reasoning, we specifically focus on backward chaining, where the query is recursively decomposed to subgoals by applying inference rules. We point out that current popular backward chaining implementations (Least-to-most prompting and LAMBADA) fail to implement the necessary features of backward chaining, such as arbitrary-depth recursion and binding propagation. To this end, we propose a novel backward chaining framework, SymBa (Symbolic Backward Chaining). In SymBA, a symbolic solver controls the whole proof process, and an LLM searches for the relevant natural language premises and translates them into a symbolic form for the solver. By this LLM-solver integration, while producing a completely structured proof that is symbolically verified, SymBa achieves significant improvement in performance, proof accuracy, and efficiency in diverse structured reasoning benchmarks compared to baselines.