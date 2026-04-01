# Data Visualization Portfolio

This portfolio demonstrates how statistical analysis and modeling are used to answer real-world questions through data.

Rather than presenting visualizations alone, each project is structured around:
- A clear question  
- A defined analytical approach  
- Measurable results  
- Interpretation and implications  

---

## Projects

---

### Fundraising Analytics (Causal Inference and Prediction)

**Question:**  
Does participant connection type influence fundraising outcomes, and can large donations be predicted?

**Approach:**
- Propensity score matching to estimate treatment effects  
- Classification models (Random Forest, XGBoost) to predict large gifts  
- Distribution analysis to examine donation behavior  
- Monte Carlo simulation for uncertainty and forecasting  

**Results:**
- A strong treatment effect was observed: participants with close connections raised significantly more  
- Donation amounts follow a heavy-tailed distribution, with a small number of participants contributing disproportionately  
- Predictive models achieved moderate performance (AUC ~0.67–0.69)  
- Simulation results show substantial variability in long-term fundraising outcomes  

**Interpretation:**
Fundraising performance is driven by both participant relationships and a small subset of high-value contributors. Predictive modeling can help identify these contributors, while simulation highlights uncertainty in future projections.

📂 [View Project](./Fundraising%20Analytics%20Visualization)

---

### Hex Game Strategy Analysis (Statistical Testing)

**Question:**  
Do opening moves in Hex influence win probability and game structure?

**Approach:**
- Chi-square test to evaluate first move distribution  
- ANOVA to assess differences in win outcomes  
- Proportion tests for chain formation patterns  
- Density analysis for game length variation  

**Results:**
- First moves are not uniformly distributed across the board  
- Certain opening moves are associated with higher win counts  
- Chain formation (unbroken and near-unbroken) varies by move type  
- Game length differs depending on opening strategy  

**Interpretation:**
Opening decisions in Hex are not random and have measurable effects on both outcomes and game dynamics. Strategic positioning early in the game influences both success rates and structural patterns.

📂 [View Project](./hex-game-analysis)

---

### Research Posters

Academic and conference-style visualizations summarizing statistical findings and research results.

📂 [View Posters](./posters)

---

## Skills Demonstrated

- Statistical inference (chi-square, ANOVA, proportion tests)  
- Causal inference (propensity score matching)  
- Predictive modeling and evaluation  
- Simulation and uncertainty analysis  
- Data visualization for decision-making  

---

## Tools Used

- R (ggplot2, dplyr, statistical testing)  
- Python (scikit-learn, matplotlib, seaborn)  

---

## Summary

This portfolio emphasizes using data to answer meaningful questions and communicate results clearly, rather than presenting visualizations in isolation.
