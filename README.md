# Cryptofinance 
---
## Part 1 — Statistics
> **Status:** ✅ completed

[See in Statistics](https://github.com/ayabelarbi/cryptofinance/blob/dfb1758dc10742593828faa051207f7fbe76980e/statistics/Cyptofinance_1.ipynb)

---
## Part 2 — Mining Strategies

This part studies different mining strategies and their profitability.

### 2.1 Strategy 1+2 (block withholding)

> **Status:** ✅ completed

- Simulation of strategy 1+2
- Monte Carlo estimation of long-run revenue rate
- Comparison with the theoretical formula
- Identification of the profitability threshold

[See in Mining-strategy](https://github.com/ayabelarbi/cryptofinance/blob/488c2a74de0cb2980bc2e62821da9c0c35f15eb8/mining-strategy/Strategy_1_Plus_2.ipynb)

➡️[Google Collab link - Strategy_1plus2.ipynb](https://colab.research.google.com/drive/19TyU__2lcfo9NBNDaUpg-BtOxzkiMAsV?usp=sharing)

---

### 2.2 Selfish mining

> **Status:** ✅ completed

This section analyzes the classical Selfish Mining (SM1) strategy and its dependence on:
- **Hashing power `q`**: Fraction of total network hash power
- **Network connectivity parameter `γ`**: Influence during blockchain ties (0 ≤ γ ≤ 1)

**Key achievements:**
- Implementation of theoretical formulas (Eyal & Sirer 2014)
- Generation of **(q, γ) profitability maps** showing regions where SM is more profitable than honest mining
- **Threshold analysis** revealing q*(γ): profitability threshold decreases from 33.3% (γ=0) to ~0% (γ=1)
- **Comparison with Strategy 1+2**: SM has 8-16 percentage points lower threshold and 4-8× higher maximum gains
- **Security analysis**: Identification of three zones (safe, marginal, dangerous) and implications for Bitcoin's incentive compatibility
- **Comprehensive conclusions**: Network connectivity is the dominant attack vector; protocol modifications are necessary

**Main finding:** Selfish Mining becomes profitable at 25-33% hash power (depending on connectivity), significantly more dangerous than Strategy 1+2 (41.4% threshold).

[See in Mining-strategy](https://github.com/ayabelarbi/cryptofinance/blob/main/mining-strategy/Section_2_2_Selfish_Mining.ipynb)

### 2.3 Optimal selfish mining

> **Status:** ⏳ not started

This part will analyze optimal decisions as a function of:
- `a`: number of blocks mined by the attacker
- `h`: number of blocks mined by honest miners

---

## Part 3 — Bitcoin Thresholds

> **Status:** ⏳ in progress

This part studies incentive thresholds for rational miners, including:
- mining on orphan blocks
- incentives to reveal or withhold blocks
- effects of connectivity and hashing power

---

## Notes

- All simulations are implemented in Python.
- Notebooks are designed to be readable and reproducible.
- The main performance metric is the long-run revenue rate  
  \(\gamma = \mathbb{E}[G] / \mathbb{E}[H]\).

---
