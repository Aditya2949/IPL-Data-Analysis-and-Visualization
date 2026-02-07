# 🏏 IPL Data Analysis & Visualization using Python

This project performs **exploratory data analysis (EDA)** on the **IPL matches dataset** using Python libraries like Pandas, Matplotlib, and Seaborn.

The main focus is to analyze match results, player performance, toss impact, and team-wise statistics using visualizations.

---

## 🧠 What I Have Done in This Project

- Imported required Python libraries for data analysis and visualization
- Loaded the IPL matches dataset
- Viewed the first few records of the dataset
- Checked the number of rows and columns in the dataset
- Analyzed **Man of the Match** awards:
  - Found frequency of all awards
  - Extracted **Top 10 players** with most awards
- Created **bar plots** for visual analysis
- Analyzed match results:
  - Frequency of match results
  - Teams winning after winning the toss
- Extracted matches where:
  - Team won **batting first**
  - Team won **batting second**
- Visualized:
  - Toss decision (bat / field) using histogram
  - Winning teams using bar plots and pie charts
- Found:
  - Top 3 teams with most wins (bar & pie chart)
  - Frequency of wins with respect to number of wickets
- Analyzed season-wise and city-wise match distribution
- Calculated how many times a team **won the match after winning the toss**

---

## 🛠️ Libraries Used

- **Pandas** – Data manipulation and analysis  
- **Matplotlib** – Basic plotting  
- **Seaborn** – Statistical data visualization  
- **NumPy** – Numerical operations  

---

## 📌 Sample Code Snippet

```python
# loading the required libraries
import pandas as pd
from matplotlib import pyplot as plt
import seaborn as sns
import numpy as np


