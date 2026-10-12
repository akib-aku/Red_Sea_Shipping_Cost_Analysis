# 🌊 Red Sea & Hormuz Risk Lab
Companion interactive research notebook for the documentary-style video analysis: **"The Strait That Costs You $105"**.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akib-aku/Red_Sea_Shipping_Cost_Analysis/blob/main/Red_Sea_Risk_Lab.ipynb)

---

## 📌 Overview
This repository contains an advanced quantitative modeling lab exploring geopolitical supply chain risks, maritime trade choke points, and insurance arbitrage. 

Every number marked as an **ASSUMPTION** in this notebook is a modeling choice, not a measured fact. The goal of this tool is to let you change the variables and test the resilience of global shipping economics.

---

## 🛠️ Core Analytical Modules Inside the Notebook:

1. **Poisson Distribution & Overdispersion Analysis:** 
   - Simulates weekly attack probabilities ($\lambda = 2.4$).
   - Demonstrates why real-world conflict exhibits high overdispersion ($\text{Var}/\text{Mean} = 2.7$) compared to pure Poisson models.

2. **Interactive Bayesian Regime Updater:**
   - Multi-stage probability updater incorporating evidence from the Mokha/Perim seizure and Yanbu energy infrastructure strikes.
   - Includes interactive sliders to test custom subjective priors.

3. **Regime Mixture Model:**
   - Contrasts quiet vs. campaign regimes to highlight how tail-risk probabilities surge in active conflict states.

4. **Historical Lull Backtest:**
   - Analyzes the statistical anomaly of the late 2024 / early 2025 quiet stretch against a constant campaign rate.

5. **Suez vs. Cape of Good Hope Cost Calculator:**
   - Evaluates per-transit expected physical losses against 0.7% war-risk insurance premiums and $1M+ Cape diversion fuel/OPEX penalties.
   - Includes a sensitivity heatmap comparing blockade risk probabilities against insurance rates.

---

## 🚀 How to Use
Click the badge above to open the notebook directly in **Google Colab**, or click the link below:
👉 [Run Red Sea Risk Lab in Google Colab](https://colab.research.google.com/github/akib-aku/Red_Sea_Shipping_Cost_Analysis/blob/main/Red_Sea_Risk_Lab.ipynb)

*Adjust the sliders, break the assumptions, and decide whether you would still send the ship.*
