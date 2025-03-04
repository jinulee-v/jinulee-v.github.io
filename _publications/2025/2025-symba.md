---
title:          "SymBa: Symbolic Backward Chaining for Structured Natural Langauge Reasoning"
date:           2025-04-29 00:01:00 +0800
selected:       true
pub:            "NAACL 2025 Main"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  To improve the performance and explainability of LLM-based natural language reasoning, structured reasoning can be applied to generate explicitly structured proofs. Among different methods for structured reasoning, we specifically focus on backward chaining, where the proof goal is recursively decomposed to subgoals by searching and applying rules. We argue that current LLM-based backward chaining systems (e.g. Least-to-most prompting and LAMBADA) are incomplete, as they omit crucial algorithmic components identified from the classic backward chaining algorithm (SLD Resolution) in computational logic. To this end, we propose a novel backward chaining system, SymBa (Symbolic Backward Chaining), which integrates a symbolic solver and an LLM. In SymBa, the solver controls the proof process, and the LLM is only called when the solver requires new information to complete the proof. Empowered by completeness, SymBa achieves a significant improvement in deductive, relational, and arithmetic reasoning benchmarks compared to the baselines.
cover:          /assets/images/covers/cover3.jpg
authors:
  - Jinu Lee
  - Weonseok Hwang (LBOX)
links:
  Paper: https://arxiv.org/abs/2402.12806
  Code: https://github.com/lbox-kr/symba
---
