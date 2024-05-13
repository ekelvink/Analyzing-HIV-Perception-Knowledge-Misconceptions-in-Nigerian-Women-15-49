# Project Name: Analyzing HIV Risk Perception, Knowledge Gaps and Misconceptions among women aged 15 - 49 years in Nigeria
---
# Introduction:
This project outlines a study focusing on the analysis of HIV risk perception, particularly examining knowledge gaps and misconceptions prevalent among **women aged 15 - 45 years** in Nigeria.

---
# Project Objectives:
To comprehensively analyze HIV risk perception among **women aged 15 - 49years** in Nigeria, focusing on knowledge gaps and misconceptions, and to explore the implications of these perceptions on individual behaviors and public health interventions.

---
# Data Sourcing:
Nigeria Demographic and Health Surveys

---
# Tools used:
The tool used for this analysis is R. 

I imported the following R libraries ; 
  janitor (# for data analysis utilities),
  here (# to set the working directory),
  haven (# for reading Stata files),
  tidyverse (# for data manipulation and visualization),
  scales (# for formatting the percentage),
  plotly (# for interactive plot),
  leaflet (# for creating a map),
  htmlwidgets (# for saving my map),
  patchwork (# for combining plots),
  flextable (# for a flexible and intuitive table).

---
# Data Transformation:
1. 𝗗𝗮𝘁𝗮 𝗖𝗹𝗲𝗮𝗻𝗶𝗻𝗴: The tasks I did here include importing relevant columns from the NDHS data (.dta) using haven, renaming columns for easy identification by assigning descriptive names to the newly imported variables, then transformed all variables into regular R factors by adding function to convert from labelled data to regular factors.
2. 𝗗𝗮𝘁𝗮 𝗩𝗶𝘀𝘂𝗮𝗹𝗶𝘇𝗮𝘁𝗶𝗼𝗻: This aspect involves visualizing key metrics to gain insights and make informed decisions. These visualizations cover aspects such as Basic information, Literacy and media, Knowledge of STIs and AIDS, Risk of getting HIV, Mode of transmission, Condom used during last sex, and Source and brand of condoms used for last sex. These insights can help us assess the level of knowledge among the Nigerian women aged 15 - 49years regarding modes of HIV transmission across a spectrum of wealth index, identify prevalent misconceptions, while exploring the socio-cultural, educational, and informational factors influencing HIV risk perception among the women.

---
# Major Highlight of the Visual:
- **Low Awareness:** The data indicates a lack of awareness of STIs and AIDS among respondents across all wealth index categories. This suggests a potential gap in health education or access to information about these health issues within the surveyed population.

- **Uniformity Across Wealth Indexes:** Interestingly, there seems to be no significant variation in the awareness levels of STIs and AIDS across different wealth index categories. This uniformity implies that awareness campaigns and educational initiatives regarding STIs and AIDS may not be effectively reaching individuals across various socioeconomic backgrounds.

- **Need for Targeted Education:** To address the lack of awareness observed in this dataset, targeted educational programs and outreach efforts may be necessary to ensure that individuals from all wealth index categories receive essential information about STIs and AIDS.

Overall, this dataset underscores the importance of comprehensive health education and awareness campaigns to promote understanding and prevention of STIs and AIDS across diverse socioeconomic groups.
