# Antarctic Penguin Morphology and Isotope Study (2007–2009)

This repository contains an end-to-end analysis and visualization of Antarctic penguin morphology and isotope data collected in three studies: **PAL0708**, **PAL0809**, and **PAL0910**.

## 📊 Overview
- **Data Source:** antarctic_penguins.csv
- **Analysis:** Conducted in R using `tidyverse`
- **Visualization:** Tableau Dashboard (morphology, isotope ratios, and trends)
- **Years:** 2007–2009
- **Species:** Adelie, Chinstrap, Gentoo

<pre> 📂 Repository Structure ``` ├── data/ # Raw and processed datasets │ ├── antarctic_penguins.csv │ ├── peng_processed.csv │ ├── analysis.Rmd # R Markdown preprocessing and cleaning ├── analysis.html # Rendered HTML from R Markdown │ ├── tableau/ # Tableau workbook files │ └── penguins.twbx │ └── README.md ``` </pre>



## 🧠 Key Insights
- Gentoo females show increasing body mass over years.
- Gentoo are the heaviest and have the longest flipper length.
- Adelie penguins have the shortest culmen length.
- Gentoo have the smallest culmen depth.
- δ¹³C decreased for Adelie and Gentoo (indicating pelagic feeding shift).
- δ¹⁵N dropped for Adelie in 2008; increased for Chinstrap and Gentoo.
- As δ¹⁵N increases, δ¹³C also increases (except for Chinstrap).

## ⚙️ R Environment

library(tidyverse)
library(dplyr)


The Tableau dashboard allows:
Dynamic axis control (X Axis Var, Y Axis Var)
Boxplots for distributions
Interactive sex highlighting and trendlines
Filters for year and species
