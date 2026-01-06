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

[See in Statistics](https://github.com/ayabelarbi/cryptofinance/blob/488c2a74de0cb2980bc2e62821da9c0c35f15eb8/mining-strategy/Strategy_1_Plus_2.ipynb)
➡️  [Google Collab link - Strategy_1plus2.ipynb](https://colab.research.google.com/drive/19TyU__2lcfo9NBNDaUpg-BtOxzkiMAsV?usp=sharing)

---

### 2.2 Selfish mining

> **Status:** ⏳ not started

This part will study the classical selfish mining strategy and its dependence on:
- hashing power `q`
- network connectivity parameter `g`

---

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
