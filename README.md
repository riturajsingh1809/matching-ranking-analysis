# Candidate-Job Matching & Ranking Analysis

### Developer: Ritu Raj Singh

---

## 📌 Project Overview

This project is an end-to-end *Data Analytics project focused on Candidate-Job Matching and Ranking Performance*.

The project analyzes how effectively candidates are matched with job opportunities and evaluates the performance of different ranking metrics. The complete workflow includes data cleaning, Python-based analysis, insight generation, and interactive Tableau visualization.

The project follows a practical analytics workflow:

*Raw Data → Data Cleaning → Python Analysis → Insights → Tableau Dashboard*

---

## 🎯 Project Objectives

- Analyze candidate-job matching performance.
- Evaluate relevance and ranking scores.
- Measure shortlisting and hiring performance.
- Compare baseline and new ranking performance.
- Identify category-wise matching patterns.
- Analyze skills matching and ranking positions.
- Identify top-performing candidate-job matches.
- Present key findings through an interactive Tableau dashboard.

---

## 🛠️ Tools & Technologies

- *Python*
- *Pandas*
- *NumPy*
- *Google Colab*
- *Microsoft Excel*
- *Tableau*
- *GitHub*

---

## 🔄 Project Workflow

### 1. Data Cleaning

The sample dataset was cleaned and prepared using Python in Google Colab.

The cleaning process includes:

- Data quality checks
- Missing value handling
- Duplicate checks
- Data type validation
- Standardization of relevant fields
- Preparation of an analysis-ready dataset

### 2. Python Analysis

The cleaned dataset was analyzed using Python to generate KPIs, performance metrics, patterns, and business insights.

Key analysis areas include:

- Total Matches
- Average Relevance Score
- Shortlist Rate
- Hire Rate
- Average Time to Hire
- Category-wise Performance
- Skills Matching
- Evaluation Labels
- Ranking Position Analysis
- Baseline vs New Ranker
- Top 10 Matches

### 3. Tableau Dashboard

The cleaned dataset was then used in Tableau to create an interactive dashboard.

The dashboard provides a visual view of:

- Matching Quality
- Relevance by Category
- Shortlist Rate
- Hire Rate
- Time to Hire
- Ranking Performance
- Skills Matching
- Top Matches

---

## 📊 Key Insights

The analysis helps understand:

- Which job categories show stronger matching performance.
- How relevance and ranking scores vary across matches.
- How shortlisting and hiring rates differ by category.
- How the new ranking approach performs compared with the baseline.
- Which candidate-job matches receive the highest ranking scores.
- How matching and ranking patterns can support better hiring decisions.

---

## 📁 Project Structure

```text
matching-ranking-analysis/
│
├── README.md
│
├── data/
│   ├── sample_dataset.xlsx
│   └── cleaned_matching_ranking_dataset.xlsx
│
├── notebooks/
│   └── python-notebook.ipynb
│
├── analysis/
│   └── matching_ranking_python_analysis.xlsx
│
├── tableau/
│   └── Tableau.twbx
│
└── screenshots/
    └── dashboard.png
