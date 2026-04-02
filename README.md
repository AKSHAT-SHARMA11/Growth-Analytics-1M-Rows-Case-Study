🚌 Flix: Growth Analytics & Pricing Intelligence System
Scaling Data Insights for 1 Million+ Records
📌 Project Overview
This repository contains a comprehensive data analysis system designed for Flix to optimize market competitiveness.
The project focuses on identifying pricing anomalies and providing actionable growth insights by benchmarking internal data against real-time market trends.
🚀 The Challenge: Big Data at ScaleUnlike standard datasets, this project involved handling 1,000,000+ (10 Lakh) rows of bus listing data.
Objective: Build a robust, automated system to flag incorrect pricing.
Complexity: Managing high-volume data, normalizing time formats, and calculating dynamic market benchmarks.
🛠️ Technical Implementation1. Advanced Data Wrangling (Python/Pandas)
Standardization: Successfully handled mixed datetime formats (%H:%M and %H:%M:%S) to ensure 100% temporal accuracy.
Efficiency: Optimized processing for 1M+ rows to maintain script performance.
2. Pricing Logic & Anomaly DetectionDefining Similarity: Engineered a logic to group "Comparable Buses" using Route Number and Departure Time windows.
Rolling Market Average: Implemented a 2-hour rolling window to calculate the Market_Avg_Price for dynamic benchmarking.
Smart Flagging: Automated alerts for prices categorized as:
🔴 Too High: Price > 1.1x Market Average.
🔵 Too Low: Price < 0.9x Market Average.
📸 Execution Proof (Visuals)StepProcess DescriptionVisual Evidence.
01Data Cleaning: Fixing time formats and numeric types.
02Logic Building: Calculating 2-hour rolling averages.
03Scalable Output: Final flagging on 1M+ records.
💡 Automation MVP PlanAs part of the assignment deliverables, I designed an automation workflow.
1.Tooling: Python (Pandas) + SQL for backend processing.
2.Workflow: Scheduled scripts to ingest daily bus listings and output a "Flagging Report" for the Growth Team.
🧰 Tech Stack
1.Language: Python (Pandas, NumPy)
2.Logic: SQL Window Functions (Rolling Windows)
3.Tools: Jupyter Notebook, MS Excel (Strategy Planning)
