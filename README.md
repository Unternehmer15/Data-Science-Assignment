# Exploratory Data Analysis of International T20 Cricket Dataset

## Overview
This project performs **Exploratory Data Analysis (EDA)** on an international **T20 cricket dataset** using Python.  
The objective is to explore patterns in T20 cricket matches such as team performance, win margins, toss decisions, venues, and match trends over the years.

The analysis is done using **Pandas, NumPy, Matplotlib, and Seaborn**.

---

## Dataset Description
The dataset contains information about international T20 cricket matches.


##  Tools and Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **AST**

---

## Data Preprocessing

The following preprocessing steps were performed:

- Checked dataset structure using `shape()`, `info()`, and `describe()`
- Renamed columns for clarity
- Handled missing values
- Converted date columns to **datetime format**
- Extracted **year** from date columns for trend analysis

---

## Exploratory Data Analysis

### 1 Matches Played Per Year
Analyzed the number of matches played each year to observe the growth of T20 cricket.

### 2️ Team Performance Analysis
- Calculated **matches played by each team**
- Calculated **matches won by each team**
- Computed **win percentage for each team**

### 3️ Toss Analysis
- Teams that won the most tosses
- Toss decision distribution (bat vs field)
- Comparison between **toss winner and match winner**

### 4️ Venue Analysis
- Venues hosting the most matches
- Distribution of matches across different cities

### 5️ Team Rivalry Analysis
Identified **pairs of teams that played the most matches against each other**.

### 6️ Umpire Analysis
Determined the **umpires who officiated the most matches**.

### 7️ Win Margin Analysis
Analyzed distribution of **wins by runs and wickets**.

---

##  Data Visualizations

The following visualizations were created using **Matplotlib and Seaborn**:

-  Bar chart of **top teams by matches won**
-  Bar chart of **top teams by matches played**
-  Line plot of **matches played per year**
-  Histogram of **win margins**
-  Box plot showing **spread of win margins**
-  Correlation heatmap
-  Venue popularity chart

These visualizations help identify trends and patterns in the dataset.

---

##  Key Insights

Some important insights from the analysis include:

- Certain teams have consistently higher win percentages.
- Some venues host significantly more matches than others.
- Winning the toss does not guarantee winning the match.
- The number of T20 matches has increased over time.
- Some team rivalries occur more frequently than others.

---

##  How to Run the Project

1️ Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

2️ Load the dataset into Python.

3️ Run the analysis notebook or Python scripts to generate insights and visualizations.

---

## Learning Outcomes

This project demonstrates:

- Data cleaning and preprocessing
- Data aggregation using Pandas
- Data visualization techniques
- Sports data analysis using Python

---

##  Author

**Yash Raj Mehta**

This project was developed as part of a **Data Analysis / Exploratory Data Analysis assignment** using Python.

---
