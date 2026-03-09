# International T20 Cricket Data Analysis (EDA)

## Project Introduction
This project focuses on performing **Exploratory Data Analysis (EDA)** on a dataset of **International T20 cricket matches** using Python.

The goal of this analysis is to uncover patterns in T20 matches such as **team success rates, toss impact, match venues, yearly trends, and match-winning margins**.

Various **Python data analysis and visualization libraries** were used to examine the dataset and generate meaningful insights.

---

## Dataset Information
The dataset contains records of **international T20 cricket matches** including details such as:

- Match date
- Teams involved
- Venue and city
- Toss winner and toss decision
- Match winner
- Win margin
- Umpires

This information helps in analyzing performance trends and match dynamics.

---

## Technologies Used

The project was developed using the following tools and libraries:

- **Python**
- **Pandas** – for data manipulation and analysis
- **NumPy** – for numerical operations
- **Matplotlib** – for creating visualizations
- **Seaborn** – for advanced statistical plots
- **AST (Abstract Syntax Trees)** – for handling structured data

---

## Data Preparation

Before performing analysis, the dataset was cleaned and processed using the following steps:

- Examined dataset structure using `info()`, `shape`, and `describe()`
- Renamed columns to improve readability
- Managed missing or incomplete values
- Converted date columns to **datetime format**
- Extracted **year information** from dates for time-based analysis

These preprocessing steps ensured the dataset was suitable for accurate analysis.

---

## Exploratory Data Analysis

### Match Trends Over Time
Analyzed how the number of international T20 matches has changed over different years.

### Team Performance Evaluation
- Identified the teams with the **highest number of matches played**
- Calculated **total wins by each team**
- Computed **team win percentages**

### Toss Outcome Analysis
- Determined which teams win the toss most frequently
- Analyzed the distribution of **toss decisions (bat vs field)**
- Examined the relationship between **toss winners and match winners**

### Venue Insights
- Identified stadiums that hosted the **largest number of matches**
- Analyzed match distribution across cities

### Team Rivalries
Studied which pairs of teams have competed against each other the most times.

### Umpire Participation
Found the **umpires who officiated the highest number of matches**.

### Win Margin Analysis
Analyzed how matches are typically won:

- Victories by **runs**
- Victories by **wickets**

---

## Visualizations

Several plots were created to better understand the dataset, including:

- **Bar charts** showing teams with the most wins
- **Bar charts** displaying teams with the most matches played
- **Line chart** representing match frequency by year
- **Histogram** illustrating distribution of win margins
- **Box plots** highlighting variability in win margins
- **Correlation heatmap** for numeric relationships
- **Charts showing most popular venues**

These visualizations help present insights in a clear and intuitive way.

---

## Major Observations

Key findings from the analysis include:

- A few teams dominate in terms of total wins and win percentage.
- Some cricket stadiums host significantly more matches than others.
- Winning the toss does not necessarily lead to winning the match.
- The number of international T20 matches has steadily increased over time.
- Certain team rivalries occur much more frequently.

---

## Running the Project

### 1. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn
