## Hi — I design quantitative investment models

I'm an active investor who builds rules-based frameworks for equity selection and trade timing. I design the models end-to-end — the factors, the weighting and scoring logic, the valuation methods, and the decision rules — and I verify that the logic is sound. The Python implementations are done with AI assistance from my written specifications; my role on the code side is specification, review, and verification.

One of those models is public here:

### 📊 [MERIDIAN — Equity Evaluation Framework](https://github.com/jacobbuildmodel/meridian)
A fundamentals-first, two-axis (**quality × valuation**) model for equity selection. It classifies each company into one of four business archetypes, scores quality **multiplicatively** (one fatal flaw drives the score to zero), extracts the growth rate the current price is implying via a reverse-DCF, and reads the result off a Quality × Valuation grid. Price is never a signal in the score — a great business at an infeasible price is a *watch*, not a *buy*.

---

*The project leads with the model design and reasoning; its README is honest about what has and hasn't been formally validated. Nothing in these repositories is financial advice.*
