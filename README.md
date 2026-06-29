# Advanced SQL Assignment: CTEs & Window Functions

## Academic Integrity Statement
I affirm that this submission is entirely my own original work conducted in accordance with university academic regulations.

* **Student Name:** [Your Full Name Here]
* **Student ID:** [Your Student ID Here]
* **Course:** C11665 - DPR400210: Database Programming
* **Instructor:** Eric Maniraguha
* **Institution:** UNILAK (University of Lay Adventists of Kigali)

---

## 1. Business Scenario
This project implements a **Hospital Management System** to track clinical operations, doctor-patient assignments, and consultation fees. The database architecture consists of 3 interrelated tables: `Doctors` (featuring a self-referencing administrative hierarchy), `Patients`, and `Appointments`.

### Database ER Diagram
```text
[Doctors] (1) <------- (N) [Appointments] (N) -------> (1) [Patients]
