# EXPERIMENT - 6

## AIM
To create a stored procedure 	ransfer_employee(emp_id, new_dept_id) with validation and error handling, and to implement triggers for salary validation and audit logging, including testing of edge cases.

---

## Student Details
- **Student Name:** Aadrika Pandey
- **Course:** Database Management Systems Lab

---

## Source Code
The complete SQL script for creating tables, the stored procedure, triggers, and execution test cases is in [experiment06.sql](./experiment06.sql).

### Key Components
1. **Salary_Audit Table**: Tracks historical salary changes with timestamps.
2. **	ransfer_employee Stored Procedure**:
   - Validates existence of both employee and target department.
   - Raises custom error SIGNAL SQLSTATE '45000' if either record does not exist.
   - Performs UPDATE when validations pass.
3. **efore_employee_salary_update Trigger**:
   - Rejects negative salaries (NEW.Salary < 0) via SIGNAL SQLSTATE '45000'.
4. **fter_employee_salary_update Trigger**:
   - Automatically writes audit log entries whenever OLD.Salary <> NEW.Salary.

---

## Output Screenshots

### 1. Stored Procedure & Trigger Outputs - Part 1
![Stored Procedure and Triggers 1](./output/output_stored_proc_and_triggers_1.png)

### 2. Stored Procedure & Trigger Outputs - Part 2
![Stored Procedure and Triggers 2](./output/output_stored_proc_and_triggers_2.png)
