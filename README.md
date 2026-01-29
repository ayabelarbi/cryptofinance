# Cryptofinance

A comprehensive study of Bitcoin mining strategies, blockchain consensus mechanisms, and cryptographic hash functions.

## 📋 Project Overview

This project implements and analyzes various aspects of cryptocurrency mining, including statistical analysis of hash functions, mining strategy simulations, and blockchain security thresholds. The work is based on practical exercises in cryptofinance and blockchain technology.

## 🗂️ Repository Structure

```
Cryptofinance/
├── statistics/          # Statistical analysis of hash functions and proof-of-work
├── mining-strategy/     # Mining strategy simulations and optimizations
├── docs/               # Documentation and theoretical analysis
└── README.md           # This file
```

## 📚 Completed Sections

### 1. Statistics
- **1.1 Hash Function Distribution**: Analysis of hash function uniformity using statistical tests
- **1.2 Proof-of-Work Duration**: Empirical validation of exponential distribution in mining times

### 2. Mining Strategies
- **2.1 Strategy 1+2 Simulation**: Numerical evaluation and comparison with theoretical formulas
- **2.2 Selfish Mining**: Performance analysis with parameters (q, γ) representing hashing power and connectivity
- **2.3 Optimal Selfish Mining**: Dynamic decision-making based on fork states (a, h)

### 3. Bitcoin Thresholds
- **3.1 Orphan Block Mining**: Determination of profitability thresholds for mining on orphan blocks
- **3.2 Block Withholding**: Analysis of rational miner behavior with zero connectivity (γ = 0)

## 🚧 Work in Progress

### 4. Advanced Topics (Bonus)
- **4.1 Double-Spending Attacks**: Framework for repeated attack scenarios
- **4.2 Ethereum Commitment Attacks**: Implementation of research from [arXiv:2407.19479](https://arxiv.org/abs/2407.19479)

## 🛠️ Technologies Used

- **Python 3.x**: Main programming language
- **Jupyter Notebook**: Interactive development and visualization
- **NumPy/SciPy**: Statistical analysis and numerical computations
- **Matplotlib**: Data visualization and plotting

## 📊 Key Concepts Explored

- **Hash Functions**: Uniformity testing and cryptographic properties
- **Proof-of-Work**: Mining difficulty and solution distribution
- **Selfish Mining**: Strategic blockchain manipulation
- **Game Theory**: Rational miner behavior and incentive structures
- **Blockchain Security**: Attack vectors and defense mechanisms

## 🔬 Methodology

Each section combines:
1. **Theoretical Analysis**: Mathematical foundations and formulas
2. **Simulation**: Numerical experiments and Monte Carlo methods
3. **Visualization**: Graphs and plots for result interpretation
4. **Comparison**: Empirical results vs. theoretical predictions

## 📈 Results and Findings

Detailed results and analysis are available in the Jupyter notebooks within each respective directory. Key findings include:

- Validation of exponential distribution in proof-of-work mining times
- Identification of profitability thresholds for selfish mining strategies
- Analysis of connectivity impact on mining strategy effectiveness

## 🤝 Collaboration

This project was developed as part of a cryptofinance course, with collaborative work on the foundational implementations and individual extensions for advanced topics.

## 📖 References

- Bitcoin Whitepaper: Nakamoto, S. (2008)
- Selfish Mining: Eyal, I., & Sirer, E. G. (2014)
- Blockchain Security and Game Theory research papers

## 📝 License

This project is for educational purposes as part of academic coursework.

## 👤 Author

Aline - [GitHub Profile](https://github.com/alineuh)

---

*Last updated: January 2026*
