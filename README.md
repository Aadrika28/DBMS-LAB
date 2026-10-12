# Database Management Systems (DBMS) Lab

Repository containing organized experiments for the **Database Management Systems Lab (MySQL)**, completed by **Aadrika Pandey**.

Every experiment is structured into its own dedicated folder containing its documentation, complete SQL source code, and original terminal execution output screenshots.

---

## 📑 List of Experiments

| Experiment No. | Title | Aim Summary | Folder Link |
| :---: | :--- | :--- | :---: |
| **03** | **Employee–Department–Project Schema** | Create schema with 30 employees, 5 departments, and 8 projects. Execute queries demonstrating selection, projection, aggregates, GROUP BY, HAVING, CASE, and ORDER BY. | [📂 Experiment-03](./Experiment-03/) |
| **04** | **Complex SQL Queries & Optimization** | Implement INNER JOIN, LEFT JOIN, SELF JOIN, 3-way join, correlated subqueries, EXISTS, simulated INTERSECT/EXCEPT, and analyze execution plans using EXPLAIN. | [📂 Experiment-04](./Experiment-04/) |
| **05** | **SQL Views & Recursive CTEs** | Create department salary summary and employee hierarchy views, test view updatability, and construct recursive Common Table Expressions (WITH RECURSIVE) to map reporting chains. | [📂 Experiment-05](./Experiment-05/) |
| **06** | **Stored Procedures & Triggers** | Create stored procedure 	ransfer_employee with existence validation and error handling (SIGNAL SQLSTATE '45000'), and implement triggers for salary validation and automated audit logging. | [📂 Experiment-06](./Experiment-06/) |

---

## 📂 Repository Structure

`
DBMS-LAB/
├── README.md                                       # Root index and experiments navigation
├── DBMS_EXPERIMENT_3_Aadrika_Pandey.pdf           # Original Experiment 3 manual PDF
├── DBMS_EXPERIMENT_4_Aadrika_Pandey.pdf           # Original Experiment 4 manual PDF
├── DBMS_EXPERIMENT_5_Aadrika_Pandey.pdf           # Original Experiment 5 manual PDF
├── DBMS_EXPERIMENT_6_Aadrika_Pandey.pdf           # Original Experiment 6 manual PDF
├── Experiment-03/
│   ├── README.md                                   # Documentation, schema, queries and results
│   ├── experiment03.sql                            # Full DDL, DML, and query script
│   └── output/                                     # Execution output screenshots
│       ├── output_queries_1.png
│       └── output_queries_2.png
├── Experiment-04/
│   ├── README.md                                   # Joins, subqueries, and EXPLAIN documentation
│   ├── experiment04.sql                            # Full query and EXPLAIN script
│   └── output/                                     # Execution output screenshots
│       ├── output_joins_and_queries_1.png
│       └── output_joins_and_queries_2.png
├── Experiment-05/
│   ├── README.md                                   # Views, updatability tests, and recursive CTE docs
│   ├── experiment05.sql                            # Full views and recursive CTE script
│   └── output/                                     # Execution output screenshots
│       ├── output_views_salary_summary.png
│       ├── output_views_and_hierarchy.png
│       └── output_recursive_cte_chain.png
└── Experiment-06/
    ├── README.md                                   # Stored procedures, triggers, and audit logging
    ├── experiment06.sql                            # Procedure, triggers, and test harness
    └── output/                                     # Execution output screenshots
        ├── output_stored_proc_and_triggers_1.png
        └── output_stored_proc_and_triggers_2.png
`

---

## 🛠️ Environment & Tools
- **DBMS**: MySQL
- **Query Editor**: byteXL / Online MySQL Compiler
- **Language**: SQL (DDL, DML, DQL, Procedural SQL)
