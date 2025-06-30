# 📌 Project Overview: Employee Performance Insights
## 🔹 Data Loading & Cleaning

Imported employee data using pandas

Converted JoinDate to proper datetime format (dd-mm-yyyy)

Ensured Salary and PerformanceRating are numeric

Handled missing values to maintain data integrity

## 🔹 Feature Engineering

Calculated Tenure as: 2025 - Join Year

Created SalaryCategory:

Salary < 50,000 → "Low"

50,000–90,000 → "Medium"

90,000 → "High"

## 🔹 Aggregated Analysis

Average Salary per Department

Gender Count per Department

Average Performance Rating per Department

Listed employees with performance rating ≤ 2

## 🔹 Excel Output

Saved all data and summaries into a single multi-sheet Excel file (employee_summary.xlsx)

## 🔹 Visualizations

Bar chart: Avg. Salary by Department

Pie chart: Salary Category Distribution
