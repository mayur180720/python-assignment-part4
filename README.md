# Data Analysis & Visualization (Python Assignment)

## Description

This project demonstrates data analysis and visualization using Python. The dataset contains student performance details such as subject scores, attendance, study hours, and pass/fail status.

---

## DataFrame Overview

The dataset is loaded into a Pandas DataFrame with the following columns:

* `name` – Student name
* `math`, `science`, `english`, `history`, `pe` – Subject scores
* `attendance_pct` – Attendance percentage
* `study_hours_per_day` – Daily study hours
* `passed` – Pass (1) or Fail (0)

---

## Data Analysis Performed

* Calculated summary statistics using `.describe()`
* Checked data shape and column data types
* Computed average scores across subjects
* Identified top-performing students
* Counted pass vs fail students

---

## Visualizations

### Matplotlib Plots

* Bar Chart → Average score per subject
* Histogram → Distribution of math scores
* Scatter Plot → Study hours vs average score (Pass vs Fail)
* Box Plot → Attendance comparison (Pass vs Fail)
* Line Plot → Math vs Science scores

---

### Seaborn Plots

* Bar Plot → Average math and science scores grouped by pass/fail
* Scatter Plot → Attendance vs average score with regression lines

---

## Concepts Used

* Pandas DataFrame operations
* Data aggregation and filtering
* Data visualization using Matplotlib and Seaborn
* Plot customization (titles, labels, legends)
* Saving plots as image files

---

## How to Run

1. Install required libraries:

   ```
   pip install pandas matplotlib seaborn
   ```
2. Run the script:

   ```
   python part4_visualization_ml.py
   ```

---

## Key Highlights

* Demonstrates real-world data analysis workflow
* Combines data processing with visualization
* Uses both Matplotlib and Seaborn for comparison

---

## Author

Mayur Thote
