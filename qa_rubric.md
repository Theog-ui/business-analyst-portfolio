# QA Rubric (10 dimensions, weighted)

| Dimension | Weight | 0 - Fails | 1 - Weak | 2 - Good | 3 - Excellent |
|---|---|---|---|---|---|
| Factual accuracy | 0.18 | Material errors | Minor inaccuracies | Mostly correct | Fully correct with references |
| Logical consistency | 0.12 | Contradictions | Leaps in reasoning | Mostly consistent | Tight, traceable logic |
| Structure & formatting | 0.08 | Disorganized | Partially structured | Clear | Clear + follows template (TSV/JSON/MD) |
| Relevance to goal | 0.10 | Off‑topic | Partially relevant | On‑topic | Laser‑focused |
| Actionability | 0.14 | No next steps | Vague steps | Concrete steps | Steps with owners, dates, metrics |
| Quantitative reasoning | 0.10 | No numbers | Loose numbers | Formulas/benchmarks | Sound models; sensitivity/edge cases |
| Risk identification | 0.08 | None | Basic | Realistic | With mitigations & monitoring |
| Constraint use | 0.06 | Ignores constraints | Mentions only | Applies constraints | Applies & justifies trade‑offs |
| Completeness | 0.07 | Missing sections | Minor gaps | Complete | Complete + alternatives |
| Tone & clarity | 0.07 | Confusing | Mostly clear | Clear | Executive‑ready |

**Scoring** = sum(weight × score/3) × 100; **Pass** ≥ 80, with no dimension at 0.
