## Hi — I design quantitative investment models

I'm an active investor who builds rules-based frameworks for equity selection and trade timing. I design the models end-to-end — the factors, the weighting and scoring logic, the valuation methods, and the decision rules — and I verify that the logic is sound. The Python implementations are done with AI assistance from my written specifications; my role on the code side is specification, review, and verification.

Two of those models are public here:

### 📊 [Equity Evaluation Framework](https://github.com/jacobbuildmodel/equity-evaluation-framework)
A fundamentals-first, two-axis (**quality × valuation**) model for equity selection. It classifies each company into one of four business archetypes, scores quality **multiplicatively** (one fatal flaw drives the score to zero), extracts the growth rate the current price is implying via a reverse-DCF, and reads the result off a Quality × Valuation grid. Price is never a signal in the score — a great business at an infeasible price is a *watch*, not a *buy*.

### ⏱️ [Pre-Earnings Decision Engine](https://github.com/jacobbuildmodel/pre-earnings-decision-engine)
A disciplined, anti-overfitting decision system for the days before an earnings release. A sealed directional-sign classifier plus a calculated-risk payoff layer, wrapped in hard gates, worst-case checks, and a governance model that decides what is even *allowed* to change. Built to answer **"no trade"** most of the time, and validated forward — never by tuning on past trades.

---

*Both projects lead with the model design and reasoning; each README is honest about what has and hasn't been formally validated. Nothing in these repositories is financial advice.*
