# Meetings Log — CSE 4/587 Phase 1

## Meeting 1 — March 1, 2026 (Discord, 8:00 PM)
- **Attendees:** Harshvardhan Shinde, Lorenzo Price, Qiang Wu
- **Duration:** ~30 min
- **Discussion:**
  - First meeting after team registration
  - Went over Phase 1 requirements together
  - Brainstormed dataset options: considered NYC taxi data, Reddit comments, and stock market data
  - Settled on S&P 500 Stock Prices 2014-2017 from Kaggle (finance domain, 500K+ rows)
  - Divided tasks: Harshvardhan takes Task 1, Qiang takes Tasks 2-5, Lorenzo helps with review and report formatting
- **Action Items:**
  - Harshvardhan: Start researching problem statement and ML problem formulations
  - Qiang Wu: Download dataset, verify it meets size requirements, start exploring
  - Lorenzo: Look into HDFS Docker setup options

## Meeting 2 — March 5, 2026 (Discord, 9:00 PM)
- **Attendees:** Harshvardhan Shinde, Lorenzo Price, Qiang Wu
- **Duration:** ~25 min
- **Discussion:**
  - Qiang showed the raw dataset (497K rows, 7 columns) — noted it's pretty clean already and only has 7 columns
  - Decided to merge with S&P 500 constituents list to add sector info (more columns, richer analysis)
  - Harshvardhan shared a rough draft of Task 1 — had 3 algorithms but only 1 ML problem type
  - Discussed that the assignment asks for N=3 distinct problem types (classification, regression, clustering), not 3 algorithms for the same problem
  - Lorenzo confirmed Docker HDFS works on his machine with apache/hadoop:3
- **Action Items:**
  - Harshvardhan: Revise Task 1 with 3 separate ML problems
  - Qiang Wu: Finish data cleaning, add sector merge, run EDA
  - Lorenzo: Help proofread the final report

## Meeting 3 — March 10, 2026 (Discord, 7:30 PM)
- **Attendees:** Harshvardhan Shinde, Lorenzo Price, Qiang Wu
- **Duration:** ~20 min
- **Discussion:**
  - Qiang presented finished Tasks 2-5: 6 cleaning operations, 6 EDA plots, HDFS screenshot done
  - Reviewed the full report notebook together (screen shared)
  - Harshvardhan submitted updated Task 1 — now has classification, regression, and clustering
  - Went through the report one more time for consistency
  - Discussed Phase 2 direction: likely use Spark for the ML models
- **Action Items:**
  - Qiang Wu: Generate final PDF, compile zip, submit on UBLearns
  - All: Review final submission before upload

## Notes
- All communication was done through Discord group chat
- No members were absent from any meeting
