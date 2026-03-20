---
name: construction-site-scheduling
description: "Use this skill whenever you want to create a schedule based on an estimate. The schedule is the sequence of activities and work over time described by the estimate. The schedule is represented using a Gantt chart."
license: MIT License
---

# Requirements for Inputs

## For Creating a Schedule

### Input: object of schedule
- input is an estimate that includes a list of activities, their durations, and dependencies between activities
- input is desired start date for the schedule
- input is desired end date for the schedule

# Requirements for Editing a Schedule

## Rules for creating or editing a schedule
- place activities in time based on the dependencies and durations of each job or task

# Requirements for Outputs

## All Excel files

### Rules for Excel files
- When creating a new schedule, the output must be an Excel file that follows the specified structure and formatting guidelines.

### Excel structure
- column "ID"
- column "Activity description"
- column "Task Description"
- a column for each week/month/yar based on the duration of activities and tasks 

### Professional Font
- Use a consistent, professional font (e.g., Arial, Times New Roman) for all deliverables unless otherwise instructed by the user

### Zero Formula Errors
- Every Excel model MUST be delivered with ZERO formula errors (#REF!, #DIV/0!, #VALUE!, #N/A, #NAME?)

### Preserve Existing Templates (when updating templates)
- Study and EXACTLY match existing format, style, and conventions when modifying files
- Never impose standardized formatting on files with established patterns
- Existing template conventions ALWAYS override these guidelines

### Color Coding Standards
Unless otherwise stated by the user or existing template

#### Industry-Standard Color Conventions
- **Blue text (RGB: 0,0,255)**: Hardcoded inputs, and numbers users will change for scenarios
- **Black text (RGB: 0,0,0)**: ALL formulas and calculations
- **Green text (RGB: 0,128,0)**: Links pulling from other worksheets within same workbook
- **Red text (RGB: 255,0,0)**: External links to other files
- **Yellow background (RGB: 255,255,0)**: Key assumptions needing attention or cells that need to be updated

### Number Formatting Standards

#### Required Format Rules
- **Years**: Format as text strings (e.g., "2024" not "2,024")
- **Currency**: Use $#,##0 format; ALWAYS specify units in headers ("Revenue ($mm)")
- **Zeros**: Use number formatting to make all zeros "-", including percentages (e.g., "$#,##0;($#,##0);-")
- **Percentages**: Default to 0.0% format (one decimal)
- **Multiples**: Format as 0.0x for valuation multiples (EV/EBITDA, P/E)
- **Negative numbers**: Use parentheses (123) not minus -123

