# Gemma 4 E4B Extreme Benchmark

**The most thorough public stress-test of Google's new 4B-parameter multimodal model (gemma4:e4b in Ollama)**

Tested locally with pure Ollama (no tools, no vision for these runs).  
**Verdict:** This 4B model is *shockingly* good — it beats many older 7B–13B models on instruction following, coding, reasoning, and creativity.

## Results Summary

### Round 1 (10 classic tests) — Average: **9.65 / 10**
| Prompt | Score | Notes |
|--------|-------|-------|
| 1. Self-knowledge | 8.5 | Perfect intro |
| 2. Bat & Ball | 10 | Flawless CoT |
| 3. 3 Switches | 10 | Textbook perfect |
| 4. Apples math | 9 | Smart ambiguity handling |
| 5. LCS coding | 10 | Full DP + backtracking |
| 6. Sci-fi story | 9 | Clever word dodging |
| 7. JSON extraction | 10 | Perfect |
| 8. Multilingual + culture | 10 | Insightful Japanese analysis |
| 9. 12-item memory | 10 | Perfect recall |
| 10. Sarcastic Robot | 10 | Hit every constraint |

### Round 2 (10 brutal tests) — Average: **9.45 / 10**
| Prompt | Score | Notes |
|--------|-------|-------|
| 1. Agentic planning | 6 | Hallucinated future data (expected) |
| 2. AIME math | 10 | Perfect algebra |
| 3. Few-shot cipher | 10 | Instant pattern recognition |
| 4. No-'e' + alliteration story | 10 | **God-tier** constraint following |
| 5. Self-reflection error | 10 | Perfect metacognition |
| 6. SparseMatrix class | 10 | Production-ready code |
| 7. 15-item long-context | 10 | Flawless |
| 8. Korean + cultural nuance | 10 | Deep insight |
| 9. Contradiction override | 10 | Masterful rule handling |
| 10. Iambic pentameter role-play | 9.5 | Only tiny meter wobble |

**Overall:** 9.55/10 — One of the strongest ~4B models ever released.

Full raw prompts + outputs are in the `prompts/` and `results/` folders.

## Why this matters
Gemma 4 E4B proves that small, on-device models can be *actually useful* for serious work. This repo lets the world see exactly how good (or where it still cracks) under extreme pressure.

Star this repo if you run local models!
