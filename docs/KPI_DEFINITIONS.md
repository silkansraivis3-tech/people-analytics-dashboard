# KPI Definitions

This document explains the main KPIs used in the People Analytics Dashboard.

The goal of these KPIs is to give a quick overview of workforce size, employee status, onboarding and training progress, data quality, and possible automation opportunities.

## Total Employees

**Definition:**  
Total number of employee records in the dataset.

**Why it matters:**  
This gives a basic view of the dataset size and helps understand the overall workforce scale used in the analysis.

## Active Employees

**Definition:**  
Employees where `status` is `Active`.

**Why it matters:**  
This shows the current active workforce and helps separate current employees from employees who have exited.

## Exited Employees

**Definition:**  
Employees where `status` is `Exited`.

**Why it matters:**  
This helps track employee exits and supports turnover-related analysis.

## Active Employee Rate

**Definition:**  
Percentage of employees where `status` is `Active`.

**Formula:**  
Active Employees / Total Employees

**Why it matters:**  
This gives a simple view of workforce stability in the dataset.

## Onboarding Completion Rate

**Definition:**  
Percentage of employees where `onboarding_completed` is `Yes`.

**Formula:**  
Employees with completed onboarding / Total Employees

**Why it matters:**  
Onboarding completion is important because incomplete onboarding can create process gaps, unclear responsibilities, and lower employee readiness.

## Training Completion Rate

**Definition:**  
Percentage of employees where `training_completed` is `Yes`.

**Formula:**  
Employees with completed training / Total Employees

**Why it matters:**  
Training completion helps understand whether employees have received required preparation for their role.

## Safety Training Completion Rate

**Definition:**  
Percentage of employees where `safety_training_completed` is `Yes`.

**Formula:**  
Employees with completed safety training / Total Employees

**Why it matters:**  
Safety training is especially important in logistics and operations environments, where employees may work with physical processes, delivery workflows, or warehouse-related tasks.

## Performance Review Completion Rate

**Definition:**  
Percentage of employees where `performance_review_completed` is `Yes`.

**Formula:**  
Employees with completed performance review / Total Employees

**Why it matters:**  
This shows whether HR and management processes are being completed consistently.

## Data Quality Issues

**Definition:**  
Number of records where `data_issue` is not empty.

**Why it matters:**  
Data quality issues can make reporting unreliable. Missing or incorrect data can affect dashboards, workforce planning, compliance checks, and management decisions.

## Automation Candidates

**Definition:**  
Number of records where `automation_candidate` is `Yes`.

**Why it matters:**  
This helps identify areas where manual checking, reminders, validations, or reporting workflows could potentially be automated.

## Average Engagement Score

**Definition:**  
Average value of `engagement_score` across all employee records.

**Why it matters:**  
Engagement score gives a high-level signal about employee sentiment and team health.

## Average Absenteeism Days YTD

**Definition:**  
Average value of `absenteeism_days_ytd` across all employee records.

**Why it matters:**  
Absenteeism can help identify workload, wellbeing, or operational issues.

## Average Overtime Hours QTR

**Definition:**  
Average value of `overtime_hours_qtr` across all employee records.

**Why it matters:**  
Overtime can show workload pressure and may help identify teams where process improvement or additional support is needed.