# Heart Attack Dataset Analysis

## Overview
Understanding the current trends of heart attacks in the dataset and analysing their relationship with demographic factors, lifestyle choices, and medical history using visualisations in Tableau.


## Tools
- Tableau

  
## Data Source
Indicators of Heart Disease (2022 UPDATE) from Kaggle  
Retrieved from: https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease/data


## Steps to Run the Project
**1. Download Dataset**
Download the file `BRFSS 2022 Indicators of Heart Disease Dataset.csv` from the `datasets` folder.

**2. Open Tableau Dashboard**
Download the file `Tableau Dashboard.twbx` from the `scripts` folder and open it using Tableau Desktop.  

> **Note:** A screenshot of the dashboard is also available in the `scripts` folder for quick review.

**3. Explore the Dashboard**
In Tableau, navigate to the **"ABAV Dashboard"** worksheet (second last sheet) to interact with the visualizations.

**4. Understand the Project**
Go to the **"ABAV Story"** worksheet (last sheet), which explains:
- Problem statement  
- Aim and objectives  
- Dataset
- Dashboard overview
- Dashboard insights  

> **Note:** A full video presentation is also available in the `video` folder for a more detailed explanation.


## Key Findings
- **Region**: Heart attack prevalence varies by region, with the highest in the Northeast (1.62%), followed by the Midwest, South, West, and US territories. These differences are likely influenced by socioeconomic and lifestyle factors.

- **Gender**: Males show a higher risk of having a heart attack than females in this population.

- **Age Group**: Generally, there is an upward trend in the number of individuals with heart attacks from younger to older age groups, with the highest count in individuals aged 79+

- **Body Health Conditions**: Individuals who experienced a heart attack had a slightly higher average BMI (29.32) compared to those without a heart attack (28.48). For those with a heart attack, they reported about 5 days of poor mental health and 9 days of poor physical health, while those without a heart attack reported roughly 4 days of poor physical and mental health. Average sleep was similar across both groups at around 7 hours per day. Overall, most body health measures were quite similar between the two groups, but there is a noticeable difference in poor physical health, suggesting it may be a contributing factor to heart attack risk.
  
- **Smoking**: Among individuals with heart attack, approximately 60% were current or former smokers and 40% were non-smokers, suggesting smoking may be associated with higher heart attack risk.
  
- **Angina (chest pain)**: Of the ~23,000 individuals with heart attack, 49% had angina and 51% did not, suggesting angina may not be a significant contributing factor given the near-equal split.
  
- **Arthritis (joint inflammation)**: 58% of individuals with heart attack had arthritis compared to 42% who did not, suggesting people with arthritis may have a slightly higher risk of heart attack.
  
- **Stroke**: Only 20% of individuals with heart attack had a prior stroke. This may be because heart attack and stroke share similar preventive measures, where individuals who experience a heart attack may adopt lifestyle changes that simultaneously reduce their stroke risk.
  
- **Alcohol consumption**: Among the ~21,000 individuals examined, 38% were drinkers and 62% were non-drinkers, possibly suggesting that alcohol consumption does not strongly contribute to heart attack risk, though this finding should be interpreted with caution.


## Insights
- **Insight 1 (Gender differences in risk factors)**: Among females with heart attack, 66% also had arthritis, which was the highest among all risk factors in the dashboard. This suggests a possible association between arthritis and heart attack female in this dataset. Among males with heart attack, 63% were current or former smokers, which was also the highest among all risk factors in the dashboard. This suggests smoking may be the main contributing risk factor for heart attack in males.

- **Insight 2 (Smoking increases co-occurring risk factors)**: Compared to non-smokers, individuals with heart attack who smoked showed higher rates of angina and arthritis. Smokers also reported more days of poor mental health and poor physical health on average. This suggests that smoking not only contributes to heart attack risk but also increases the likelihood of developing other related conditions.




