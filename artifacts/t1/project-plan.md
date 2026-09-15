# T1 Project Plan

## Project Goal

Develop a clear and reproducible research workflow for comparing three familiar asset classes represented by illustrative ETFs: `SPY` (US equities), `TLT` (long-term US Treasury bonds), and `GLD` (gold). This tutorial (T1) creates a written plan; later tutorials are expected to use the same repository to design a bounded analysis task and organize a verifiable agent workflow.

## Available Data

- `data/etf_snapshot.csv` — one row per illustrative ETF (`SPY`, `TLT`, `GLD`) with `expected_return_pct`, `volatility_pct`, `max_drawdown_pct`, and `expense_ratio_pct`.
- `data/data_dictionary.md` — explains each column's meaning and unit and documents dataset limitations.
- The dataset is synthetic teaching data: it is deliberately small and fixed, so no download or data-cleaning step is required for the tutorials.

## Expected Final Deliverable

The final deliverable of the project is a reproducible, verifiable comparison of the three asset classes, produced by a later, planned analysis. This T1 plan is the starting deliverable: a written project plan that later tutorials will build on when they design the bounded analysis task and organize the verifiable agent workflow.

## Three Project Milestones

1. **T1 — Project plan and versioning:** Create this written project plan, then have the student review and save it with Git. JiuWenSwarm does not commit or push during T1.
2. **T2 — Analysis design:** Design a bounded analysis task that uses the ETF snapshot data (planned work, not yet performed).
3. **T3 — Verifiable agent workflow:** Organize an agent workflow that executes the designed analysis and verifies the results (planned work, not yet performed).

## One Data Limitation

All numeric values in `etf_snapshot.csv` are synthetic teaching assumptions, not live quotations, verified historical estimates, or forecasts. The dataset also omits correlations, taxes, transaction costs, liquidity, currency exposure, and investor-specific constraints, so it must not be used as investment advice or as the basis for a real investment decision.

## Next Action

Have the student review this plan and commit it with Git. Afterward, proceed to the later tutorials that design the bounded analysis task and organize the verifiable agent workflow.
