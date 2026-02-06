# Teaching-Method-Reward-Analysis
An R-based statistical report investigating how teaching methods and reward systems influence performance. Featuring a Two-Way ANOVA with replication, this project demonstrates data cleaning, hypothesis testing, and PDF report generation using R Markdown.

# Analysis of Teaching Methods and Reward Systems on Patient Skills

## 🏥 Project Overview
This project investigates the effectiveness of medical teaching strategies and incentive structures. By applying a **Two-Way Factorial ANOVA**, we analyze how three different teaching methods and three reward systems (None, Praise, Tangible) impact patient skill acquisition scores.

## 📊 Statistical Analysis
The study utilizes a factorial design with replication ($n=4$ per cell) to evaluate:
1. **Main Effect of Teaching Method:** Does the delivery style matter?
2. **Main Effect of Reward System:** Do incentives drive performance?
3. **Interaction Effect:** Does the best teaching method change depending on the reward?



## 🛠 Tech Stack
- **Environment:** RStudio
- **Formatting:** R Markdown & LaTeX
- **Statistical Test:** Factorial ANOVA (`aov`)
- **Visuals:** Interaction plots for behavioral data

## 📂 Repository Contents
- `Teaching-Method-Reward-Analysis`: Complete source code and data entry.
- `Teaching-Method-Reward-Analysis.Rmd`: The finalized PDF report with interpretations.

## 📝 Key Findings
The analysis identified highly significant p-values for both **Method** and **Rewards**, while confirming that the **Interaction** was not significant ($p > 0.05$), suggesting that the chosen teaching method's success is stable across different incentive environments.
