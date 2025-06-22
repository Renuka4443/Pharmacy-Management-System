# 💊💉Pharmacy Management System

A **Database Management System (DBMS)** mini-project built to automate and streamline pharmacy operations, such as managing prescriptions, customers, medicines, employees, and billing using SQL.

---

## 📄 Project Description

The Pharmacy Management System is designed to efficiently manage various aspects of a pharmacy including customer records, prescriptions, drug inventory, billing, and employee data. It utilizes core DBMS concepts such as:

- **ER & Schema Design**
- **Normalization**
- **SQL Tables and Data Insertion**
- **Stored Procedures & Functions**
- **Triggers**
- **Views**
- **Joins**
- **Exception Handling**

By automating key operations, the system enhances accuracy, minimizes human error, and improves the efficiency of pharmacy management.

---

## 🔧 Technologies Used

- **SQL (Oracle)** for database schema and queries
- **PL/SQL** for procedures, functions, triggers, and exception handling

---

## 🗃️ Database Features

### 📑 Tables Included
- `Customer`, `Insurance`, `Prescription`, `PrescriptionDrug`
- `Orders`, `OrderedDrugs`, `Bill`, `Medicine`
- `Employee`, `Notification`, `Employee_Notification`
- `Disposed`, `Employee_Disposed_Drugs`

### 🧠 Implemented Concepts
- **Procedures**: `CheckDrugStock`, `GenerateOrderReport`, `CheckEmployeeSalary`
- **Functions**: `CalculateDiscount`, `GetPrescriptionsByCustomer`
- **Trigger**: Auto-capitalizes drug names on insert/update
- **Views**: `CustomerPrescriptionView`, `TotalBillView`
- **Joins**: Inner Join, Left/Right Outer Join, Cross Join
- **Exception Handling**: For employee salary checks and drug stock validation

---

## 📂 Folder Contents

- `REPORT.pdf` – Detailed explanation of system architecture, ERD, normalization, and implementation.
- `CODE.txt` – Complete SQL code including table creation, data insertion, queries, views, triggers, procedures, and test cases.

---

## How to Use

1. Use an Oracle DBMS environment (like Oracle SQL Developer).
2. Run the table creation and data insertion scripts from `CODE.txt`.
3. Execute views, functions, procedures, and triggers as needed for testing.
4. Review the report (`REPORT.pdf`) for schema explanation and use case flow.

---

## 👨‍💻 Contributors

- Renuka Wadetwar
- Mansee Dakhole
- Poornima Mendhekar 





