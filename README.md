# Research-project-database_1
# 🗂️ Database Project – Project Management System

This project represents a **simple relational database schema** for managing projects, funding agencies, employees, and their relationships within an organization. The schema is designed to model real-world project assignment and supervision workflows.

---

## 📌 Overview

The system consists of five main tables:

1. **`project`** – Contains information about each project.
2. **`fundingagency`** – Stores data about agencies funding the projects.
3. **`employee`** – Represents the employees involved in the projects.
4. **`employee_project`** – A relational table that maps employees to the projects they work on.
5. **`project_manager`** – Tracks which employees are managing which projects.

---

## 🧱 Database Schema

### 🔹 `project` Table
| Column Name | Data Type     | Description                    |
|-------------|---------------|--------------------------------|
| Project_ID  | `INT (PK)`    | Unique ID of the project       |
| Name        | `VARCHAR(100)`| Name of the project            |
| Duration    | `INT`         | Duration of the project        |
| Budget      | `DECIMAL(12,2)` | Budget allocated to the project |

---

### 🔹 `fundingagency` Table
| Column Name | Data Type      | Description               |
|-------------|----------------|---------------------------|
| Agency_ID   | `INT (PK)`     | Unique ID of the agency   |
| Name        | `VARCHAR(100)` | Name of the agency        |
| Address     | `VARCHAR(255)` | Address of the agency     |

---

### 🔹 `employee` Table
| Column Name | Data Type      | Description              |
|-------------|----------------|--------------------------|
| SSN         | `INT (PK)`     | Employee's unique ID     |
| Emp_Name    | `VARCHAR(50)`  | Name of the employee     |
| Salary      | `DECIMAL(10,0)`| Salary of the employee   |

---

### 🔹 `employee_project` Table
| Column Name | Data Type | Description                                |
|-------------|-----------|--------------------------------------------|
| SSN         | `INT (FK)`| Refers to `employee.SSN`                   |
| Project_ID  | `INT (FK)`| Refers to `project.Project_ID`             |
| Manager_SSN | `INT`     | Possibly refers to the managing employee   |

---

### 🔹 `project_manager` Table
| Column Name | Data Type | Description                            |
|-------------|-----------|----------------------------------------|
| Project_ID  | `INT (FK)`| Refers to `project.Project_ID`         |
| Manager_SSN | `INT (FK)`| Refers to `employee.SSN`               |

---

## 🧑‍💻 Use Cases
- Track projects and their budgets
- Manage employee assignments and salaries
- Identify which employee is managing each project
- Maintain relationships with funding agencies

---

## 💾 Technologies Used
- SQL / RDBMS (Any standard SQL database like MySQL, PostgreSQL, etc.)
- Relational schema design principles

---

## ✅ Status
- 📘 Schema designed
- 🛠️ Ready to be implemented in any SQL environment

---

## 📬 Contributions
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📝 License
This project is open source and free to use under the MIT License.
# 🗂️ Database Project – Project Management System

This project represents a **simple relational database schema** for managing projects, funding agencies, employees, and their relationships within an organization. The schema is designed to model real-world project assignment and supervision workflows.

---

## 📌 Overview

The system consists of five main tables:

1. **`project`** – Contains information about each project.
2. **`fundingagency`** – Stores data about agencies funding the projects.
3. **`employee`** – Represents the employees involved in the projects.
4. **`employee_project`** – A relational table that maps employees to the projects they work on.
5. **`project_manager`** – Tracks which employees are managing which projects.

---

## 🧱 Database Schema

### 🔹 `project` Table
| Column Name | Data Type     | Description                    |
|-------------|---------------|--------------------------------|
| Project_ID  | `INT (PK)`    | Unique ID of the project       |
| Name        | `VARCHAR(100)`| Name of the project            |
| Duration    | `INT`         | Duration of the project        |
| Budget      | `DECIMAL(12,2)` | Budget allocated to the project |

---

### 🔹 `fundingagency` Table
| Column Name | Data Type      | Description               |
|-------------|----------------|---------------------------|
| Agency_ID   | `INT (PK)`     | Unique ID of the agency   |
| Name        | `VARCHAR(100)` | Name of the agency        |
| Address     | `VARCHAR(255)` | Address of the agency     |

---

### 🔹 `employee` Table
| Column Name | Data Type      | Description              |
|-------------|----------------|--------------------------|
| SSN         | `INT (PK)`     | Employee's unique ID     |
| Emp_Name    | `VARCHAR(50)`  | Name of the employee     |
| Salary      | `DECIMAL(10,0)`| Salary of the employee   |

---

### 🔹 `employee_project` Table
| Column Name | Data Type | Description                                |
|-------------|-----------|--------------------------------------------|
| SSN         | `INT (FK)`| Refers to `employee.SSN`                   |
| Project_ID  | `INT (FK)`| Refers to `project.Project_ID`             |
| Manager_SSN | `INT`     | Possibly refers to the managing employee   |

---

### 🔹 `project_manager` Table
| Column Name | Data Type | Description                            |
|-------------|-----------|----------------------------------------|
| Project_ID  | `INT (FK)`| Refers to `project.Project_ID`         |
| Manager_SSN | `INT (FK)`| Refers to `employee.SSN`               |

---

## 🧑‍💻 Use Cases
- Track projects and their budgets
- Manage employee assignments and salaries
- Identify which employee is managing each project
- Maintain relationships with funding agencies

---

## 💾 Technologies Used
- SQL / RDBMS (Any standard SQL database like MySQL, PostgreSQL, etc.)
- Relational schema design principles

---

## ✅ Status
- 📘 Schema designed
- 🛠️ Ready to be implemented in any SQL environment

---

## 📬 Contributions
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📝 License
This project is open source and free to use under the MIT License.
![image](https://github.com/user-attachments/assets/9f6adf1e-7e73-40c3-b99f-aef04d481936)
![image](https://github.com/user-attachments/assets/af4f2dc4-9a4e-4702-a3b4-4aef505df348)


