# DPT — Data Projecting Tool

DPT is a browser-based data analysis tool designed to make common data analysis tasks fast and simple — without requiring SQL or complicated software.

## Features

### Dataset Analysis
- Automatic numeric/categorical column detection
- Dataset overview
- Row and column counts
- Missing values handled as `(NULL)`

### Numeric Statistics
- Count
- Average
- Median
- Standard deviation
- Q1
- Q3
- IQR
- Total / Sum

### Categorical Statistics
- Number of unique categories
- Top 5 categories
- Category frequencies
- Average category count
- Total count

### Correlations
- Pearson correlation
- Automatic relationship classification
- Sort by correlation strength

### Data Grouping
- Select columns
- GROUP BY multiple columns
- Row counts for each group
- Percentage of total rows
- Sort groups by size
- View distinct values within groups

### Calculations / Aggregations
- Values
- Count
- Average
- Sum
- Minimum
- Maximum
- Median
- Grouped calculations

## Supported Data

DPT currently supports:

- CSV files
- Excel files (`.xlsx`, `.xls`)
- Manual CSV-style data entry

## How to Use

1. Open DPT in a browser.
2. Load a CSV/Excel file or enter data manually.
3. DPT automatically analyzes the dataset.
4. Use the visible statistics for quick analysis.
5. Expand **Correlations**, **Data Grouping**, or **Calculations / Aggregations** when needed.

## Technology

DPT is currently built as a single HTML file using:

- HTML
- CSS
- JavaScript
- SheetJS for Excel file support

No server or database is required.

## Project Status

DPT is an actively developing project.

The goal is to make a large portion of routine exploratory data analysis possible in seconds, directly from the browser.

## License

License information will be added later.
