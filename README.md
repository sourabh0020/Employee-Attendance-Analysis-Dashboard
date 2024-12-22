Project: Employee Attendance Analysis Dashboard

Overview

This project focuses on analyzing and visualizing employee attendance data using Power BI. The dataset contains attendance records for more than 80 employees, including details such as their employee codes, names, and daily attendance statuses (e.g., Present, Work From Home, Leave, etc.) over a period of time.

The goal of this project was to transform raw data into an interactive dashboard that provides insights into attendance patterns, making it easier to track and manage attendance records efficiently.

Problem Statement

The raw attendance dataset was unstructured, making it difficult to analyze and visualize directly. Some of the key challenges included:

Data Structure: The original dataset had Employee Codes and Names as columns, requiring restructuring to fit into a tabular format.

Data Quality: The dataset contained duplicate and null values that needed to be removed.

Limited Insights: Without proper cleaning and visualization, deriving actionable insights was challenging.

Steps Taken

Step 1: Data Transformation in Excel

Restructured Data: The initial dataset had employee IDs and names as columns, making it difficult for analysis. I transposed these into rows to form a proper tabular structure with columns for Employee Code, Name, Date, and Attendance Status.

Saved as Excel: The restructured data was saved in an Excel file for further processing.

Step 2: Data Cleaning in Power Query

Imported Data to Power BI: The Excel dataset was loaded into Power BI using the Power Query editor.

Performed Data Cleaning:

Removed duplicate rows to ensure each record was unique.

Removed null values to maintain data integrity.

Standardized attendance statuses (e.g., Present, WO, WFH, HSL, PL, etc.).

Added calculated columns for analysis (if needed, such as categorizing different types of leave).

Optimized Data Model: Ensured proper relationships between tables and structured the data model for visualization.

Step 3: Dashboard Creation in Power BI

Developed Visualizations:

Created charts and graphs to visualize attendance trends, leave patterns, and Work From Home (WFH) statistics.

Added slicers for dynamic filtering based on employee names, attendance statuses, and date ranges.

Enhanced User Experience:

Used interactive features such as slicers and drill-down capabilities.

Ensured the dashboard provided actionable insights at a glance.

Step 4: Export and Publish

Exported Dashboard: The dashboard was exported as a Power BI report for sharing and presentation.

Published to GitHub: Uploaded the project files, including the cleaned dataset and Power BI (.pbix) file, to GitHub.

Results

The final Power BI dashboard provides the following insights:

Attendance patterns for individual employees and the organization as a whole.

Identification of employees with frequent leaves, WFH days, or specific attendance statuses.

Dynamic filtering capabilities to customize views and analyze attendance trends over time.
