# Morning Agent – Macro State Engine

This project builds a daily macro risk and trade framework across:

- US & Canada yield curves
- G10 FX monitoring
- Event severity scoring
- Regime persistence statistics
- DV01 stress simulation
- FX market making simulation
- Constraint gating for trade ideas

The system is stateful: it stores historical slope metrics and computes rolling z-scores, volatility states, and empirical regime persistence probabilities.

Outputs:
- Excel Morning Brief (auto-generated)
- Predictive Outlook block
- Rates DV01 risk summary
- FX MM simulation
- Constraint-gated trade ideas

Architecture:
Python → Excel report → VBA formatting layer
