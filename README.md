# Internship_Completion_Analysis

## Project Overview
This project analyzes internship completion rates using Power BI and Excel, identifying key success factors such as mentor interaction, internship duration, and department trends. The goal is to provide insights that help improve internship program efficiency.

### Dataset Description

The dataset used in this analysis includes the following columns:

- Intern ID :                   Unique identifier for each intern.
- Enrollment Date :             Date the intern joined the program.
- Completion Status :           Completed, Dropped Out, or In Progress.
- Dropout Reason :              If applicable, reason for dropping out.
- Department :                  Assigned department.
- Internship Duration :         Duration in weeks.
- Mentor Interaction :          Frequency (Weekly, Biweekly, None).
- Performance Score :           Optional metric based on intern output.

### Tools Used

- Microsoft Excel (Data Cleaning, Pivot Tables, Statistical Analysis)
- Power BI (Data Visualization, Dashboards)

### Project Goals
- Analyze enrollment trends to see how internship participation varies over time.
- Evaluate completion rates across different departments.
- Assess the impact of mentorship frequency on completion success.
- Determine the effect of internship duration on performance outcomes.
- Visualize insights using Power BI dashboards for easier interpretation.

### Data Processing Steps
1. Data Preparation
- Cleaned missing values and inconsistencies.
- Standardized date formats and categorical variables.
- Categorized Completion Status into numeric values (Completed = 1, Dropped Out = 0).

2. Statistical Analysis
- Enrollment Insights: Counted interns per department.
- Completion Rates: Calculated internship success percentage.
- Mentor Impact: Compared completion rates across mentor interaction frequencies.
- Duration Effect: Analyzed internship duration correlation with performance.

3. Data Visualization
- Visualizations created in Power BI:
- Bar Chart: Completion rates by department.
- Line Graph: Enrollment trends over time.
- Heatmap: Mentor interaction vs duration vs completion rates.

### How to Run This Project
- Steps in Power BI
- Load the dataset (internship_data.xlsx) into Power BI.
- Create relationships if necessary (e.g., linking internship duration and completion status).
- Build visualizations using bar charts, line graphs, and heatmaps.
- Organize the dashboard layout for clarity.
- Save and export visuals if needed.

### Steps in Excel
- Open the dataset.
- Use PivotTables for department-wise statistics.
- Perform basic statistical calculations (e.g., completion rates).
- Apply conditional formatting to highlight trends.
