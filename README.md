# Dynamic Blockchain: Block Size and Monopolistic Auctions 🔗📊

This repository contains the experimental framework and codebase for my Master’s research at the Technion, focusing on optimizing Transaction Fee Mechanisms (TFM) and block size dynamics in Blockchain environments.

## 🌟 Research Overview
The research introduces **LOUM (Leave One oUt Monopolistic)**, an advanced auction mechanism designed for dynamic block size environments. The project addresses the trade-off between blockchain throughput and system stability, ensuring properties such as **DSIC (Dominant Strategy Incentive Compatibility)** and **MIC (Miner Incentive Compatibility)**.

## 🧪 Experimental Framework
The code in this repository implements a series of simulations and empirical analyses conducted on a **real-world dataset of Ethereum transactions**.

### Key Components:
- **LOUM Auction Implementation:** A Python-based realization of the Monopolistic Auction variation discussed in the thesis.
- **Dynamic Block Size Simulator:** Modeling how the system adapts to varying transaction demands while maintaining equilibrium.
- **Ethereum Data Pipeline:** Scripts for processing and analyzing historical Ethereum transaction data to validate the mechanism's performance.
- **Comparative Analysis:** Benchmarking LOUM against traditional EIP-1559 and standard Monopolistic auctions.

## 📈 Key Results
The experiments demonstrate:
- **Incentive Alignment:** Proof-of-concept that LOUM maintains DSIC* even under varying miner strategies.
- **Efficiency:** The mechanism successfully manages budget constraints while preventing fake transaction creation (Paranoid Miner scenario).
- **Real-world Applicability:** High-fidelity simulations using actual Ethereum network data.

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:** NumPy, Pandas (for data processing), Matplotlib/Seaborn (for result visualization)
- **Data Source:** Ethereum Mainnet transaction logs.

## 📖 Citation
If you use this code or refer to the research, please cite:
> **Levy, S. (2024). Dynamic Blockchain: Block Size and Monopolistic Auctions. Research Thesis, Technion - Israel Institute of Technology.**
