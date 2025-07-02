# LLM-Cognitive-Model-Translation

This repository accompanies our BRIMS 2025 paper on using large language models (LLMs) to translate cognitive models between symbolic architectures, specifically Soar and ACT-R.

## 🧠 Overview

We explore how LLMs (e.g., GPT-4o, ChatGPT 3.5) can:

- Translate production rules and model structure from Soar to ACT-R and vice versa.
- Generate initialization, procedural, and debugging prompts for symbolic code.
- Scaffold model creation through HITL (human-in-the-loop) prompting strategies.

The counting task (from 1 to 6) is used as a canonical example to evaluate generation quality and structure alignment across architectures.

## 📂 Contents

### `/models`

- `count.soar` – A complete Soar model that counts from 1 to 6 using propose/apply/detect rules.
- `count.lisp` – An ACT-R implementation of the same behavior, using declarative chaining.
- `count_phase_1` – Intermediate variants or WIP versions (see notes inside).

### `/prompts`

Prompt engineering logs across multiple architectures and LLM variants:

- GPT-4o and GPT-3.5 (Wu, Parth, etc.)
- Soar and ACT-R prompt templates
- Transcripts of model outputs and refinements


