# Cybersecurity Threats Analysis

## How to View
View the report here: [Cybersecurity Threats Analysis](https://tobitob708.github.io/cybersecurity-threats-analysis/cybersecurity-threat-analysis.html)

## Introduction
This project was developed as the **final project for MXB262 Visualising Data** at QUT.  
The dataset was sourced from **Kaggle** and covers global cybersecurity incidents from **2015–2024**, focusing on attack types, financial losses, and resolution times.  

## Dataset Description
The dataset used in this report is “🌐 Global Cybersecurity Threats (2015-2024)” by Atharva Soundankar, sourced from Kaggle (https://www.kaggle.com/datasets/atharvasoundankar/global-cybersecurity-threats-2015-2024).
The dataset contains 3,000 observations and 10 variables. Each entry represents a cyber incident and includes the following key variables:
- Country: country where the attack took place
- Year: Year of the incident
- Attack Type: Type of cybersecurity threat
- Target Industry: Industry targeted
- Financial Loss ($M): Estimated financial loss in millions
- Number of Affected Users: Number of users impacted by the attack
- Attack Source: Origin of the attack
- Security Vulnerability Type: Type of vulnerability
- Defense Mechanism Used: Cyber defense strategy applied
- Incident Resolution Time (Hours): Time taken to fully resolve the incident

This dataset allows analysis to be done for both the quantitative impacts (such as financial loss and resolution time) and the qualitative aspects (such as attack origin and attack type). It also spans a wide range if industries and global regions, offering a diverse view of cybersecurity incidents. However, it is important to note that this dataset has not been verified by a credible source. Because of this restriction, the figures should be interpreted as indicative rather than definitive, and conclusions should be supported by further studies.

## Features
- **Interactive choropleth map** of incidents by country  
- **Bar chart** comparing financial losses across attack types  
- **Boxplot with jitter** visualising resolution time distributions  

## Tools
- R  
- ggplot2  
- Leaflet  

## Files
- `Global_Cybersecurity_Threats_2015-2024.csv` → dataset (from Kaggle)  
- `cybersecurity-threat-analysis.Rmd` → analysis code  
- `cybersecurity-threat-analysis.html` → interactive visualisation  
---
