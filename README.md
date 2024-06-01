# Comprehensive-Fashion-Store-SQL-Database
This project involves creating a comprehensive SQL database for a fashion store using SQLite. The database is designed to simulate real-world operations of a fashion company, including detailed information about employees, fashion designs, clients, and orders.

Key Components:

1. Data Generation:
   - Utilized Python with numpy and Faker libraries to generate realistic, synthetic data.
   - Created four dataframes: employees, designs, clients, and orders, each containing relevant attributes.

2. Database Schema:
   - Employee Table: Contains details such as employee ID, names, birth dates, department, hire dates, and addresses.
   - Design Table: Includes design ID, names, and the employee ID of the creator.
   - Client Table: Holds client IDs, names, contact information, and membership types.
   - Order Table: Details order IDs, design IDs, client IDs, order dates, client ratings, and a compound key for unique identification.

3. Data Types:
   - Included various data types: nominal, ordinal, interval, and ratio data to ensure a diverse and realistic dataset.

4. Database Implementation:
   - Imported CSV files into SQLite DB Browser.
   - Set up primary keys, foreign keys, unique constraints, and not-null values to maintain data integrity and establish relationships between tables.

5. Ethical Considerations:
   - Ensured data privacy by using only synthetic data.
   - Represented various demographics and departments fairly.
   - Created the dataset for educational purposes only.

6. Example Queries:
   - Demonstrated complex SQL queries, including joins and selections, to showcase the functionality and relationships within the database.

This project highlights the ability to create, manage, and query a realistic database, demonstrating advanced SQL and data management skills.
