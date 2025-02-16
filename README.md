# Bank Client Data Analysis

## Overview
This repository contains an analysis of a bank client dataset, where pivot tables were created to answer various questions regarding client attributes.

## Dataset Description
The dataset includes information about clients' demographics, financial history, and contact details from the bank's marketing campaigns.

### Columns:
- **Age**: Numeric value representing the client's age.
- **Job**: Type of job (e.g., admin, management, blue-collar, etc.).
- **Marital**: Marital status (e.g., married, divorced, single).
- **Education**: Level of education (e.g., primary, secondary, tertiary).
- **Default**: Whether the client has credit in default (yes/no).
- **Balance**: Average yearly balance in euros.
- **Housing**: Whether the client has a housing loan (yes/no).
- **Loan**: Whether the client has a personal loan (yes/no).
- **Contact**: Type of contact communication (telephone/cellular/unknown).
- **Day**: Last contact day of the month.
- **Month**: Last contact month of the year (e.g., jan, feb, mar, etc.).
- **Duration**: Last contact duration in seconds.
- **Campaign**: Number of contacts performed during this campaign.
- **Pdays**: Number of days passed since last contact from a previous campaign.
- **Previous**: Number of contacts before this campaign.
- **Poutcome**: Outcome of the previous campaign (e.g., success, failure, unknown).
- **y**: Whether the client subscribed to a term deposit (yes/no).

## Analysis Questions
The analysis explores the following key questions using pivot tables:

1. Age distribution of bank clients.
2. Proportions of clients in different job categories.
3. Distribution of marital status.
4. Proportions of clients with different education levels.
5. Percentage of clients with credit in default.
6. Average yearly balance by job category.
7. Comparison of clients with/without housing loans.
8. Comparison of clients with/without personal loans.
9. Distribution of contact communication methods.
10. Term deposit subscription rates based on the outcome of previous campaigns.

## Requirements
To run the analysis, you will need:
- **Microsoft Excel** (for reviewing and creating pivot tables).
- **The bank client dataset**, which can be downloaded from the provided link.
- **Python (optional)** for further data analysis.

## Code Usage
If you prefer to analyze the dataset using Python, you can use the following sample script:

```python
import pandas as pd

# Load dataset
df = pd.read_csv("bank_client_data.csv")

# Display first few rows
print(df.head())

# Summary statistics
print(df.describe())

# Count of job categories
print(df['Job'].value_counts())
```

## Instructions
1. Download the dataset from the link provided above.
2. Open the Excel file and explore the pivot tables created for each of the analysis questions.
3. Modify or add pivot tables as needed for further insights.
4. Alternatively, use Python to perform additional analysis.

## License
This project is open-source and available for further modifications and contributions.
