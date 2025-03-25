# Movies Database

## Project General Objectives


This project aimed to design and implement a Movies Database from scratch.
Demonstrate the technical and non-technical skills developed during the Data Analyst program.

The project contains 9 technical project tasks divided into 3 Sprints.

Each Sprint starts with a sprint planning meeting and end with a sprint review, including a client demo, followed by a retrospective, in line with the Scrum methodology.

At the end of the project, team provides a final project presentation to the entire class and to the client.



---

## Project Steps

### Sprint 1

#### 1. Task 1: Set Up a Trello Board
   - **Tools Used**: Trello
   - **Objectives**: Initialize a shared Trello board for the project.
                     Establish basic project documentation and organize tasks effectively.

#### 2. Task 2: Data Cleaning and Validation
-  **Tools Used**: Visual Studio Code (VS Code), Python, Excel
- **Objectives**:  Identify and fix miss or incomplete fields
                   Correct data formats
                   Identify and correct inconsistent text formats

**Exploring the Data**
   - **Goal**: Conduct an initial data exploration to understand data distribution, check column names, types, and identify potential issues.
   - **Analysis**: Use functions like `.info()`, `.describe()`, and `.head()` to get a quick overview of the data structure and statistics.

**Data Cleaning**
   - **Handle Missing Values**: Drop rows or columns with missing values if they are insignificant; fill values where essential.
   - **Fix Data Types**: Ensure all columns have consistent data types 
   - **Validation**: Check for any remaining inconsistencies and verify the cleaned data.

#### 3. Task 3: Refine Movies Based on Client Feedback
   - **Objectives**: Apply client feedback to further refine the Movies 
                     dataset.
                     Document changes made to the data based on client 
                     instructions.

### 8. Load Data into MySQL
   - **Set Up Connections**: Connect to MySQL and PostgreSQL using `sqlalchemy` and load the cleaned data into each database.
   - **Table Creation**: Set up tables in both MySQL and PostgreSQL using Python SQLAlchemy to automate table creation and data insertion.
   - **Verification**: Run initial SQL queries to confirm that the data has been loaded accurately.

### 9. SQL Analysis: Complex Queries and Business Problem Solving
   - **Business Problem-Solving**: Write and execute complex SQL queries to answer critical business questions, such as:
   - **Documentation**: Keep clear notes of each query's objective, approach, and results.


---

## Requirements

- **Python 3.13+**
- **SQL Databases**: MySQL
- **Python Libraries**:
  - `pandas`, `numpy`, `sqlalchemy`, `mysql-connector-python`, `psycopg2`

---

## Project Structure

```plaintext
|-- data/                     # Raw data and transformed data
|-- sql_queries/              # SQL scripts for analysis and queries
|-- notebooks/                # Jupyter notebooks for Python analysis
|-- README.md                 # Project documentation
|-- requirements.txt          # List of required Python libraries
|-- main.py                   # Main script for loading, cleaning, and processing data
```
---

## Results and Insights

This section will include your analysis findings:


## Future Enhancements

Possible extensions to this project:
- Integration with a dashboard tool (e.g., Power BI or Tableau) for interactive visualization.
- Additional data sources to enhance analysis depth.
- Automation of the data pipeline for real-time data ingestion and analysis.


## Acknowledgments
- **Data Source**: Generation Ghana Team

---
