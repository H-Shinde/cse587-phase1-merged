# CSE 4/587 — End-to-End Big Data Pipeline (Phase 1)

## S&P 500 Stock Prices Analysis (2014–2017)

### Project Overview
This project builds an end-to-end big data pipeline using Hadoop and Spark to analyze S&P 500 stock market data. Phase 1 covers problem definition, data acquisition, HDFS ingestion, data cleaning, and exploratory data analysis.

### Dataset
- **Source:** [Kaggle — S&P 500 Stock Data](https://www.kaggle.com/datasets/camnugent/sandp500) (CC0 Public Domain)
- **Size:** 497,472 rows × 7 columns
- **Time Span:** January 2014 – December 2017
- **Coverage:** 505 S&P 500 component stocks (daily OHLCV data)

### Project Structure
```
├── Phase1_Report.ipynb        # Full report notebook (Tasks 1-5)
├── Phase1_Report.html         # HTML version of the report
├── phase1_task4_5.ipynb       # Executable notebook for data cleaning & EDA
├── hdfs_screenshot.png        # HDFS verification screenshot
├── work_division.md           # Team work division
├── meetings_log.md            # Team meetings log
└── Project Phase 1 (1).pdf   # Assignment specification
```

### Tasks Completed
| Task | Description | Points |
|------|-------------|--------|
| Task 1 | Problem Statement | 20 pts |
| Task 2 | Data Sources & Citations | 15 pts |
| Task 3 | HDFS Utilization (raw + cleaned data) | 15 pts |
| Task 4 | Data Cleaning (6 operations) | 25 pts |
| Task 5 | Exploratory Data Analysis (6 EDA operations) | 25 pts |

### Tools Used
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- Hadoop HDFS (Docker: apache/hadoop:3)
