# Data Dictionary — scenarios.tsv

| Column | Type | Description |
|---|---|---|
| id | string | Unique scenario ID (S1..Sn) |
| domain | enum | Finance, E‑commerce, Operations, Policy, People Ops, etc. |
| scenario_title | string | Short title |
| scenario | text | The business situation to reason about |
| inputs | text | Key numbers or facts provided |
| constraints | text | Limits, rules, or requirements |
| acceptance_criteria | text | What a good answer must include |
| evaluation_dimensions | text | Rubric dimensions to emphasize |
| edge_cases | text | Non‑obvious situations to handle |
