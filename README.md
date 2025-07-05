Employee Analytics 📊

This project analyzes a dataset of employee records to uncover insights related to retention, demographics, and compensation. Using PostgreSQL and SQL queries, it explores factors like education level, age, experience, benching status, and payment tier to better understand employee behavior and attrition patterns.

 📁 Dataset Overview
The dataset includes columns:
- **Education**: Employee education level.
- **JoiningYear**: Year the employee joined the company.
- **City**: Location of the employee.
- **PaymentTier**: Compensation tier (1, 2, or 3).
- **Age**: Employee’s age.
- **Gender**: Gender identification.
- **EverBenched**: Whether the employee was ever benched (boolean).
- **ExperienceInCurrentDomain**: Years of experience in current role.
- **LeaveOrNot**: Whether the employee left (boolean).

🛠️ Features
- SQL table creation with appropriate data types (BOOLEAN, TEXT, INT).
- Importing CSV data using `COPY`.
- Data cleaning: converting Yes/No fields to BOOLEAN.
- Exploratory SQL queries, including:
  - Counts of employees staying/leaving by education.
  - Average age and experience grouped by education.
  - Attrition rates by payment tier.
  - Gender-based analysis.
- Aggregate functions: `COUNT()`, `AVG()`, `SUM()`, and conditional aggregates with `FILTER()`.
- Visualization suggestions for retention and compensation trends.
