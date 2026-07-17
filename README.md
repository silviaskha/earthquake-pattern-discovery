# Earthquake Pattern Discovery using Association Rule Mining

## Overview

This project applies **Association Rule Mining (Apriori)** to discover hidden spatial-temporal co-occurrence patterns from historical Indonesian earthquake records.

Instead of predicting earthquakes, the project focuses on **unsupervised pattern discovery**, revealing which earthquake regions frequently appear together within the same daily observation window.

---

## Dataset

Source: Indonesian Earthquake Catalog (BMKG)

| Item | Value |
|------|------:|
| Time Span | 2009–2022 |
| Earthquake Events | 91,395 |
| Daily Transactions | 4,333 |
| Earthquake Regions | 51 |

---

## Problem Statement

Historical earthquake catalogs describe individual seismic events but do not explicitly reveal regional relationships.

This project transforms raw earthquake records into transaction data and applies Association Rule Mining to discover statistically meaningful regional co-occurrence patterns.

---

## Methodology

```
Raw Data
    │
    ▼
Data Quality Assessment
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Transaction Engineering
    │
    ▼
Transaction Encoding
    │
    ▼
Apriori Algorithm
    │
    ▼
Association Rules
    │
    ▼
Visualization
    │
    ▼
Business Insights
```

---

## Results

| Metric | Value |
|---------|------:|
| Frequent Itemsets | 11,708 |
| Association Rules | 27,129 |
| Average Confidence | 69.8% |
| Average Lift | 1.33 |
| Strongest Lift | 1.97 |

---

## Repository Structure

```
earthquake-pattern-discovery/
│
├── README.md
├── requirements.txt
├── notebooks/
│   └── earthquake_pattern_discovery.ipynb
├── data/
│   ├── raw/
│   └── processed/
├── images/
├── results/
└── src/
```

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Run

```bash
jupyter notebook notebooks/earthquake_pattern_discovery.ipynb
```

---

## Key Outputs

- Exploratory Data Analysis
- Transaction Dataset
- Frequent Itemsets
- Association Rules
- Rule Network Visualization
- Statistical Summary
- Business Insights

---

## Skills Demonstrated

- Python
- Pandas
- Data Cleaning
- Exploratory Data Analysis
- Association Rule Mining
- Apriori Algorithm
- Statistical Analysis
- Data Visualization
- Network Analysis
- Scientific Communication

---

## Future Improvements

- FP-Growth comparison
- Sequential Pattern Mining
- Temporal window comparison
- Graph analytics
- Earthquake network centrality analysis

---

