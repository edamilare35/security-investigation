# security-investigation
## Overview
This project involves investigating potential security issues related to login attempts and employee machine activities in a large organization. The goal is to use SQL filters to retrieve and analyze records from the `employees` and `log_in_attempts` tables to uncover suspicious activities.

## Project Structure
- `data/`: Contains the datasets used for the investigation.
- `docs/`: Documentation related to the project, including a project overview, data description, investigation plan, findings, and recommendations.
- `sql/`: SQL scripts for creating tables, loading data, and performing queries.
- `scripts/`: Python scripts for data preprocessing and analysis.
- `results/`: Summary reports and visualizations of the findings.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/edamilare35/security-investigation.git
   cd security-investigation
   ```

2. Install necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the database and load data:
   ```bash
   # Ensure your database server is running
   psql -U your_username -f sql/create_tables.sql
   psql -U your_username -f sql/load_data.sql
   ```

4. Run the analysis scripts:
   ```bash
   python scripts/data_preprocessing.py
   python scripts/analysis.py
   ```

## Findings and Recommendations
Detailed findings and recommendations can be found in the `docs/` folder.
```

This documentation will help in organizing your investigation project efficiently and ensure that all aspects of the investigation are covered comprehensively.