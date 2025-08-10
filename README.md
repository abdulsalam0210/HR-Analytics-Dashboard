# HR-Analytics-Dashboard
The HR Analytics Dashboard provides workforce insights, enabling HR teams and management to monitor trends, identify attrition patterns, and make data-driven decisions. It covers demographics, job roles, education, salary ranges, and attrition causes — helping organizations improve retention strategies and workforce planning.



##  Questions (KPIs)
- Which departments have the highest attrition?
- What is the average employee tenure?
- Which age group is leaving the company most often?
- Does salary range impact attrition rate?
- What is the current total workforce and how is it changing?


##  Process Followed in Dashboard Creation

###  Data Collection
- Collected HR dataset containing employee demographics, job roles, salaries, and attrition details.
- **Source:** Company HR system / sample HR dataset.

###  Data Cleaning & Preparation *(Power Query)*
- Removed duplicates and irrelevant columns.
- Fixed missing values and corrected data types.
- Standardized department, job role, and education fields.

###  Data Transformation
- Created calculated columns for age groups, salary ranges, and tenure categories.
- Used DAX measures for KPIs like **Attrition Rate**, **Average Age**, **Average Salary**.

###  Data Modeling
- Established relationships between tables (employee details, department, education, salary).
- Ensured model optimization for performance.


