# B41_DA_014_Stat_Seekers
Objective

The objective of this project is to process a dataset, clean and store it in an SQL database, and create a dynamic dashboard in Power BI. The dashboard will provide real-time insights by reflecting any changes made in the SQL database.

Project Workflow

1. Dataset Processing

Steps Followed:

Downloaded the dataset from the provided link and uploaded it to Google Drive for accessibility.

Connected to Google Drive programmatically using Python.

Loaded the dataset into a pandas DataFrame and performed data cleaning:

Handled missing values to ensure data integrity.

Normalized fields for consistency across the dataset.

Prepared the cleaned data for SQL database integration.

2. SQL Database Integration

Steps Followed:

Set up an SQL database and designed a schema to store the cleaned data efficiently.

Used Python to load the cleaned data from pandas into the SQL database.

Verified the structure and content of the database to ensure it supports the insights tracked by the dashboard.

3. Power BI Dynamic Dashboard

Steps Followed:

Established a connection between Power BI and the SQL database.

Designed interactive visualizations to display key metrics, such as:

Total sales.

Monthly performance.

Department-wise analysis.

Focused on creating a user-friendly and visually appealing interface.

4. Real-Time Updates

Steps Followed:

Configured automatic refresh intervals in Power BI to ensure real-time synchronization.

Tested and validated that changes in the SQL database are accurately reflected in the dashboard.
