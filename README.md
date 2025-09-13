# LinkedIn Network Analysis 📊

This project analyzes LinkedIn connection data of a student network using **Python, Graph Theory, and Statistical Methods**.  
The goal was to uncover **patterns, influencers, and insights** from real-world social connections.

---

## Project Overview
- **Dataset**: JSON files containing user degrees and adjacency lists
- **Size**: 28,117 individuals, ~199,770 total connections
- **Methods Used**:
  - Data cleaning & preprocessing (duplicates, nulls, inconsistent formats)
  - Graph construction using adjacency lists
  - Degree distribution, average/median/mode analysis
  - Random Walk and Pruned Path algorithms
  - Visualization of network and influencers

---

## Key Insights
- **Skewed Network**: Most users had very few connections (mode = 1), while a small fraction dominated outreach.
- **Top Influencers**: Identified super-connectors with >4,000 connections.
- **Efficient Routes**: Pruned paths revealed short, stable, and strong connection chains.
- **Community Patterns**: Denser sub-networks showed centralized connectivity.

---

## Tech Stack
- **Python**
- **Pandas, NumPy**
- **NetworkX**
- **Matplotlib / Seaborn**
- **Graph Theory & Statistics**

---

