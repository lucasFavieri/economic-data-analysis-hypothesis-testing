# Economic Data Analysis: Global Digital Divide & Hypothesis Testing 🌍📊

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucasFavieri/marketing-analytics-ab-testing/blob/main/ab_testing_marketing_analysis.ipynb)

This project was developed during a **Mini-Hackathon** at Facultet (Porto). Using the **Quality of Government (QoG) Standard Dataset (2020)**, I performed inferential statistical analysis to investigate the socio-economic and institutional drivers behind global internet penetration.

## 🎯 Project Overview
The goal of this study is to move beyond descriptive statistics and use **statistical rigor** to test established socio-economic theories.

### 🧪 Hypotheses Tested:
1.  **Modernization Theory (Pearson Correlation):** Testing if national wealth (GDP) is the primary predictor of digital access.
2.  **Institutional Theory (Independent T-Test):** Analyzing if the "Rule of Law" significantly impacts the quality of digital infrastructure.
3.  **Democratic Transition Theory (Chi-Square):** Investigating the link between political freedom (Freedom House Status) and digital access.

## 🛠️ Tech Stack & Methods
- **Language:** Python
- **Libraries:** `pandas`, `numpy`, `scipy.stats`, `seaborn`, `matplotlib`.
- **Statistical Tests:** Pearson Correlation, Independent T-test, Chi-Square Test of Independence.
- **Data Source:** Quality of Government Institute (Cross-sectional data for year 2020).

## 📈 Key Insights & Results
* **The Wealth Factor:** Confirmed a very strong positive correlation ($r = 0.92$) between Log GDP and internet penetration.
* **The Governance Gap:** Nations with high-quality Rule of Law scores average **81%** internet access, compared to only **45%** in lower-quality governance environments.
* **Political Freedom:** The Chi-Square test ($\chi^2 = 40.52, p < 0.001$) revealed that "Free" countries are statistically much more likely to have high digital participation.

## 🚀 Recommendations
- **Beyond Hardware:** Digital development aid should be coupled with institutional and legal reforms to ensure long-term infrastructure sustainability.
- **Policy:** International initiatives should prioritize digital rights and "Open Internet" protocols, especially in regions with lower political freedom scores.

---
*Developed by [Lucas Favieri](https://github.com/lucasFavieri) as part of the Data Science Learning Path.*
