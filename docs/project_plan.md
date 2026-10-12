# ContextLens: Project Plan

## Research Question

When an AI system answers questions about heat-related health risks, does it retrieve relevant evidence across different geographic contexts? Can context-aware retrieval improve evidence relevance and coverage?

## Initial Scope

The first prototype will focus on heat-related health questions. Online addiction in children may be considered later if time permits.

## Systems to Compare

1. Keyword-based retrieval.
2. Semantic retrieval using text embeddings.
3. Context-aware semantic retrieval.
4. An LLM answer baseline, evaluated separately if feasible.

## Evaluation

We will build a documented set of questions and source passages, then define relevance judgments before comparing systems.

Planned metrics:
- Recall at k: the proportion of relevant passages retrieved in the top k results.
- Precision at k: the proportion of top k results judged relevant.
- Evidence coverage: the proportion of predefined evidence points represented.
- Geographic-context coverage: whether relevant geographic contexts are represented.

## Research Safeguards

- Do not assume evidence from one geographic region is inherently more relevant.
- Distinguish geographic coverage from scientific quality and relevance.
- Record source URLs and retrieval decisions where available.
- Report negative and inconclusive results honestly.
- Claim improvements only when supported by evaluation.
- Document dataset limitations and the prototype's scope.

## Current Status

The initial project setup is complete. The retrieval system and evaluation dataset have not yet been implemented.
