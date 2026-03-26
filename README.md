# Intern Performance Evaluation System

## Overview
This project provides a KPI-based system to evaluate intern performance and generate automated monthly reports using Python.

It helps track productivity, quality of work, and mentor feedback in a structured and data-driven way.

---

## Features
- Calculates task completion time automatically  
- Evaluates project quality and mentor feedback  
- Generates monthly performance reports  
- Provides performance insights using aggregated data  

---

## KPIs Used

### 1. Task Completion Time
Measured as the number of days taken to complete a task.

### 2. Project Quality
Score between 1–10 representing the quality of completed work.

### 3. Mentor Feedback
Score between 1–5 based on mentor evaluation.

---

## Project Structure
├── intern_performance.csv
├── Performance_Evaluation_Metrics.ipynb
├── monthly_performance_report.csv
├── README.md


---

## How to Run the Project

### Step 1: Open Notebook
Upload `Performance_Evaluation_Metrics.ipynb` to Google Colab or run locally using Jupyter Notebook.

---

### Step 2: Upload Dataset
Upload the file:
intern_performance.csv

---

### Step 3: Install Dependencies
If running locally:
pip install pandas matplotlib


---

### Step 4: Run the Notebook
Execute all cells to:
- Process data  
- Calculate KPIs  
- Generate charts  
- Create monthly report  

---

### Step 5: Download Report
The final report will be saved as:
monthly_performance_report.csv


---

## Output

The system generates:

- Monthly average completion time  
- Monthly average quality score  
- Monthly average feedback score  
- Performance trends (via charts)  

---

## Use Cases

- Internship performance tracking  
- Team productivity analysis  
- HR reporting and evaluation  
- Academic or training program assessment  

---

## Future Improvements

- Interactive dashboards (Power BI / Streamlit)  
- Real-time data integration  
- Advanced performance scoring models  
