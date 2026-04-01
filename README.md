# Data Visualization Portfolio

Applied statistical visualizations across real-world datasets, including healthcare, game strategy, and classification modeling. This portfolio focuses on using statistical methods and machine learning outputs to support interpretation and decision-making.

## Overview

This repository contains a collection of visualizations developed as part of academic and applied data science projects. The work emphasizes:

- Statistical testing and interpretation  
- Model evaluation and comparison  
- Clear visual communication of results  
- Use of real-world datasets  

The goal is to move beyond plotting and show how visualizations support analysis and conclusions.

---

## Hex Game Strategy Analysis

Statistical analysis of first-move strategy and game dynamics in 11x11 Hex. The dataset includes thousands of games and focuses on how early decisions impact outcomes.

### Methods
- Chi-square test for distribution of first moves  
- ANOVA for game length differences  
- Proportion tests for unbroken and near-unbroken chains  
- Move classification (Center, Edge, Corner)  

### Key Findings
- First moves are not randomly distributed  
- Center positions dominate early play  
- Certain opening moves lead to higher rates of near-unbroken chains  
- Move type affects both win probability and game length  

### Visualizations

![Chi-square](images/chisq.png)  
Result: First move selection is significantly non-uniform, indicating strong strategic preference.

![ANOVA](images/anova_1st.png)  
Result: Game length varies significantly based on opening move type.

![Proportion](images/catmovetype_nearunbroken.png)  
Result: Move categories show different probabilities of forming near-unbroken chains.

![Density](images/density.png)  
Result: Distribution of game lengths highlights differences across strategies.

---

## Multiple Sclerosis (MS) Prediction Analysis

Classification analysis using clinical and MRI features to predict progression to clinically definite multiple sclerosis (CDMS).

### Methods
- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  
- ROC curve analysis  
- Feature evaluation  

### Key Findings
- Random Forest achieved the strongest performance across models  
- Certain clinical features contribute more strongly to classification  
- Model comparison highlights trade-offs between interpretability and performance  

### Visualizations

![ROC Curve](images/roc.png)  
Result: Random Forest demonstrates the highest predictive performance based on ROC comparison.

![Confusion Matrix](images/confusion_matrix.png)  
Result: Classification results show model strengths in identifying positive cases.

---

## Cardiovascular Risk Analysis

Analysis of heart disease risk using clinical indicators from the UCI Cleveland dataset.

### Methods
- Logistic Regression baseline  
- Random Forest classification  
- ROC and confusion matrix evaluation  

### Key Findings
- Random Forest improves classification accuracy over baseline models  
- Feature patterns align with known clinical risk indicators  
- ROC analysis confirms improved model discrimination  

### Visualizations

![ROC Comparison](images/roc_comparison.png)  
Result: Random Forest outperforms Logistic Regression in predictive accuracy.

![Confusion Matrix](images/rf_confusion_matrix.png)  
Result: Improved classification of high-risk patients.

---

## Visualization Approach

All visualizations are designed with clarity and statistical interpretation in mind:

- Clean layout and readable structure  
- Consistent styling and formatting  
- Focus on highlighting statistical results  
- Designed for presentation and reporting contexts  

---

## Tools and Technologies

- Python: pandas, NumPy, scikit-learn, matplotlib  
- R: ggplot2, statistical testing, data analysis  
- Statistical Methods:  
  - Chi-square tests  
  - ANOVA  
  - Proportion tests  
  - ROC analysis  

---

## Repository Structure
