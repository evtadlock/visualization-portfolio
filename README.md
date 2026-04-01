# Data Visualization Portfolio

Collection of statistical visualizations focused on hypothesis testing, pattern analysis, and interpretation using real-world data.

Each project in this repository is self-contained and includes its own README with full methods, results, and explanations.

---

## Projects

### Hex Game Strategy Analysis

Statistical analysis of first-move strategy and game dynamics in 11x11 Hex using thousands of recorded games.

This project applies statistical testing to evaluate how early decisions influence outcomes and structural patterns in gameplay.

#### Methods
- Chi-square test on opening move distribution  
- ANOVA on game length differences  
- Proportion tests on unbroken and near-unbroken chains  
- Move classification (Center, Edge, Corner)  

#### Key Findings
- First moves are not randomly distributed  
- Center positions are used more frequently than edge or corner openings  
- Certain opening moves are associated with higher rates of near-unbroken chains  
- Move type affects both win probability and game length  

[View Project](./hex-game-analysis)

#### Visualizations

![Chi-square](hex-game-analysis/images/chisq.png)  
Result: First move selection is significantly non-uniform, indicating strategic preference.

![ANOVA](hex-game-analysis/images/anova_1st.png)  
Result: Game length varies based on opening move type.

![Proportion](hex-game-analysis/images/catmovetype_nearunbroken.png)  
Result: Move categories show different probabilities of forming near-unbroken chains.

![Density](hex-game-analysis/images/density.png)  
Result: Distribution of game lengths highlights variation across strategies.

---

## Tools

- R: ggplot2, statistical testing  
- Statistical methods:
  - Chi-square tests  
  - ANOVA  
  - Proportion tests  

---

## Repository Structure
