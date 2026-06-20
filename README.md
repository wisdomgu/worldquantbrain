# WorldQuant BRAIN Research Portfolio

## Overview

Independent quantitative researcher on the WorldQuant BRAIN platform. Developed and validated systematic trading strategies (alphas) using statistical and machine learning methods.

## Key Achievements

- **Silver Level** – Acquired 5,000 Points
- **5 Validated Alphas** – All passed Fitness > 1.0 threshold
- **Best Sharpe: 1.97** – Risk-adjusted return metric
- **Lowest Turnover: 1.62%** – Ultra-low transaction costs
- **100+ Simulations Run** – Systematic hypothesis testing
- **~5% Success Rate** – Industry-standard signal discovery rate

## Methodology

### Factor Categories Tested

| Category | Result |
|----------|--------|
| **Balance Sheet Leverage** (liabilities/assets, assets/equity) | ✅ Strong positive alpha |
| **Momentum/Reversal** | ✅ Positive alpha |
| **Cashflow Ratios** | ❌ Negative or low |
| **Analyst Revisions** | ❌ No predictive signal |
| **Implied Volatility** | ❌ No predictive signal |
| **Social Sentiment** | ❌ No predictive signal |
| **Event-Driven (Volume + Reversal)** | 🟡 Near-miss (Fitness 0.95) |

### Key Learnings

- The most robust signals are **simple, economically intuitive, and low-turnover**
- **Turnover matters more than Sharpe** for Fitness
- Leverage factors outperform across multiple variations
- **95% of hypotheses fail** – this is expected and normal

## Alpha Performance

| Alpha | Sharpe | Turnover | Fitness | Status |
|-------|--------|----------|---------|--------|
| Leverage Factor (liabilities/assets) | 1.81 | 1.69% | 1.52 | ✅ Validated |
| Assets/Equity | 1.48 | 1.88% | 1.12 | ✅ Validated |
| Leverage (Decay=3) | 1.90 | 21.31% | 1.19 | ✅ Validated |
| Leverage (Decay=2) | 1.97 | 40.43% | 1.02 | ✅ Validated |
| Momentum/Reversal | 1.46 | 47.63% | 1.00 | ✅ Validated |

*Table: Performance metrics for all validated alphas.*

## Screenshots

![IS Summary Example](<img width="1071" height="452" alt="image" src="https://github.com/user-attachments/assets/b935be78-b85c-4f42-a218-25a5e66e9952" />
)

*Example of a validated alpha's IS Summary showing Sharpe, Turnover, and Fitness.*

## Validation Process

1. **Hypothesis generation** – Based on economic intuition and academic literature
2. **Expression coding** – WorldQuant BRAIN Fast Expression language
3. **Backtesting** – Historical simulation on U.S. equities (TOP3000)
4. **Fitness evaluation** – Sharpe / sqrt(Turnover) > 1.0 required
5. **Self-correlation check** – Must be below 0.7 to avoid redundancy
6. **Submission** – Passes platform validation and becomes part of portfolio

## Tools & Environment

- **Platform**: WorldQuant BRAIN
- **Language**: Fast Expression language
- **Universe**: TOP3000 U.S. equities
- **Neutralization**: Subindustry (primary), also tested Industry and Sector
- **Truncation**: 0.08 (primary), tested 0.05
- **Decay**: 0, 2, 3 (tested variations)

## Independent Research Context

This work is part of my broader quantitative research:

- **3 research papers** in algorithmic finance (2 accepted)
- **Regim** – Full-stack quant research platform with 11 REST endpoints
- **École Polytechnique engagement** – Peer-level dialogue with a researcher

## Related Work

- [Regim Platform]([https://regim.vercel.app](https://regim-dashboard.vercel.app/))
- [Paper: Regime Survival Forecasting for Adaptive Execution](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6763019)
- [LinkedIn Profile](https://www.linkedin.com/in/satish-garg/)

---

*Repository maintained as a portfolio of quant research work. Alpha expressions are proprietary and not included.*
