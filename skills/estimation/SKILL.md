---
name: Estimation
description: "Use this skill any time user wants to create or edit an estimate. To create an estimate the input is PriceLists from PriceList MCP server and the output is an Excel file with the estimate. To edit an estimate the input is an existing Excel file and the output is a modified Excel file."
license: MIT License
---

# Requirements for Inputs

## For Creating an Estimate
- Input: object of Estimate (private works or public works) with all relevant fields filled out, including:
  - Description of work
  - Quantity
  - Any specific requirements or constraints
- Input: PriceLists from PriceList MCP server
  - Must include all relevant pricing information for materials, labor, and any other cost components
  - Must be up-to-date and accurate to ensure the estimate is reliable

# Requirements for Outputs

## All Excel files

### Excel structure
- column "Progressivo"
- column "Articolo"
- column "Descrizione dei lavori e delle provviste"
- column "Unità di misura"
- column "Quantità"
- column "Prezzo unitario"
- column "Totale"

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

