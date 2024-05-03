# Shark-Analysis-Team
**Project: Analyzing Patterns in Shark Attack Incidents: A Global Perspective**

## Team Members
- Courtney Cole
- Mohamed Ibrahim
- Albert Lee
- Jay Singh

## Introduction
This project undertakes a detailed statistical exploration into the patterns of shark attacks across the globe. Our aim is to understand the factors influencing the occurrence and outcomes of shark encounters, thereby contributing to better preventative strategies and public awareness.

## Table of Contents
- [Team Members](#team-members)
- [Introduction](#introduction)
- [File Structure](#file-structure)
- [Research Questions](#research-questions)
- [Results](#results)
- [Discussion](#discussion)
- [Conclusions](#conclusions)
- [Acknowledgments](#acknowledgments)
- [References](#references)
- [Repository](#repository)

## File Structure
- **API Retrieval Script**: Implemented with `requests.get()`. Did not require an API key.
- **Data Cleaning Notebook**: `Shark Data_1.ipynb` - Cells 1 to 57 cover data preprocessing.
- **Analysis Notebooks**:
  - Courtney: `Shark Data_1.ipynb` - Starting from cell 58 to the end.
  - Mohamed: `Shark Data_Mohamed.ipynb` - Starting from cell 58 to the end.
  - Albert: `seasonal_patterns-albert.ipynb` - Entire notebook.
  - Jay: `Shark Data.ipynb` - Starting from cell 67 to the end.


## Research Questions
### 1. Seasonal Patterns: Are attacks more frequent during certain months or seasons? (Albert)
**Shark Attacks by Month:**
![Shark Attacks by Month](Data-Visualization/Seasonal-Patterns-Albert/shark_attacks_by_month.png "Shark Attacks by Month")
Analysis of shark attack frequency reveals significant seasonal variation, peaking in the warmer months. This trend correlates with increased water temperatures and coastal activities, particularly from June through September.

**Shark Attacks by Season:**
![Shark Attacks by Season](images/shark_attacks_by_season.png "Shark Attacks by Season")
Summer is the most dangerous season for shark attacks, reflecting increased human activity in waters. Spring and fall show moderate levels, while winter has the lowest incidence, correlating with colder water temperatures and reduced water-related activities.

**Time Series Analysis and 5-Year Moving Average:**
![Time Series Analysis](images/time_series_analysis.png "Time Series Analysis")
From a historical perspective, shark attacks were minimal from 1880 to 1920, increasing with coastal population growth and enhanced reporting. The 5-year moving average shows a general upward trend, peaking shortly after 2000. Post-2015, there's a decline, likely due to improved safety measures.

**Linear Regression:**
![Linear Regression](images/linear_regression.png "Linear Regression")
The model indicates a general increase in shark attacks over time, supported by a strong positive correlation between time and attack numbers. This trend aligns with observed peaks and historical data trends.

### 2. Species Involvement: Which shark species are most involved in attacks, and are some more likely to cause severe injuries? (Jay)
**Which Shark Species Are Most Involved:**
![Which Shark Species Are Most Involved](images/shark_species_involved.png "Which Shark Species Are Most Involved")
White Sharks lead in attack incidents, followed by Tiger and Bull Sharks. Each species' behavior contributes differently to attack scenarios and injury severities.

**Do Shark Attacks Leave Severe Injuries:**
![Shark Attack Injury Severity](images/shark_attack_severity.png "Do Shark Attacks Leave Severe Injuries")
While most shark attacks are not severe, a significant minority lead to serious injuries, highlighting the unpredictable nature of these encounters.

### 3. Activities Leading to Attacks: Is there a relationship between certain activities and the likelihood of an attack? (Courtney)
**Number of Shark Attacks by Activity:**
![Number of Shark Attacks by Activity](images/shark_attacks_by_activity.png "Number of Shark Attacks by Activity")
Surfing, swimming, and spearfishing are the activities most associated with shark attacks. The data suggests that prolonged exposure in shark-favored waters increases the risk of attacks.

**Surfing Deep Dive: Provoked v. Unprovoked:**
![Surfing Provoked vs Unprovoked](images/surfing_provoked_unprovoked.png "Surfing Deep Dive: Provoked v. Unprovoked")
The vast majority of shark attacks on surfers are unprovoked, emphasizing the inherent risks of surfing in shark-patrolled waters.

### 4. Geographic Hotspots: Which locations are more prone to attacks, and why? (Mohamed)
**Attacks per Country:**
![Attacks per Country](images/attacks_per_country.png "Attacks per Country")
Analysis of shark attack data identifies the USA, Australia, and South Africa as regions with the highest incidences, influenced by factors such as beach-going populations and marine biodiversity.

## Results
Our analyses have provided several key insights into shark attack patterns, which are visually represented in the images above. Each member's contribution has highlighted different aspects of shark behavior and human interaction.

## Discussion
The findings from our research offer important implications for public safety and shark conservation efforts. Limitations in the data were addressed, and potential for further detailed studies were identified.

## Conclusions
In conclusion, our research sheds light on the complex nature of shark-human interactions and provides a basis for further studies and safety strategies. The collective efforts of our team have highlighted significant patterns that could aid in reducing shark attack incidents.

## Acknowledgments
We thank our instructor, Benjamen Alford, at the KU Data Analytics Boot Camp for his support and guidance throughout this project.

## References 🌐
- Global Shark Attack Dataset: [Link to Dataset](https://public.opendatasoft.com/explore/dataset/global-shark-attack/table/?flg=en-us&disjunctive.country&disjunctive.area&disjunctive.activity&dataChart)

## Repository 🌐

All code and datasets are maintained in the [Shark-Analysis-Team GitHub Repository](https://github.com/CourtneyCole123/Shark-Analysis-Team/tree/main).
