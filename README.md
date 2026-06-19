# Workshop: Speculative Decoding

Materials for the **Speculative Decoding** workshop — Nebius Academy (2026-06-19).

## Contents

- [`workshop.ipynb`](workshop.ipynb) — hands-on notebook for the workshop.
- `Speculative Decoding Workshop - Nebius Academy 260619.pptx` — presentation slides.

## About

Speculative decoding speeds up autoregressive LLM inference by using a small,
fast *draft* model to propose several tokens ahead, which the larger *target*
model then verifies in a single forward pass — accepting the correct prefix and
preserving the target model's output distribution.

## Getting started

Open the notebook in Jupyter or VS Code:

```bash
jupyter lab workshop.ipynb
```
