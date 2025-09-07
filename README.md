# Gender and Trust in the Police  
*An analysis using the Crime Survey for England and Wales (2023–2024)*  

## Overview  
This project investigates the relationship between **gender** and **trust in the police** among non-victims, using data from the **Crime Survey for England and Wales (CSEW 2023–2024)**. Trust in the police is a central measure of institutional legitimacy, and understanding demographic differences helps highlight gaps in public confidence.  

The study applies survey design methods and statistical testing to explore whether men and women differ in their reported trust in the police, independent of direct victimisation experiences.  

---

## Methods  
- **Data Source:** Crime Survey for England and Wales (2023–2024), 30,847 respondents.  
- **Independent Variable:** Gender (`sex`)  
- **Dependent Variable:** Trust in the police (`poltrst`)  
  - Original 4-point Likert scale recoded into a binary measure (high trust vs. low trust)  
- **Statistical Technique:** Chi-squared test of independence  
- **Software & Libraries:** R (`haven`, `dplyr`, `janitor`)  

---

## Key Findings  
- No statistically significant relationship between gender and trust in the police among non-victims.  
- Both men and women reported nearly identical levels of high trust (72.4% vs. 72.9%).  
- Chi-squared test: χ² = 0.52, p = 0.47 → insufficient evidence to reject the null hypothesis.  

---

## Limitations  
- Binary recoding may obscure subtle differences (e.g., “a lot” vs. “a fair amount” of trust).  
- Chi-squared test does not account for potential confounders like age or ethnicity.  
- CSEW excludes institutionalised populations (e.g., prisoners), limiting representativeness.  

---

## Policy Implications  
- Gender alone is a weak predictor of police trust among non-victims.  
- Improvements to survey design
