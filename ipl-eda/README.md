# 🏏 IPL Historical Analytics & Match Intelligence

> **End-to-End Exploratory Data Analysis of IPL Ball-by-Ball Data**

This project explores historical IPL data by transforming raw ball-by-ball deliveries into meaningful batting, bowling, and match-level insights. It focuses on data cleaning, feature engineering, and exploratory data analysis to build a strong foundation for an end-to-end Machine Learning pipeline capable of predicting IPL match outcomes.

---

## 🎯 Project Objectives

- Clean and preprocess raw IPL datasets.
- Engineer player-level performance statistics.
- Perform exploratory data analysis (EDA).
- Discover meaningful cricket insights.
- Build features for future Machine Learning models.
- Develop an IPL Match Prediction System.
- Deploy the final project as a web application.

---

## 📂 Datasets Used

| Dataset | Description |
|----------|-------------|
| **deliveries.csv** | Ball-by-ball IPL delivery records |
| **matches.csv** | Match information including winner, venue, toss, margins and Player of the Match |
| **batsman_stats.csv** | Engineered batting statistics generated from deliveries.csv |
| **bowler_stats.csv** | Engineered bowling statistics generated from deliveries.csv |

---

# 🏗️ Project Workflow

```text
Raw IPL Datasets
        │
        ▼
 Data Cleaning
        │
        ▼
 Feature Engineering
        │
        ▼
 Player Statistics
        │
        ▼
 Exploratory Data Analysis
        │
        ▼
 Cricket Insights
        │
        ▼
 Future Machine Learning Pipeline
```

---

# 🧹 Data Cleaning

The datasets were carefully cleaned before analysis.

### Cleaning Steps

- Removed unnecessary columns
- Checked duplicate records
- Handled missing values
- Corrected data types
- Standardized categorical values
- Filled valid missing values
- Verified dataset consistency

---

# ⚙️ Feature Engineering

Player-level statistics were engineered from the raw delivery data.

## 🏏 Batting Features

- Runs Scored
- Batting Average
- Strike Rate
- Boundary Percentage
- Total Fours
- Total Sixes
- Half Centuries
- Centuries
- Matches Played

---

## 🎯 Bowling Features

- Wickets Taken
- Bowling Average
- Bowling Economy
- Bowling Strike Rate
- Dot Ball Percentage
- Four Wicket Hauls
- Five Wicket Hauls
- Matches Played

These engineered features will serve as inputs for future machine learning models.

---

# 📊 Exploratory Data Analysis

EDA was performed on all engineered datasets.

## 🏏 Batting Analysis

- Top Run Scorers
- Most Consistent Batsmen
- Strike Rate Analysis
- Boundary Hitters
- Milestone Analysis

---

## 🎯 Bowling Analysis

- Highest Wicket Takers
- Bowling Economy
- Bowling Average
- Strike Rate
- Dot Ball Specialists
- Multi-Wicket Performances

---

## 🏟️ Match Analysis

- Toss Decisions
- Toss vs Match Winner
- Venue Analysis
- Team Performances
- Winning Margins
- Player of the Match Distribution

---

# 🔍 Key Insights

- Consistent batsmen are not always the fastest scorers.
- Economy rate and wicket-taking ability are not always directly related.
- Teams display different strengths across venues.
- Winning the toss does not always guarantee victory.
- Player performance varies significantly with match context.
- Historical data provides meaningful indicators for future predictive modelling.

---

# 🧠 Engineering Decisions

Instead of using raw columns directly, player-level features were engineered to represent real-world cricket concepts in a machine-readable format.

Examples include:

- Batting Strength
- Bowling Strength
- Strike Rate
- Economy
- Boundary Percentage
- Dot Ball Percentage

This project emphasizes feature engineering as the bridge between raw cricket data and future machine learning models.

---

# 💻 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📈 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Statistical Analysis
- Data Aggregation
- Data Visualization
- Analytical Thinking
- Sports Data Analytics

---

# 🚀 Project Roadmap

## ✅ Completed

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis

## 🔄 In Progress

- Advanced Feature Engineering
- Feature Selection

## 📌 Upcoming

- Machine Learning Models
- Hyperparameter Tuning
- Model Evaluation
- FastAPI Deployment
- Cricket Analytics Dashboard

---

# 📂 Repository Structure

```text
ipl-eda
│
├── notebooks
├── data
├── images
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# ▶️ Getting Started

Clone the repository

```bash
git clone https://github.com/sxrthk17/data-analysis-projects.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Open the notebook

```bash
jupyter notebook
```

---

# 🌱 About This Project

This project is the first stage of my Machine Learning journey.

Rather than stopping at visualization, the goal is to progressively transform this repository into a complete end-to-end IPL Match Prediction System with advanced feature engineering, machine learning, deployment, and an interactive cricket analytics dashboard.

I believe that understanding the reasoning behind every engineered feature is just as important as building the final model.

---

## ⭐ If you found this project interesting, consider giving the repository a star!
